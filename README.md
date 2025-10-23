# dump-fixing-tools
Tools for fixing bad disc/ROM/etc dumps

## General
### Automatic
 - [findcrcs](https://github.com/claunia/findcrcs)	 - I guess this is not superceded by find-ends, but I'm not sure.		
 - [crc-trim-prefix](https://github.com/hcs64/crc-trim-prefix/) -	Superceded by find-ends?
 - [find-ends](https://github.com/hcs64/find-ends)	- Rebuild the missing ends of files, given the expected complete CRC32 and another file to search for the missing parts."	
 - [bitflipper](https://github.com/conorpp/bitflipper) -	Flips bits in a file to correct minor corruption, until SHA1 is found. I've confirmed it can be sped up significantly by adding CRC32 pre-check to the code, but I don't know how to do that cleanly.		
 - [rdiff](https://github.com/librsync) - 	Allows people to share differences between a file, without either person needing to send a whole file - good for cautious dumpers, if a similar dump to the MIA one is non-MIA.	([tutorial + windows build zip with required dll included](https://gist.github.com/mariomadproductions/a1c4335f5a770f38a924c657e5929797))
			
### Manual
 - [HxD](https://mh-nexus.de/en/hxd/) - Or hex editor of your choice	
			
## Discs
### Automatic
 - [ResurrectSkeleton](https://github.com/Deterous/ResurrectSkeleton)

#### IBM PC - Windows
 - [autorun-inf-fuzzer](https://github.com/DopefishJustin/)	

### Manual
 - CDMage			
 - [ISOBuster](https://www.isobuster.com/)			
 - [CueTools](http://cue.tools/wiki/Main_Page)			
 - [Official flac tools](https://xiph.org/flac/documentation_tools.html) - or [FlacFrontend](https://flacfrontend.sourceforge.net/)
 - PSXt001z
 - Descramble_CDDA
 - [fix_xa_submode_and_rebuild_ecc_edc](https://discord.com/channels/631875781563252784/1067102085960704020/1428468415844057088) - by Wiggy2k		
			
## Carts
### Nintendo DS
#### Automatic
 - [ds-underdumped-header-fixer](https://github.com/mariomadproductions/ds-underdumped-header-fixer) - Fixes DS ROM with undumpered header, using equiv. good ROM's full GameHeader output.	
			
