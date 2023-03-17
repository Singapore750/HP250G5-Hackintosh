# HP 250 G5 Hackintosh


## After downloading EFI
* create your own USB map using [USBToolBox](https://github.com/USBToolBox/tool) [helpful tutorial](https://lzhoang2601.github.io/) by Hoàng Hồng Quân (your selection of ports may not be the same as mine)
* use GenSMBIOS to generate your SMBIOS following the dortania guide 

## The latest
Opencore 0.8.7 is out! 
Big Sur EFI released!
Trackpad and wireless both work. I used to have a problem where I could get one or the other to work but not both. Big Sur is very stable and doesn't cause many issues. 
* macrecovery commands: 
** macOS 13 Ventura - python ./macrecovery.py -b Mac-B4831CEBD52A0C4C -m 00000000000000000 -os latest download
** macOS 12 Monterey - python ./macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 download
** macOS 11 Big Sur -  python macrecovery.py -b Mac-42FD25EABCABB274 -m 00000000000000000 download
 
  Sourced from Dortania guide 
  HAPPY NEW YEAR!!! Opencore 0.8.8 will come out soon. Expect updates soon!



## Es posible que suba un nuevo update...Asegúrense de que hubieran starred mi repo
Mil disculpas por la tardanza...
si tengo bastante estrellas...tal vez pudiere hacer un EFI para macOS 14... pero dudo mucho de que mi computadora sea compatible
hasta entonces



