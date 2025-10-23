# dump-fixing-tools
Tools for fixing bad disc/ROM/etc dumps so that they match the hash of a proper dump listed in e.g. Redump or No-Intro.

## General
### Automatic
 - [findcrcs](https://github.com/claunia/findcrcs) - GUI/further automation tool:  [GUI for FindCRCs](http://forum.redump.org/topic/14688/gui-for-findcrcs/).
 - [crc-trim-prefix](https://github.com/hcs64/crc-trim-prefix/) - Superceded by find-ends?
 - [find-ends](https://github.com/hcs64/find-ends) - Rebuild the missing ends of files, given the expected complete CRC32 and another file to search for the missing parts."	
 - [bitflipper](https://github.com/conorpp/bitflipper) - Flips bits in a file to correct minor corruption, until SHA1 is found. I've confirmed it can be sped up significantly by adding CRC32 pre-check to the code, but I don't know how to do that cleanly.		
 - [rdiff](https://github.com/librsync) - Allows people to share differences between a file, without either person needing to send a whole file - good for cautious dumpers, if a similar dump to the MIA one is non-MIA.	([tutorial + windows build zip with required dll included](https://gist.github.com/mariomadproductions/a1c4335f5a770f38a924c657e5929797))
 - [ReScene](http://rescene.wikidot.com/)
			
### Manual
 - [HxD](https://mh-nexus.de/en/hxd/) - Or hex editor of your choice	
			
## Discs
### General
#### Automatic
 - [ResurrectSkeleton](https://github.com/Deterous/ResurrectSkeleton) - Rebuilds a CD image given a redumper skeleton and extracted files
 - [fix_xa_submode_and_rebuild_ecc_edc](https://discord.com/channels/631875781563252784/1067102085960704020/1428468415844057088)

#### Manual
 - CDMage			
 - [ISOBuster](https://www.isobuster.com/)			
 - [CueTools](http://cue.tools/wiki/Main_Page)			
 - [Official flac tools](https://xiph.org/flac/documentation_tools.html) - or [FlacFrontend](https://flacfrontend.sourceforge.net/)
 - Descramble_CDDA

### DVD-Video
##### Automatic
 - **WANTED:** Tool to fix (encrypt?) the ISOs that ImgBurn etc produce

### IBM PC
#### Windows
##### Automatic
 - [autorun-inf-fuzzer](https://github.com/DopefishJustin/autorun-inf-fuzzer)

### Sony - PlayStation
#### Automatic
 - [PSXt001z](https://github.com/Dremora/psxt001z)

### Sony - PlayStation 3 etc
#### Automatic
 - **TO LINK:** Encryption tools
 - **WANTED:** Packing tools

### Sega Dreamcast
#### Automatic
 - [TOSEC 2 Redump](http://forum.redump.org/topic/17099/dreamcast-tosec-2-redump-and-vice-versa-dumps-converter/)

### Nintendo GameCube
#### Automatic
 - **TO LINK:** NKit/Nkit2 (supports other systems too?)

### Nintendo - Wii
#### Automatic
 - **TO LINK:** NKit/Nkit2

### Wii U
### Automatic
- [WudCompress](https://gbatemp.net/threads/wii-u-image-wud-compression-tool.397901/) - decompress from unofficial WUX compression format

## Carts
### General/Multiple
#### Automatic
 - [ucon64](https://ucon64.sourceforge.io/)

### Nintendo digital
#### Automatic
 - **WANTED:** Packing tools
 - **TO LINK:** Encryption tools
 - **TO LINK:** Metadata standardisation tools

### Nintendo DS
#### Automatic
 - [NDecrypt](https://github.com/SabreTools/NDecrypt) - cart encryption
 - **TO LINK:** woodsec (older encryption tool)
 - [ds-underdumped-header-fixer](https://github.com/mariomadproductions/ds-underdumped-header-fixer) - Fixes DS ROM with undumpered header, using equiv. good ROM's full GameHeader output.

### Nintendo 3DS
#### Automatic
 - [NDecrypt](https://github.com/SabreTools/NDecrypt) - cart encryption
 - **TO LINK:** Cart ROM private header removal tool

