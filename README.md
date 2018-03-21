### Main Source
https://github.com/NTT123/Hackintosh-HP-Z420-MacOS-High-Sierra-10.13

### Boot
* Clover options `npci=0x2000 dart=1 nv_disable=1`
* Change SMBIOS options using details in  `resources/config.plist`

### USB Commands

#### Format Options
* `diskutil list`
* `diskutil eraseDisk HFS+ <Name> GPT /dev/<disk>`