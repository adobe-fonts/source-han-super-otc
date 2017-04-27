# Downloading Source Han Super OTC

The Adobe-branded Source Han Sans, Source Han Serif, and Source Han Code JP, along with the Google-branded Noto Sans CJK and Noto Serif CJK, are open source Pan-CJK and Japanese (Source Han Code JP) typefaces whose OpenType/CFF fonts and CID-based sources are covered under the terms of the [SIL Open Font License, Version 1.1](http://scripts.sil.org/OFL) (also see the [LICENSE](LICENSE.txt) and [FAQ](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL-FAQ_web)).

In this project you will find six ready-to-install OpenType/CFF Collections (aka Super OTCs) that include 64, 78, or 142 fonts depending on which of the five typeface families are included, along with versions that lack the 'SVG ' table.

The Super OTCs include various combinations of the 36 [Source Han Sans OTFs](https://github.com/adobe-fonts/source-han-sans/tree/release/OTF), the 28 [Source Han Serif OTFs](https://github.com/adobe-fonts/source-han-serif/tree/release/OTF), the 14 [Source Han Code JP OTFs](https://github.com/adobe-fonts/source-han-code-jp/tree/release/OTF), and the 64 [Noto Sans CJK and Noto Serif CJK OTFs](https://github.com/googlei18n/noto-cjk). The main intent of this particular open source project is to stress-test environments that consume OpenType/CFF Collections, specifically macOS (OS X) Version 10.8 (aka *Mountain Lion*) or later, iOS 7 or later, Windows 10 Version 1703 (aka *Creators Update*) or later, flavors of Linux that use *fontconfig* and FreeType Version 2.5.0.1 or greater, and Adobe CS6 apps or later.

The [COMMANDS.txt](COMMANDS.txt) file provides the command lines that were used to pre-process the 142 OpenType/CFF fonts and to combine them into six different OpenType/CFF Collections.

## Super OTC ZIP Files

**Special Note**: The ZIP files for the Super OTCs have been necessarily split into three parts, due to GitHub's 100MB file size limit. Unfortunately, the built-in *Archive Utility* app of macOS does not support split ZIP files, and we therefore recommend that you download and install the [Unarchiver](http://unarchiver.c3.cx/unarchiver) app. To unzip, either drag the Part 3 file (the one with the ".zip" filename extension, and named *SourceHan.ttc.zip* *NotoCJK.ttc.zip*, or *SourceHanNotoCJK.ttc.zip*) onto the *Unarchiver* app, or use Control-Click to open it by specifying that app (after installing the *Unarchiver* app, you may also be able to simply double-click the Part 3 file). Either of these actions will combine the three parts and unzip them. For Windows, select the Part 3 file, then use the "Extract All" context menu to combine the three parts and unzip them. For Ubuntu and possibly other flavors of Linux, try using "cat" to combine the three parts into a large ZIP file, then use "unzip" to decompress, ignoring any warning messages (use the file sizes and MD5 hashes provided below to confirm).

### Source Han

This Super OTC includes 78 fonts, is 307,876,932 bytes, and its MD5 hash is eab487461fb2ab15f91c5427d54fd279.

[Super OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.z01) (89,128,960 bytes) + [Super OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.z02) (89,128,960 bytes) + [Super OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.zip) (73,863,368 bytes)

This Super OTC is the same as above, but lacks an 'SVG ' table, is 307,870,132 bytes, and its MD5 hash is d5c776896707b7feb27fdd9dab86ff27.

[Super OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NoSVG/SourceHan.ttc.z01) (89,128,960 bytes) + [Super OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NoSVG/SourceHan.ttc.z02) (89,128,960 bytes) + [Super OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NoSVG/SourceHan.ttc.zip) (73,859,654 bytes)

### Noto CJK

This Super OTC includes 64 fonts, is 277,453,112 bytes, and its MD5 hash is 406e56bd28ac2c8854909b90b3e0cef2.

[Super OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NotoCJK.ttc.z01) (89,128,960 bytes) + [Super OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NotoCJK.ttc.z02) (89,128,960 bytes) + [Super OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NotoCJK.ttc.zip) (47,713,879 bytes)

### Source Han + Noto CJK

This Super OTC includes 142 fonts, is 308,096,324 bytes, and its MD5 hash is 2120d019397b39a9cd929339e020c7c9.

[Super OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHanNotoCJK.ttc.z01) (89,128,960 bytes) + [Super OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHanNotoCJK.ttc.z02) (89,128,960 bytes) + [Super OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHanNotoCJK.ttc.zip) (73,872,402 bytes)

This Super OTC is the same as above, but lacks an 'SVG ' table, is 308,089,524 bytes, and its MD5 hash is d8da0f38789fa14dee770e375dc3164d.

[Super OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NoSVG/SourceHanNotoCJK.ttc.z01) (89,128,960 bytes) + [Super OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NoSVG/SourceHanNotoCJK.ttc.z02) (89,128,960 bytes) + [Super OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/NoSVG/SourceHanNotoCJK.ttc.zip) (73,868,701 bytes)

## Font installation instructions

* [macOS](https://support.apple.com/en-us/HT201749)
* [Windows](https://www.microsoft.com/en-us/Typography/TrueTypeInstall.aspx)
* [Linux/Unix-based systems](https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116)

## Getting Involved

Send suggestions for changes to the Source Han Super OTC project maintainer, [Dr. Ken Lunde](mailto:lunde@adobe.com?subject=[GitHub]%20Source%20Han%20Super%20OTC), for consideration.

## Further information

For information about the design and background of the Source Han typefaces, please refer to their respective repositories.
