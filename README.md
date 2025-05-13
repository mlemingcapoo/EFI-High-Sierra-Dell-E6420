# EFI-High-Sierra-Dell-E6420
Hackintosh EFI CLOVER folder for Dell Latitude E6420<br>
Version: MacOS High Sierra 10.13.x


What's working:
- bootable (10.13.x)
- usb ports (if <b>USBPorts.kext</b> doesn't work, means if you face "Still waiting for root device" kernel panic, pls use <b>USBInjectAll.kext</B> instead)
- camera
- ethernet
- audio, mic (if not, you will have to change <i>layout-id</i> in config.plist
- touchpad


Not working:
- wifi (Each laptop has different wifi card. You're on your own)
- bluetooth (require supported wifi card)
- cardreader
- adjusting brightness is buggy
- nvidia 


Known issues:
- Sometimes, depends on what you are doing, the system will freeze and the only way to make it work again is hold down the power button to completely shutdown, and reboot. I literally have no idea what went wrong and the only way is to disable gpu acceleration
