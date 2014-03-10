rt5390
======

Ralink RT5390 driver compatible with modern (3.13+) Linux kernels.

One patch stolen from [here](http://ubuntuforums.org/showthread.php?t=2160399&p=12732190#post12732190); another (2450-001.patch) - cant remember; I applied it manually.

GCC 4.7 required.

usage:

# make clean

# make

# make install

# modprobe rt5390sta
