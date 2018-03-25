# Downloading Source Han &amp; Noto CJK Mega/Ultra OTCs

The Adobe-branded *Source Han Sans*, *Source Han Serif*, and *Source Han Code JP*, along with the Google-branded *Noto Sans CJK* and *Noto Serif CJK*, are open source Pan-CJK and Japanese (*Source Han Code JP*) typefaces whose OpenType/CFF fonts and CID-based sources are covered under the terms of the [SIL Open Font License, Version 1.1](http://scripts.sil.org/OFL) (also see the [LICENSE](LICENSE.txt) and [FAQ](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL-FAQ_web)).

In this project you will find three ready-to-install OpenType/CFF Collections (aka Mega and Ultra OTCs) that include 64, 78, or 142 fonts depending on which of the five typeface families are included.

The Mega and Ultra OTCs include various combinations of the 36 [Source Han Sans OTFs](https://github.com/adobe-fonts/source-han-sans/tree/release/OTF), the 28 [Source Han Serif OTFs](https://github.com/adobe-fonts/source-han-serif/tree/release/OTF), the 14 [Source Han Code JP OTFs](https://github.com/adobe-fonts/source-han-code-jp/tree/release/OTF), and the 64 [Noto Sans CJK and Noto Serif CJK OTFs](https://github.com/googlei18n/noto-cjk). The main intent of this particular open source project is to stress-test environments that consume OpenType/CFF Collections, specifically macOS (OS X) Version 10.8 (aka *Mountain Lion*) or later, iOS 7 or later, Windows 10 Version 1703 (aka *Creators Update*) or later, flavors of Linux that use *fontconfig* and FreeType Version 2.5.0.1 or greater, and Adobe CS6 apps or later.

The [COMMANDS.txt](COMMANDS.txt) file provides the command lines that were used to pre-process the 142 OpenType/CFF fonts and to combine them into three different OpenType/CFF Collections.

## Mega &amp; Ultra OTC ZIP Files

**Special Note**: The ZIP files for the Mega and Ultra OTCs have been necessarily split into three parts, due to GitHub's 100MB file size limit. Unfortunately, the built-in *Archive Utility* app of macOS does not support split ZIP files, and we therefore recommend that you download and install the [Unarchiver](http://unarchiver.c3.cx/unarchiver) app. To unzip, either drag a Part 3 file (the one with the ".zip" filename extension, and named *SourceHan.ttc.zip* *NotoCJK.ttc.zip*, or *SourceHanNotoCJK.ttc.zip*) onto the *Unarchiver* app, or use Control-Click to open it by specifying that app (after installing the *Unarchiver* app, you may also be able to simply double-click a Part 3 file). Either of these actions will combine the three parts and unzip them. For Windows, select a Part 3 file, then use the "Extract All" context menu to combine the three parts and unzip them. For Ubuntu and possibly other flavors of Linux, we recommend that you download and install the [Unarchiver command-line tools](https://unarchiver.c3.cx/commandline), then simply execute the *unar* command with a Part 3 file as its argument.

## Mega OTCs

### Source Han

This Mega OTC includes 78 fonts, is 307,983,900 bytes, and its MD5 hash is 95d976a8594af2764e33f9b8e0139192.

[Source Han Mega OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.z01) (89,128,960 bytes) + [Source Han Mega OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.z02) (89,128,960 bytes) + [Source Han Mega OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.zip) (73,962,052 bytes)

### Noto CJK

This Mega OTC includes 64 fonts, is 277,560,080 bytes, and its MD5 hash is c3f1d474597f5345760748f34537eeb5.

[Noto CJK Mega OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NotoCJK.ttc.z01) (89,128,960 bytes) + [Noto CJK Mega OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NotoCJK.ttc.z02) (89,128,960 bytes) + [Noto CJK Mega OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NotoCJK.ttc.zip) (47,817,104 bytes)

## Ultra OTC

### Source Han + Noto CJK

This Ultra OTC includes 142 fonts, is 308,203,516 bytes, and its MD5 hash is c01f4a60cee523104f9c936cf8a2df2f.

[Ultra OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHanNotoCJK.ttc.z01) (89,128,960 bytes) + [Ultra OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHanNotoCJK.ttc.z02) (89,128,960 bytes) + [Ultra OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHanNotoCJK.ttc.zip) (73,973,121 bytes)

## Font installation instructions

* [macOS](https://support.apple.com/en-us/HT201749)
* [Windows](https://www.microsoft.com/en-us/Typography/TrueTypeInstall.aspx)
* [Linux/Unix-based systems](https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116)

### Alternative instruction

For Homebrew and Linuxbrew users,

```shell
$ brew tap caskroom/fonts # Homebrew (see https://github.com/caskroom/homebrew-fonts)
$ brew tap asciian/fonts # Linuxbrew (see https://github.com/asciian/homebrew-fonts)
$ brew cask install font-source-han-noto-cjk
```

## Getting Involved

Send suggestions for changes to the Source Han &amp; Noto CJK Mega/Ultra OTCs project maintainer, [Dr. Ken Lunde](mailto:lunde@adobe.com?subject=[GitHub]%20Source%20Han%20Super%20OTC), for consideration.

## Further information

For information about the design and background of the Source Han typefaces, please refer to their respective repositories.
