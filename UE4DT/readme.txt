Unreal Engine 4 Decryption Tool
https://www.fileforums.com/showthread.php?t=103145

Usage:
ue4dt.exe e|d -m# -c# -b# -k# <stdin> <stdout>

-m = method (1 = games that use borderlands3, street figher v... format, 2 = games that use rune ii format)
-c = chunk size
-b = block count
-k = key in hexadecimal.

The key must be in hexadecimal format. Other key formats will not work because there is currently no parser for them yet.

I am not sure if this is universal, I don't have any unreal engine games and I was sent a small sample to work on. Borderlands 3 "pakchunk2-WindowsNoEditor_0_P.pak", seems like it works

Note: This only decrypts, you'll have to find other means of precompressing the data. The input/output size remains the same. 