LZO precompressor (Side project)
https://www.fileforums.com/showthread.php?t=102615

Hi again guys, here's another procompressor for another algorithm.

Things you should know:
* This thing does not detect every single stream in the game, like specific precompressors like DELZORec when dealing with game titles like Far Cry 3 and 4.
* It's slow af from my opinion but it's first release, probably a few releases down the line, it can be made faster.
* It can be buggy, had problems setting it up, it wasn't like oodle and zstd, for now. I have no idea what causes certain bugs because firstly, I lack samples which produce bugs, I may need help in this department when you come across bugs, do report with helpful information
* For now, I have added support for lzo1x_999 (1-9)
* Max decompressed stream size should be no more than 4MB for it to be detected.

Ran a test on a portion of lzo streams I bundled together and these were results:

Compressed 1 file, 33,987,678 => 62,617,798 bytes. Ratio 184.24%
Compression time: cpu 0.06 sec/real 19.78 sec = 0%. Speed 1.72 mB/s

Extracted 1 file, 62,617,798 => 33,987,678 bytes. Ratio 184.24%
Extraction time: cpu 0.13 sec/real 3.46 sec = 4%. Speed 9.82 mB/s

