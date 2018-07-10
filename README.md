Latest pre-compiled binary of TBB (2018 - Update 4) for the Raspberry Pi 3.

## Head over to https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB for installing OpenCV (3.4.1 dev) along with TBB (2018-Update 4) for the Raspberry Pi .

# Proof:

![](https://github.com/abhiTronix/TBB_Raspberry_pi/blob/master/Screenshot%20from%202018-04-05%2014-58-08.jpg)
My Proof of work: **TBB (version: 2018 - Update3) installation** .

# Live Performance Benchmarking (check CPU Load) - OpenCV (with TBB):

[![Everything Is AWESOME](https://github.com/abhiTronix/TBB_Raspberry_pi/blob/master/Youtube-video.png)](https://youtu.be/HBxyQU-c62o "Live! Raspberry Pi OpenCV & Dlib Multi-Snapchat Filters Python Implementation [Robust and Fastest]")


# TBB ( Intel(R) Threading Building Blocks )
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# TBB for RPi3
A pre-compiled Latest binary (2018 - Update 4) of TBB for the Raspberry Pi 3. It is available in a ".deb" package and will save you countless hours not having to compile it yourself.  This may or may not stay updated as I have to manually compile this version.  I will try to make available most major versions.  This was compiled on a Raspberry Pi 3 Model B+ running raspbian stretch.  This enables TBB which helps multithreading in many OpenCV algorithms .

# Installation Instructions
## (Tested on Raspberry pi 3 with Raspbian Stretch)
Simple (but straight forward):
```
sudo dpkg -i <path to libtbb-dev_2018-U4_armhf.deb>
sudo ldconfig
```
# Files:
Latest .deb files and full support is only provided through email (*abhi.una12@gmail.com*) . Consider supporting my countless hours of hardwork and helping me out by making small *Donation for my ongoing Independent A.I. Research. Thankyou.*

# Huge thanks to:
https://hackaday.com/2016/12/01/running-intel-tbb-on-a-raspberry-pi/ for guiding me through.

https://github.com/01org/tbb for TBB binaries.

#love from India ;)
