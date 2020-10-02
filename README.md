CP/67 CMS Source Code
=====================

This is the original source code for the IBM CP/67 CMS operating system from 1973. 

The source is in assembly listing format as produced by the S/360 assembler for CP/67. 

This source code was recovered from tape reels found in a dumpster (literally!) and then
converted to digital .aws format. The format is in very told VM TAPE format not directly
usable on today's z/VM (which is the grand-grand-grandchild of CP/67). So I read into
VM/370 which is still close enough to CP/67 to be able to read the tape format.

From there, it was written to .aws format with the VMFPLC2 tape format. Then, moved to 
a modern z/VM system, and then printed to ASCI files... with love. 

As of today (October 2020) there are some ^L control chars here and there which need to be cleaned up, 
but the code is all there in its' beauty for posterity. I will take care of that in a second step. 

There are 3 files in this repo: 

1. the CMSMacros.txt file contains all the macros needed for the assembler to assemble the source. 
2. The CMSSource.txt file contains the assembler source to be fed into the assembler (together with macros).
3. The other file contains the source code listings after a clean assembly. 

thanks

Moshix

