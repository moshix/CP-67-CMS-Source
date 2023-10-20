[![Discord](https://img.shields.io/discord/423767742546575361.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/vpEv3HJ)
<a href=" https://github.com/moshix/mvs/blob/master/codenotary.com"><img src="https://raw.githubusercontent.com/moshix/mvs/master/secured-by-immudb.svg" width="109px;"/></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmoshix%2FCP-67-CMS-Source&count_bg=%2379C83D&title_bg=%23555555&icon=ibm.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
[![View SBOM](https://img.shields.io/badge/sbom.sh-viewSBOM-blue?link=https%3A%2F%2Fsbom.sh%2Fe66f59a5-c50f-4d75-b28d-c9bab9a7ca73)](https://sbom.sh/e66f59a5-c50f-4d75-b28d-c9bab9a7ca73)

CP/67 CMS Source Code
=====================

This is the original source code for the IBM CP/67 CMS operating system from 1969.. 

The source is in assembly listing format as produced by the S/360 assembler for CP/67. 

This source code was recovered from tape reels found in a dumpster (literally!) and then
converted to digital .aws format. The format is in very told VM TAPE format not directly
usable on today's z/VM (which is the grand-grand-grandchild of CP/67). So I read the tapes into
VM/370 which is still close enough to CP/67 to be able to read the tape format.

From there, it was written to .aws format with the VMFPLC2 tape format. Then, moved to 
a modern z/VM system, worked on the files a bit, then moved them back to VM/370, and then
printed to ASCI files... with love. Two of the files on the tapes had permanent read errors, so
some content may be lost. 
 
I received generous help from Bob Polmanter and Neale Ferguson to make this happen. Thank you!

There are 3 files in this repo: 

1. the CMSMacros.txt file contains all the macros needed for the assembler to assemble the source. 
2. The CMSSource.txt file contains the assembler source to be fed into the assembler (together with macros), in 1973
3. The CMSAssemblyListings.txt file contains the source code listings after a clean assembly. 

thanks

Moshix<br>
October, 2023  

