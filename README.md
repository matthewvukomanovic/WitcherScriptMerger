# Script Merger for The Witcher 3 - Vortex edition

Special thanks to AnotherSymbiote for creating this tool and giving us permission to fiddle with it.
You can find the original repo here: https://github.com/AnotherSymbiote/WitcherScriptMerger/

This fork has been created to cater for/fix any issues that arise when using this tool alongside Vortex Mod Manager.


As specified by the original creator, this tool:
- Checks your Mods folder for mod conflicts.  Uses [QuickBMS](http://aluigi.altervista.org/quickbms.htm) to scan .bundle packages.
- Merges .ws scripts or .xml files inside bundle packages using the powerful open-source merge tool [KDiff3](http://kdiff3.sourceforge.net/).
- Packages new .bundle packages using the official mod tool [wcc_lite](http://www.nexusmods.com/witcher3/news/12625/?).
- Detects updated merge source files using the [xxHash](https://github.com/Cyan4973/xxHash) algorithm by Yann Collet, [implemented in .NET](https://github.com/wilhelmliao/xxHash.NET) by Wilhelm Liao.

**KDiff3 & other external binary dependencies aren't included in this source code.**
