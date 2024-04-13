# AOSPA flashing kit for MiAtoll

Scripts to flash ROM on windows/mac/linux, including latest platform-tools and drivers, for AOSPA - Xiaomi POCO M2 Pro / Redmi Note 9S / Redmi Note 9 Pro / Redmi Note 9 Pro Max / Redmi Note 10 Lite.

## Steps

1. Download the latest fastboot package from https://paranoidandroid.co/miatoll/
2. Copy it to this folder and rename it to aospa.zip
3. Run install_google_usb_driver (Windows users only; requires admin)
4. Reboot to bootloader (`adb reboot bootloader` OR shutdown phone and long press power + volume down button)
5. Run flash_aospa

### Notes
- `.cmd` scripts are for windows, can be run by right click -> run as administrator.
- `.sh` scripts are for linux and mac, you should know how to use them!
- You may see warnings like `Warning: skip copying xyz image avb footer` while flashing firmware, this is normal and can be ignored safely.
- The device will reboot automatically into "AOSPA Fastboot" (fastbootd) during ROM flash, this is normal and expected behaviour.
- These scripts do not wipe data.
