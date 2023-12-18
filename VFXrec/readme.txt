Metro Exodus Precompression Tool
https://www.fileforums.com/showthread.php?t=103563

Another lz4 game in the bag as requested

I rushed this release, something came up and got busy. I ran one test and compared it with metro-vfx-unpacker and it seems like some streams are left behind.

test on patch_01.vfx (patch_01.vfs0, patch_01.vfs1):
using vfxrec 4.85 GB (5,215,404,338 bytes)
using metro-vfx-unpacker 5.29 GB (5,690,004,897 bytes)

That's all I can do for now

Extracted 3 files, 5,215,404,078 => 3,369,431,485 bytes. Ratio 154.79%
Extraction time: cpu 7.53 sec/real 196.03 sec = 4%. Speed 17.19 mB/s

Probably R2 will be able to detect everything. 