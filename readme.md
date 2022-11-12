# HP 250 G5 Hackintosh
## Things that don't work (for Monterey)  
* wireless internet (intel card) --*ethernet does work, however*
* bluetooth - use [snapdrop](https://snapdrop.io)

If you want the wifi and bluetooth to work and are fine using Big Sur use [L9PYKE's EFI](https://github.com/L9PYKE/HPG5250BIGSUR)

## After downloading EFI
* create your own USB map using [USBToolBox](https://github.com/USBToolBox/tool) [helpful tutorial](https://lzhoang2601.github.io/) by Hoàng Hồng Quân (your selection of ports may not be the same as mine)
* use GenSMBIOS to generate your SMBIOS following the dortania guide 

## Upcoming release in November 👀
Opencore 0.8.6 is out! New EFI in development! VENTURA!

* macrecovery command: python ./macrecovery.py -b Mac-B4831CEBD52A0C4C -m 00000000000000000 download
