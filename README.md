# libyaz0 v0.5
A library for compressing/decompressing Yaz0/1 compression formats.

By MasterVermilli0n / AboodXD.  
Decompression and compression algorithms based on wszst's.

## `main.py` usage:

 * `main [option...] input`

### Options:
 * `-o <output>`: Output file, if not specified, the output file will have the same name as the intput file
 * `-c`: Compress (Will try to decompress if not specified)

### Compression options:
 * `-level <level>`: compression level (0-9) (1 is the default)  
0: No compression (Fastest)  
9: Best compression (Slowest)

 * `-unk <unk>`: the unknown value that will be located at 0x8-0xC (0x00000000 is the default)