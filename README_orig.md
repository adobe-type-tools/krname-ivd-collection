# KRName IVD Collection

The purpose of the _KRName_ IVD (_Ideographic Variation Database_) Collection, which was registered in the [2017-12-12](https://unicode.org/ivd/data/2017-12-12/) version of the IVD, is to register IVSes for a small number of ideograph variants that appear in [Korea's official list of hanja](https://help.scourt.go.kr/nm/images/hanja/hanja_2015.pdf) (aka ideographs) for personal names. Note that there is a [text version](https://srad.jp/~yasuoka/journal/589283/) prepared by Koichi Yasuoka, and a [formatted and enhanced PDF version](http://www.unicode.org/L2/L2017/17173-irgn2200-unihan-db.pdf#page=4) prepared by Jaemin Chung. Many thanks to Koichi Yasuoka, Motoko Yasuoka, and Jaemin Chung for preparing materials that made the _KRName_ IVD Collection possible.

The provided _KRName-Regular.otf_ OpenType/CFF font and its sources, which are based on [_Source Han Serif_](https://github.com/adobe-fonts/source-han-serif/), support the _KRName_ IVD Collection, and this font serves as an example implementation.

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

Suggest changes by submitting an [Issue](https://github.com/adobe-type-tools/krname-ivd-collection/issues).
