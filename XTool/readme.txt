XTool - Successor of ZTool 
https://www.fileforums.com/showthread.php?t=101729

XTool version 0.1

Created by Razor12911

Commands:
  e - encode
  d - decode

Operations and codecs available:
  precomp - data precompression
    zlib     : loaded
    crilayla : loaded

Options:
  precomp - data precompression
    c#: chunk size (default 16mb)
    t#: number of threads, use p for percentage

Usage   : XTool [command]:[operation]:[options]:[codecs] [input] [output]
Example : XTool e:precomp:c32mb,t4:zlib,lz4 Textures.tfc Textures.tfc.xtl

Acknowledgement:
  zlib:
  -  Jean-loup Gailly
  -  Mark Adler
  reflate:
  -  Eugene Shelwien
  bdiff:
  -  Peter Johnson
  crilayla:
  -  KenTse
  -  RamiroCruzo