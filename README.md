# Yamaha RX-V Device Type
This is a networked receiver device type for SmartThings.  It allows you to change the input, adjust the volume, mute and turn off/standby your receiver via a SmartApp or the SmartThings UI.

I losely based some of the workings on <a href='http://openremote.org/display/forums/Controlling++RX+2065+Yamaha+Amp'>OpenRemote</a> and <a href='https://github.com/BirdAPI/yamaha-network-receivers'>EventGhost</a>.  However, everything in this implementation works for my receiver, the RX-V675.

##Supported Models
 * RX-V371, RX-V373, RX-V375, RX-V377
 * RX-V471, RX-V473, RX-V475, RX-V477
*  RX-V571, RX-V573, RX-V575, RX-V575
 * RX-V671, RX-V673, RX-V675, RX-V677
 * RX-V771, RX-V773, RX-V775, RX-V777
 * RX-V871, RX-V873, RX-V875, RX-V877
 * RX-A3020, RX-A2020, RX-A1020, RX-A820, RX-A720
 * RX-A3010, RX-A2010, RX-A1010, RX-A810, RX-A710
 * RX-A3000, RX-A2000, RX-A1000
 * RX-V3073, RX-V2073, RX-V1073
 * RX-V3071, RX-V2071, RX-V1071
 * RX-V3067, RX-V2067, RX-V1067, RX-V867
 * RX-V2065, RX-V3900, DSP-AX3900, RX-Z7, DSP-Z7
 * HTR-7065, HTR-6065, HTR-5065, HTR-4065
 * HTR-6064
 * HTR-9063, HTR-8063, HTR-6295
 
 I also suspect it could be easily modified for some other recievers. 

##Potential Bugs
I noticed the XPATH was different for Volume Up / Down between my implementation and OpenRemote's forum post.  They may have implemented it differently, or Yamaha may have changed the command.  

##License 
Copyright (c) 2015, Kristopher Kubicki
All rights reserved.
