## Tests
This Recovery is based on SM-S711U, But all testing was conducted on SM-S7110, including orangefox

# Contributors
- (Maxim)[https://github.com/Maxim-Root] - Device Owner & Main Tester
- (Jamie)[https://github.com/SavedByLight] - Maintainer
- (Teamwin Recovery Project)[https://github.com/teamwin]

# Build Command
    export ALLOW_MISSING_DEPENDANCIES=true; bash build/envsetup.sh; lunch twrp_r11q-eng; mka recoveryimage

# What Works?
- Touchscreen
- adb
- adb sideload
- mtp
- USB OTG
- Fastboot
- Temperature
- Battery Percentage
- Backup/Restore
- Flashing zips in recovery
- All Reboot and Power off options

# Known Issues
- Although USB OTG works, @Maxim-Root found it occasionally has a delay mounting.
- Data is not yet decrypted and may not be, we are testing it.

# Contact incase you have any queries
- (Telegram)[https://t.me/+-DAOeMzGrGk1ODli]