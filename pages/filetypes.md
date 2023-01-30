# File Formats (WIP)

Documentation on file formats found in the Yo-kai Watch games. Almost all of these
warrant their own page at some point, with more information about the file structure. 

## .cfg.bin
Magic Number: N/A

These files are generally used to store information such as NPC/game dialoge, 
items sold at stores, objects on the map, and much more.

For just editing dialoge, the [original Kuriimu](https://github.com/IcySon55/Kuriimu) 
works well, but for others you may need to use [CfgBinEditor](https://github.com/togenyan/CfgBinEditor), 
which does require some basic Node.js knowlage to get running, and the tool itself 
is also very much incomplete.

## .fa
Magic Number: `ARC0` (Ascii)

The archive format that is used by many Level-5 games, including all Yo-kai Watch games. 
[Kuriimu2](https://github.com/FanTranslatorsInternational/Kuriimu2) is able to extract and 
repack these archives.


