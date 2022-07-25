# Read Me

I am using Quartus Prime Version 20.1.0 Lite Edition 
on a Windows 11 Machine

<br>
<br>

I have also installed Linux Support for Windows using Docker Desktop so that I can work on creating Embedded Linux Images using the Linux Console.

<br>
<br>

However, just to be safe that if this setup does not work, I will be also setting up a Ubuntu 20 Machine on a Virtual Box.

<br>
<br>

## Installed Ubuntu on Virtual Box
<hr>
To avoid lagging -

```
bcdedit /set hypervisorlaunchtype off
```
Note that it disables Docker!

To turn it back on 
```
bcdedit /set hypervisorlaunchtype auto
```

## First Link to Obtain Further Documentation
<hr>
As the first step, I started referring to the documentation on Terasic Nano DE10's Home Page :

[https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=205&No=1046&PartNo=4#contents]()

<br>
<br>

## For Drivers Installation I Followed the Following
<hr>

Driver Installation Guide :

https://www.terasic.com.tw/wiki/Intel_USB_Blaster_II_Driver_Installation_Instructions

Troubleshooting For Windows :

https://www.intel.com/content/www/us/en/support/programmable/articles/000085878.html

Substitute 'usb-blaster-ii.inf' and 'usb-blaster-ii.cat' files in '<Quartus Installation Path>\quartus\drivers\usb-blaster-ii' folder
with the one's [Here](https://www.intel.com/content/dam/support/us/en/programmable/kdb/support/knowledge-center/tools/2021/usb-blaster-ii-update.zip)

<br>
<br>

# My Updates

## Update 1 - Hello World

To get started with the FPGA, I follow the instructions in pdf [My First FPGA](https://www.terasic.com.tw/cgi-bin/page/archive_download.pl?Language=English&No=1046&FID=86a1c2f74b7ff8a8abf58d2b4689d4be)

The first program is in 
[Work\01_HelloWorld]()


<br>
<br>


## Update 2 - Connect to the terminal of Linux Booted on the device

Install the drivers from - <br> 
[https://ftdichip.com/wp-content/uploads/2021/08/CDM212364_Setup.zip](https://ftdichip.com/wp-content/uploads/2021/08/CDM212364_Setup.zip)

And Use Putty To Connect to the COM Port at Baud Rate 115200

UserName : root 

And no password

You can follow the instructions given here if any doubt
[Getting_Started_Guide.pdf](https://www.terasic.com.tw/cgi-bin/page/archive_download.pl?Language=English&No=1046&FID=753abb03f323f8f2135130881425ee7b)


<br>
<br>
