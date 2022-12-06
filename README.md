# Files for Finnish hyphenation and spelling in Affinity Publisher

This repository conntains 3 files needed in Affinity Publisher to hyphenate and spell check Finnish language. Files have been forked from https://www.apt-browse.org/browse/debian/wheezy/main/all/myspell-fi/0.7-18/file/usr/share/hunspell. At the moment original hunspell dictionary contains some repeating and unsorted word blocks. Removed in this repository.

The`fi_FI.aff` file contains basic information how Finnish words are consturcted. In the begining there is an instruction to set a correct character set. Original files use UTF8 encoding. According to tests I have been able to conduct UTF8 works well with Finnish Windows 10. There may be other sources of these files with ISO

The `fi_FI.dic` file is a bag of Finnish words. There is a word counter at the beginig of the file. Affinity Publisher does not update this file. If you teach new words to Publisher they are stored elswhere not in this file.

The `hyph_fi_FI.dic` file contains instructions how to split words for hyphens. There is also a character set definition at the 1st row. If any problems when hyphenating scandinavian letters change this to UTF8.

You can download dictionary files by clicking the green Code button on top right hand corner. Unzip contents to Affinitys Dictionaries folder. You can find this location in the app from `Edit - Preferences - Tools`

![image](https://user-images.githubusercontent.com/24242044/205483402-095cd467-d668-45f7-826c-2dee38fca26b.png)

Open the folder by clicking `Open` then copy unzipped files. Change the character set if needed.

