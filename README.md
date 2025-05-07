# Contributions
- [Maxim](https://github.com/Maxim-Root) - Device Owner & Main Tester
- [Jamie](https://github.com/SavedByLight) - Maintainer
- [Teamwin Recovery Project](https://github.com/teamwin)

Blocking checks
- [x] Correct screen/recovery size
- [x] Working Touch, screen
- [x] Backup to internal/microSD (NO SDCARD SLOT)
- [x] Restore from internal/microSD (NO SDCARD SLOT)
- [x] reboot to system
- [x] ADB

Medium checks
- [x] update.zip sideload
- [x] UI colors (red/blue inversions)
- [x] Screen goes off and on
- [x] F2FS/EXT4 Support, exFAT/NTFS where supported
- [x] all important partitions listed in mount/backup lists
- [x] backup/restore to/from external (USB-OTG) storage (not supported by the device)
- [#] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [ ] decrypt /data (Probably can't be fixed)
- [x] Correct date

Minor checks
- [x] MTP export
- [x] reboot to bootloader [Download Mode]
- [x] reboot to recovery
- [x] poweroff
- [x] battery level
- [x] temperature
- [x] encrypted backups
- [x] input devices via USB (USB-OTG) - keyboard, mouse and disks (not supported by the device)
- [x] USB mass storage export
- [x] set brightness
- [-] vibrate (TW_NO_HAPTICS)
- [x] screenshot
- [-] partition SD card [NOT SUPPORTED BY DEVICE, NO SDCARD SLOT]