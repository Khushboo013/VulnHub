# Symfonos-3
16 June 2022
11:02 AM

<img src="symfonos3/media/image1.png" style="width:6.45in;height:2.49167in" />

<img src="symfonos3/media/image2.png" style="width:6.28333in;height:2.00833in" />

<img src="symfonos3/media/image3.png" style="width:6.45833in;height:4.00833in" />

<img src="symfonos3/media/image4.jpeg" style="width:6.41667in;height:1.98333in" />

<img src="symfonos3/media/image5.png" style="width:6.40833in;height:4.78333in" />

<img src="symfonos3/media/image6.jpeg" style="width:6.46667in;height:2.45in" />

<img src="symfonos3/media/image7.png" style="width:6.40833in;height:3.74167in" />

<img src="symfonos3/media/image8.png" style="width:6.45in;height:2.35833in" />

<img src="symfonos3/media/image9.png" style="width:6.2in;height:1.56667in" />

shellshock vulnerability

<img src="symfonos3/media/image10.png" style="width:6.83333in;height:2.175in" />

<img src="symfonos3/media/image11.png" style="width:6.75833in;height:0.775in" />

<img src="symfonos3/media/image12.png" style="width:6.79167in;height:0.5in" />

<img src="symfonos3/media/image13.png" style="width:6.6in;height:1.41667in" />

<img src="symfonos3/media/image14.png" style="width:5.75in;height:1.13333in" />

<img src="symfonos3/media/image15.png" style="width:4.575in;height:2.3in" />

<img src="symfonos3/media/image16.png" style="width:6.05in;height:1.375in" />

<img src="symfonos3/media/image17.png" style="width:6.025in;height:0.74167in" />

after that wait some time to recieve the packet and press ctrl+c
tranfer to the main machine and analysi
the file.pcap

<img src="symfonos3/media/image18.png" style="width:3.7in;height:1.15833in" />

<img src="symfonos3/media/image19.png" style="width:4.65833in;height:1.78333in" />

we get the password now log into the user

<img src="symfonos3/media/image20.png" style="width:4.58333in;height:1.34167in" />

<img src="symfonos3/media/image21.png" style="width:5.81667in;height:4.65833in" />

we can see ftpclient.py has root privilege

so i change the ftplib file from python that was import

The only interesting thing we know about the system is that there’s file called ftpclient.py in /opt/ftpclient/ running as root, we saw that in pspy output. And it connects with ftp using ftplib.py. If we can edit that(ftplib.py)imported file we can get a root reverse shell through that.**

But first we should see if we have permission to edit python libraries or not.

<img src="symfonos3/media/image22.png" style="width:5.38333in;height:2.375in" />

Now just wait for sometime(or run some random commands to speed up the process) and we’ll have the root reverse shell

<img src="symfonos3/media/image23.png" style="width:6.4in;height:1.33333in" />

<img src="symfonos3/media/image24.png" style="width:6.325in;height:2.875in" />

<img src="symfonos3/media/image25.png" style="width:6.21667in;height:3.90833in" />

<img src="symfonos3/media/image26.png" style="width:0.15833in;height:0.41667in" /><img src="symfonos3/media/image27.png" style="width:0.15833in;height:0.41667in" />
