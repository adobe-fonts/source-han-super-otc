# Downloading Source Han Super OTC

Source Han Sans, Source Han Serif, and Source Han Code JP are open source Pan-CJK and Japanese typefaces whose OpenType/CFF fonts and CID-based sources are covered under the terms of the [SIL Open Font License, Version 1.1](http://scripts.sil.org/OFL) (also see the [LICENSE](LICENSE.txt) and [FAQ](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL-FAQ_web)). Here you will find a single OpenType/CFF Collection (aka Super OTC) that includes all 78 fonts from these three typefaces. The 36 [Source Han Sans OTFs](https://github.com/adobe-fonts/source-han-sans/tree/release/OTF), the 28 [Source Han Serif OTFs](https://github.com/adobe-fonts/source-han-serif/tree/release/OTF), and the 14 [Source Han Code JP OTFs](https://github.com/adobe-fonts/source-han-code-jp/tree/release/OTF) are combined into a single OpenType/Collection, and the main intent of this particular oepn source project is to stress-test environments that can consume OpenType/CFF Collections, specifically macOS (OS X) Version 10.8 (aka *Mountain Lion*) or later, iOS 7 or later, or Windows 10 Version 1703 (aka *Creators Update*) or later. For Adobe apps, CS6 or later.

The [COMMANDS.txt](COMMANDS.txt) file provides the command lines that were used to pre-process the 78 OpenType/CFF fonts and to combine them into a single OpenType/CFF Collection.

### Super OTC

[Super OTC Part 1](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.z01) (89,128,960 bytes) + [Super OTC Part 2](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.z02) (89,128,960 bytes) + [Super OTC Part 3](https://github.com/adobe-fonts/source-han-super-otc/raw/master/SourceHan.ttc.zip) (73,863,368 bytes)

The ZIP file for the Super OTC has been necessarily split into three parts, due to GitHub's 100MB file size limit (the Super OTC is 307,876,932 bytes). Unfortunately, the built-in *Archive Utility* app of macOS does not support split ZIP files, and we therefore recommend that you download and install the [Unarchiver](http://unarchiver.c3.cx/unarchiver) app. To unzip, either drag the Part 3 file (the one with the ".zip" filename extension, and named *SourceHan.ttc.zip*) onto the *Unarchiver* app, or use Control-Click to open it by specifying that app (after installing the *Unarchiver* app, you may also be able to simply double-click the Part 3 file). Either of these actions will combine the three parts and unzip them. For Windows, select the Part 3 file, then use the "Extract All" context menu to combine the two parts and unzip them.

## Font installation instructions

* [macOS](https://support.apple.com/en-us/HT201749)
* [Windows](https://www.microsoft.com/en-us/Typography/TrueTypeInstall.aspx)
* [Linux/Unix-based systems](https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116)

## Getting Involved

Send suggestions for changes to the Source Han Super OTC project maintainer, [Dr. Ken Lunde](mailto:lunde@adobe.com?subject=[GitHub]%20Source%20Han%20Super%20OTC), for consideration.

## Further information

For information about the design and background of the Source Han typefaces, please refer to their recpective repositories.
