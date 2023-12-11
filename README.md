# OPN-OPLL-MegaMod
 OPN+OPLL MegaMod, the latest hardware version has passed hardware verification
 
# 2023.11.25
OPN+OPLL MegaMod v0.3 have passed hardware testing and all functions have been verified. The old version has many problems and is not recommended.  
## OPN+OPLL MegaMod v0.3 includes the following features:
1. OPN and OPLL chips can support playing VGM music of PC-9801-26K, MSX-Music, ZX-Spectrum, and Atari ST. Software driver support provided by natalie.  
2. A typical dual op amp driven by a single 5V (take NE5532 as an example), it works well and sounds loud. It is especially effective for the sound amplification function of OPLL.  
3. Independent volume adjustment knob. Supports adjusting the volume of OPN and SSG, as well as the overall volume of the mixer. The volume of OPLL cannot be adjusted because the volume of OPLL itself is too small. This function is completely normal, and the volumes of each channel will not interfere with each other when adjusting the volume.  
4. SSG can be configured with stereo sound. Use three three-position toggle switches to independently control the stereo channels of each SSG. This function is completely normal and will not affect the volume of OPN and OPLL.
5. SSG stereo mixing circuit. This part is based on the ZX-Spectrum's golden ratio mixing circuit, but I modified the resistor values to provide a more stereo effect.  
6. OPN and OPLL monophonic mixing circuit. Since there is no such combination of using OPN.FM+OPLL at the same time, OPN and OPLL configurable stereo make little sense. A mono mix is used here, which means the left and right channels sound the same.  
7. Compatible with OPLL cloning chip. Just remove the pull-down resistors of the MO and RO analog audio tree pool of YM2413.  
8. Compatible with U3567, UM3567, YM2413-F and YM2413B-F, using a simple conversion board to implement.  

![image](https://github.com/denjhang/OPN-OPLL-MegaMod/blob/main/OPN%2BOPLL%20MegaMod%20v0.3/Actual%20pictures%20front.jpg)
![image](https://github.com/denjhang/OPN-OPLL-MegaMod/blob/main/OPN%2BOPLL%20MegaMod%20v0.3/Actual%20pictures%20back.jpg)

![image](https://github.com/denjhang/OPN-OPLL-MegaMod/blob/main/OPN%2BOPLL%20MegaMod%20v0.3/sshot-20231113-202009.png)
![image](https://github.com/denjhang/OPN-OPLL-MegaMod/blob/main/OPN%2BOPLL%20MegaMod%20v0.3/sshot-20231113-202023.png)
![image](https://github.com/denjhang/OPN-OPLL-MegaMod/blob/main/OPN%2BOPLL%20MegaMod%20v0.3/sshot-20231113-202037.png)
