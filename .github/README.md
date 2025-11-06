# My totally unique and definitely independent rEFInd theme

![Screenshot](screenshot.bmp)

## Installation

1. Locate your rEFInd directory:
```bash
cd /boot/efi/EFI/refind # for most linux based systems
```

2. Create the `themes` subdirectory and clone this repo to it:
```bash
sudo mkdir themes
cd themes
git clone https://github.com/miamoremustachio/refind-schmefind.git
```

3. Add the following line at the end of the `refind.conf` file:
```bash
include themes/refind-schmefind/theme.conf
```

## Credits

This theme is a fork of [rEFInd Ambience - Deer and Fireflies](https://github.com/jpmvferreira/refind-ambience-deer-and-fireflies) by [jpmvferreira](https://github.com/jpmvferreira) with negligible config changes.

Wallpaper belongs to [Muhammad Nafay at artstation](https://www.artstation.com/artwork/xgrb2)

## License

All of contents present in this repository are licensed under the MIT license.
