CLS-ZStd
https://www.fileforums.com/showthread.php?t=98121

Here's CLS version of ZStd, ran some tests, it's fast during compression because no temps are created, also added multi threading feature, it's only effective if you use a high level to compress, also if the chunk size is high as well, then it is effective, if you're using level 1 for example, and you try to use multi threading, just know that it is going to be slow, since level 1 is almost like copying a file, just adding multi threaded copying doesn't mean speed will be fast, it will drop.
During decompression, I ran tests as well, it's also fast, you can easily get more than 200mb/s. Decompression is single threaded. 