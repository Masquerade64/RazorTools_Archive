Oodle precompressor (Side project) 
https://www.fileforums.com/showthread.php?t=102453

Hello, I decided to give oo2core_6_win64.dll another shot to see what was really causing the crashing issues I was facing and somehow it the coding software itself so I decided to rewrite the code.... again... but now using Lazarus instead of Delphi because of it causing too many problems, I spent an entire day writing this because it was the only time I had, been very busy lately and I think I got it working.

I have tested on the samples I got from WWE2K19, it handles it just fine, not sure about the entire game but that's for you to find out.

If you look at the attachment, there is a separate jc4 executable. Well that's just a recompile of the main executable just with a few changes to it supports the remaining stream that game has since two compression methods were used on it but to make it work, you would have to combine the main precompressor with the jc4 to fully precompress the game.... I think... not sure since I really had very little time to work on this plus only had 2 samples from the game.
Combining the methods means -moo2rec+oo2recj

Support for now is simply limited to kraken compressed games, just take the dll from game and place it near exe, use the scanner included as a guide, it will show you exactly what method was used in that particular game.

DLLs supported:
oo2core_4_win64.dll
oo2core_5_win64.dll
oo2core_6_win64.dll
oo2core_7_win64.dll

Some results:

Just Cause 4 (game0.arc)

lzma:ultra:d176m:
15,8 MB (16 584 704 bytes) >> 13,6 MB (14 346 879 bytes)
oo2rec+lzma:ultra:d176m:
15,8 MB (16 584 704 bytes) >> 20,2 MB (21 202 181 bytes) >> 13,3 MB (13 965 518 bytes)
oo2rec+oo2recj+lzma:ultra:d176m:
15,8 MB (16 584 704 bytes) >> 25,5 MB (26 774 015 bytes) >> 12,3 MB (12 968 978 bytes)

Just Cause 4 (dlc.arc)

lzma:ultra:d176m:
22,8 MB (23 957 504 bytes) >> 20,2 MB (21 189 235 bytes)
oo2rec+lzma:ultra:d176m:
22,8 MB (23 957 504 bytes) >> 35,5 MB (37 286 828 bytes) >> 18,7 MB (19 661 381 bytes)
oo2rec+oo2recj+lzma:ultra:d176m:
22,8 MB (23 957 504 bytes) >> 45,2 MB (47 453 198 bytes) >> 17,1 MB (17 986 419 bytes)

These results are already making me wonder if I made mistakes somewhere and left several streams behind.... XDD

See you guys in a while, enjoy and I hope it works lol