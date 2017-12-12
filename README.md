# tbb_raspberry_pi
Latest pre-compiled binary of TBB (2018-Update 2) for the Raspberry Pi 3

# TBB ( Intel(R) Threading Building Blocks )
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# TBB for RPi3
A pre-compiled Latest binary (2018 Update 2) of TBB for the Raspberry Pi 3. It is available in a ".deb" package and will save you countless hours not having to compile it yourself.  This may or may not stay updated as I have to manually compile this version.  I will try to make available most major versions.  This was compiled on a Raspberry Pi 3 Model B+ running raspbian stretch.  This enables TBB which helps multithreading in many OpenCV algorithms .

# Installation Instructions
0) Simple (but straight forward):
  ```
sudo dpkg -i <path to libtbb-dev_2018-U2_armhf.deb>
sudo ldconfig
  ```
# Huge thanks to:
https://hackaday.com/2016/12/01/running-intel-tbb-on-a-raspberry-pi/ for guiding me through.

https://github.com/01org/tbb for TBB binaries.
