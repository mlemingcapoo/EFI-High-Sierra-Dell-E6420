# EFI-High-Sierra-Dell-E6420
A working (kinda) hackintosh EFI CLOVER folder for Dell Latitude E6420<br>
Version: MacOS High Sierra 10.13.x


What's working:
- bootable (10.13.x)
- usb ports (if <b>USBPorts.kext</b> doesn't work, means if you face "Still waiting for root device" kernel panic, pls use <b>USBInjectAll.kext</B> instead)
- camera
- ethernet
- audio, mic (if not, you will have to change <i>layout-id</i> in config.plist
- touchpad


Not working:
- wifi (becuase i'm not planing to fix wifi. Each laptop has different wifi card. Buy an Usbwifi instead)
- bluetooth (require an unique pcie card as well)
- cardreader (nobody use it)
- adjusting brightness is buggy, but useable
- nvidia (ofc not)


Known issues:
- Sometimes, depend on what you r doing, the system will freeze and the only way to make it work again is hold down the power button to completely shutdown, and reboot. (This is an issue that i don't know how to fix, maybe it's about power management, wrong usb mapping or cpu?. Patching your own DSDT and SSDT, create your own USBPorts.kext may help!)
- MacOS system after install will have different issues, errors, it depends on where you download the <i>macOS installer image</i>
