# dump-fixing-tools
Tools for fixing bad disc/ROM/etc dumps so that they match the hash of a proper dump listed in e.g. Redump or No-Intro. Contributions welcome.

## General
 - [findcrcs](https://github.com/claunia/findcrcs) - GUI/further automation tool:  [GUI for FindCRCs](http://forum.redump.org/topic/14688/gui-for-findcrcs/).
 - [find-ends](https://github.com/hcs64/find-ends) - Rebuild the missing ends of files, given the expected complete CRC32 and another file to search for the missing parts.
 - [crcoffset](https://github.com/hcs64/crcoffset) - Adjust padding to match a file known only by CRC and size
 - [bitflipper](https://github.com/conorpp/bitflipper) - Brute force bit flips in a file to match a hash. I've confirmed it can be sped up significantly by adding CRC32 pre-check to the code, but I don't know how to modify the code properly.		
 - [rdiff](https://github.com/librsync) - Allows people to share differences between a file, without either person needing to send a whole file - good for cautious dumpers, if a similar dump to the MIA one is non-MIA.	([tutorial + windows build zip with required dll included](https://gist.github.com/mariomadproductions/a1c4335f5a770f38a924c657e5929797))
 - [ReScene](http://rescene.wikidot.com/)
			
Manual tools:
 - [HxD](https://mh-nexus.de/en/hxd/) - Or hex editor of your choice	
			
## Discs
### General
 - [ResurrectSkeleton](https://github.com/Deterous/ResurrectSkeleton) - Rebuilds a CD image given a redumper skeleton and extracted files
 - [fix_xa_submode_and_rebuild_ecc_edc](https://discord.com/channels/631875781563252784/1067102085960704020/1428468415844057088)

Manual tools:
 - CDMage			
 - [ISOBuster](https://www.isobuster.com/)			
 - [CueTools](http://cue.tools/wiki/Main_Page)			
 - [Official flac tools](https://xiph.org/flac/documentation_tools.html) - or [FlacFrontend](https://flacfrontend.sourceforge.net/)
 - Descramble_CDDA

### IBM PC
#### Windows
 - [autorun-inf-fuzzer](https://github.com/DopefishJustin/autorun-inf-fuzzer) - Brute-force an AUTORUN.INF file to match a hash.

### Sony - PlayStation
 - [PSXt001z](https://github.com/Dremora/psxt001z)

### Sony - PlayStation 3
 - [LibIRD](https://github.com/Deterous/LibIRD) - Rebuild ISO from loose files and IRD file

### Sega Dreamcast
 - [TOSEC 2 Redump](http://forum.redump.org/topic/17099/dreamcast-tosec-2-redump-and-vice-versa-dumps-converter/) - Convert from TOSEC to Redump format

### Microsoft - Xbox and Xbox 360
 - [XboxKit](https://github.com/Deterous/XboxKit) - Rebuild ISO from XISO and sidecar files

### Wii U
- [WudCompress](https://gbatemp.net/threads/wii-u-image-wud-compression-tool.397901/) - decompress from unofficial WUX compression format

## Carts
### General/Multiple
 - [ucon64](https://ucon64.sourceforge.io/)

### Nintendo DS
 - [NDecrypt](https://github.com/SabreTools/NDecrypt) - encryption
 - [ds-underdumped-header-fixer](https://github.com/mariomadproductions/ds-underdumped-header-fixer) - Fixes undumpered header, using equivalent good ROM's full GameHeader output.

### Nintendo 3DS
 - [NDecrypt](https://github.com/SabreTools/NDecrypt) - encryption

----

<details>
<summary>Tools to add and wanted tools</summary>

## Discs 
### DVD-Video
 - **Wanted:** Tool to fix (encrypt?) the ISOs that ImgBurn etc produce

### Nintendo GameCube
 - **To add:** NKit/Nkit2 (supports other systems too?)

### Nintendo - Wii
 - **To add:** NKit/Nkit2

## Carts
### Nintendo Entertainment System
 - **Wanted:** Brute force iNES header to match hash?

### Nintendo DS
 - **To add:** woodsec (older encryption tool)

### Nintendo 3DS
 - **To add:** Cart ROM private header removal tool

## Digital
### Nintendo
 - **Wanted:** Packing tools
 - **To add:** Encryption tools
 - **To add:** Metadata standardisation tools

### Sony - PlayStation 3 etc
 - **To add:** Encryption tools
 - **Wanted:** Packing tools

</details>
