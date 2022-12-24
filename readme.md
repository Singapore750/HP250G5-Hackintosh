# HP 250 G5 Hackintosh


## After downloading EFI
* create your own USB map using [USBToolBox](https://github.com/USBToolBox/tool) [helpful tutorial](https://lzhoang2601.github.io/) by Hoàng Hồng Quân (your selection of ports may not be the same as mine)
* use GenSMBIOS to generate your SMBIOS following the dortania guide 

## The latest
Opencore 0.8.7 is out! 
Big Sur EFI released!
Trackpad and wireless both work. I used to have a problem where I could ghet one or the other to work but not both. Big Sur is very stable and doesn't cause many issues. 
* macrecovery command: python ./macrecovery.py -b Mac-B4831CEBD52A0C4C -m 00000000000000000 download
I am now working on EFI's for Monterey and Ventura. Ventura EFI should be out after the Opencore guide is updated with Ventura instructions.

## Problem with Monterey
* Sometimes it will say that a drive is missing and that it has encountered a datal error. To fix this just power off the computer and boot from USB again. 
