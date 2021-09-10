# Introduction
Currently tested and working on MacOS Catalina 10.15.6 (Maybe worked with other or newer version).
Using OpenCore 0.6.8

## What's Working
- QE/CI (Graphic Acceleration, Intel UHD 620)
- Audio Speaker (Realtek ALC256 Layout 66 or 21)
- Audio Jack & Mic (Verbstub Kext - Choose Headset on Popup)
- Battery Indicator
- HDMI + Audio
- Camera
- Brightness (F3 & F4)
- Touchpad (I2C)
- USB Port (1xUSB 2.0, 2xUSB 3.0, 1xUSB Type C)
- Intel Wifi + Bluetooth (AC7265 itlwm + Heliport)
- SD Card Reader
- Sleep, Shutdown, Restart

## Not Working
- NVIDIA MX150 (Disabled, Unsupported)
- Internal Mic
- Fingerprint (Disabled, Unsupported)

## Notes
- Make sure to generate your own `PlatformInfo` on config.plist
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo

## Useful Links
- https://github.com/hackintosh-stuff/ComboJack?fbclid=IwAR3OdPNIv6gm6JJgruYvS07hB41cD0UqMQolJqNAVY5BxkyucZizhtZhpfo
- https://awesomeopensource.com/project/daliansky/XiaoMi-Pro-Hackintosh
- https://github.com/linhnguyen-gt/Hackintosh-Acer-Swift3-SF315-52G
