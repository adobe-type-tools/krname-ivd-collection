# KRName IVD Collection

The purpose of the KRName IVD Collection, which was submitted for registration as [PRI #351](http://www.unicode.org/ivd/pri/pri351/), is to register IVSes for a small number of variant ideographs that appear in [Korea's official list of hanja](http://help.scourt.go.kr/nm/img/hanja/hanja_2015.pdf) (aka ideographs) for personal names. Note that there is a [text version](https://srad.jp/~yasuoka/journal/589283/) prepared by Koichi Yasuoka, and a [formatted and enhanced PDF version](http://www.unicode.org/L2/L2017/17173-irgn2200-unihan-db.pdf#page=4) prepared by Jaemin Chung. Many thanks to Koichi Yasuoka, Motoko Yasuoka, and Jaemin Chung for preparing materials that made the KRName IVD Collection submission possible.

The provided KRName-Regular.otf OpenType/CFF font and its sources, which are based on [Source Han Serif](https://github.com/adobe-fonts/source-han-serif/), implements the sequences using the next-available VSes. (The font will be updated after this IVD collection has been registered, if the VS assignments change.)

## Font installation instructions

* [macOS](https://support.apple.com/en-us/HT201749)
* [Windows](https://www.microsoft.com/en-us/Typography/TrueTypeInstall.aspx)
* [Linux/Unix-based systems](https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116)

## Building the font from source

### Requirements

To build the binary font file from source, you need to have installed the [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html) (AFDKO). The AFDKO tools are widely used for font development today, and are part of most font editor applications.

### Building the font

In this repository, all necessary files are in place for building the OpenType/CFF font, and the COMMANDS.txt file provides the command lines that are used.

## Getting Involved

Send suggestions for changes to the KRName IVD Collection project maintainer, [Dr. Ken Lunde](mailto:lunde@adobe.com?subject=[GitHub]%20KRName%20IVD%20Collection), for consideration.
