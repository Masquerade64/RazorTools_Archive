SRTTR Precompression Tool
https://www.fileforums.com/showthread.php?t=103546

I just got Saints Row The Third Remastered and instead of playing the game like a normal person would, I wanted to find out what compression method is used in the game by checking the game executable and to my surprise, I found traces of lz4 functions being used so I checked the vpp_pc files to see if precompression was possible and yes it was.

So I made the tool to use, enjoy

My test results on the vpp_pc files only:

Compressed 44 files, 48,891,349,439 => 73,898,969,645 bytes. Ratio 151.15%
Compression time: cpu 63.91 sec/real 1495.70 sec = 4%. Speed 32.69 mB/s

PS. Not all vpp_pc files contain lz4, maybe I missed a few streams but just don't expect to save a lot of GBs because lz4 is also a weak compression algorithm. (Compression not tested)

I'm off to playing the game so cheers. 