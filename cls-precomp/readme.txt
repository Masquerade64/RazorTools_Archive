Universal CLS for Precomp
https://www.fileforums.com/showthread.php?t=97938

Here's an attempt of making CLS precomp for newer precomp versions, not as good as the one done by ProFrager but at least shows progress.

Precomp versions supported:
All (0.38-0.46)

Brute method is not supported, only intense method is available.

only cls-precomp.dll and your precomp.exe are needed for both compression and decompression else if cls is not present during compression and you added arc.ini and you use this cls, decompression will ALWAYS fail.

Injection not necessary

Drawbacks:
Using this cls may inflict on final size than when you use precomp without it, the bright side is it shows progress during installation for any newer precomp versions.
Games like DiRT Rally are the ones most likely to inflict a lot on final size because the game is filled with massive zlib streams.
Otherwise for the drawback, if it bad news to you, you could rely on the version done by ProFrager.
Another drawback is temp directory is created for precomp to work on.
If the compressors used other than precomp take long to decompress, percentage will look stuck sometimes, also depends on how big the inflated size was after precomp.

I did this in about an hour and only ran 2 successful tests so if there are any bugs, please report back.

Tested using Precomp 0.45 both x86 and x64.