Latest pre-compiled binary of TBB (2018 - Update 6) for the Raspberry Pi.

## Head over to https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB for installing Pre-released OpenCV (4.0.0)/Stable OpenCV (3.4.3) along with TBB (2018-Update 6) for the Raspberry Pi .

# TBB ( Intel(R) Threading Building Blocks )
![Github](https://img.shields.io/badge/TBB-2018%20Update%206-blue.svg?longCache=true&style=for-the-badge)
<t>![Github](https://img.shields.io/badge/Files-Available-green.svg?longCache=true&style=for-the-badge)<br>
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# TBB for Raspberry Pi
A pre-compiled Latest binary (2018 - Update 6) of TBB for the Raspberry Pi built from scratch inorder to achieve max multi-threaded performance. It is available in a ".deb" package and will save your countless hours as not have to compile it yourself. There is no other Latest source of TBB file for raspberry pi available besides this on internet ;). This may or may not stay updated as I have to manually compile this version.  I will try to make available most major versions.  This was compiled on a **Raspberry Pi 2/3 Model B/B+ running raspbian Stretch**.  This enables TBB which helps multithreading in many OpenCV algorithms. There is no latest source of TBB for Rpi on internet so i decided to create my own as part of my research. Hope this helps you, Cheers.

# Proof:
![](https://github.com/abhiTronix/TBB_Raspberry_pi/blob/master/proof1.png)
Files: **TBB (version: 2018 - Update-2 to Update-6) files on my machine.** .
<br>
<br>
![](https://github.com/abhiTronix/TBB_Raspberry_pi/blob/master/new.gif)
My Proof of work: **TBB (version: 2018 - Update 4) installation** .
<br>
<br>
# Live Performance Benchmarking (check CPU Load) - OpenCV (with TBB):

[![Everything Is AWESOME](https://github.com/abhiTronix/TBB_Raspberry_pi/blob/master/Youtube-video.png)](https://youtu.be/HBxyQU-c62o "Live! Raspberry Pi OpenCV & Dlib Multi-Snapchat Filters Python Implementation [Robust and Fastest]")


# Installation Instructions
## (Tested on Raspberry pi with Raspbian Stretch)
Simple (but straight forward):
```
sudo dpkg -i <path to libtbb-dev_2018-U6_arm.deb>
sudo ldconfig
```
# Files:
Tryout **Old TBB file (as a demo)** is available ![libtbb-dev_4.5-1_armhf.deb](https://github.com/abhiTronix/TBB_Raspberry_pi/blob/master/libtbb-dev_4.5-1_armhf.deb).<br>

**But if you want the latest .deb files and full installation support associated, it is only provided through email (*abhi.una12@gmail.com*)**. Also consider supporting my countless hours of hardwork and helping me out by making small *Donation for my ongoing Independent A.I. Research in return. Thankyou.

# Huge thanks to:
https://hackaday.com/2016/12/01/running-intel-tbb-on-a-raspberry-pi/ for guiding me through.

https://github.com/01org/tbb for TBB binaries.

#love from India ;)
