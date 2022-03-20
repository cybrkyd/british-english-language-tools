
# British English Dictionary

Filename:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;en\_GB.dic and en\_GB.aff<br>
Description:&nbsp;&nbsp;&nbsp;&nbsp;A strict British-English spell checker dictionary.<br>


## Introduction
It is almost impossible to find a purely British-English dictionary or word 
list. By default, Oxford and Cambridge include US/CAD/AUS English variants and 
references in their published dictionaries and on their websites. Further, what 
is often labelled as 'en-GB' is almost always, in fact, International English.

This dictionary aims to include only those words conforming to the preferred 
standard of British-English spelling.

* en\_GB.dic and en\_GB.aff are for Hunspell and derivatives
* british-english-dictionary-darmeth is an extension for Firefox, Thunderbird and SeaMonkey
* The word list which forms the basis of this dictionary is [here](https://github.com/darmeth/british-english-words)

## Installation

### Hunspell

1. On Linux systems, make sure package **hunspell-en-gb** is installed.
2. Download en\_GB.dic and en\_GB.aff and add them to the Hunspell dictionary 
directory, overwriting the existing files. The Hunspell directory is usually 
"/usr/share/hunspell"

You need sudo for this:

    $sudo cp en_GB.dic en_GB.aff /usr/share/hunspell/

### Firefox, Thunderbird, SeaMonkey extension

Please see the [README.md](https://github.com/darmeth/en-GB-dictionary/blob/main/ext-firefox-thunderbird-seamonkey/README.md) file for the extension.


## Licences
en-GB-words and derivatives are available under a [GPL3 licence](https://github.com/darmeth/en-GB-dictionary/blob/main/LICENCE)

