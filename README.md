Droidian on Samsung Galaxy S9 (Qualcomm) (starqlte)
========

Droidian is a GNU/Linux distribution based on top of Mobian, a Debian-based distribution for mobile devices. The goal of Droidian is to be able to run Mobian on Android phones.

## THE INSTRUCTIONS BELLOW WILL WIPE ALL THE DATA ON YOUR DEVICE

# Default password: 1234

## Installation
 * Download the latest build here: https://github.com/droidian-starqlte/droidian-images/releases
 * Unpack the zip file
 * flash this [recovery.img](https://github.com/droidian-starqlte/android_kernel_samsung_sdm845/releases/download/starqlte/recovery.img)
 * Boot to TWRP and in the reboot section boot to fastboot
 * on Linux run flash_all.sh script:
    <pre><code>./flash_all.sh</code></pre>
 * on Windows run flash_all.bat
 * Reboot to system and "DO NOT PRESS THE POWER BUTTON WHEN SCREEN IS BLACK or BLANK, BE PATIENT"
 * Support group: https://t.me/DroidianLinux

## Bugs and workarounds
- Encryption is broken. Device is not unlockable after encryption is enabled.
* Offline charging is broken and will boot the device.
* GPS does not work.
* Fingerprint does not work.
* Only one sim can be used.
