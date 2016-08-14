# dav-file-converter

scripts to deal with amcrest security camera dav files on an ftp server

## find-ok-files

```
find /directory/of/dav/files > all-files.txt
./find-ok-files < all-files.txt
ffmpeg -safe 0 -f concat -i files-final.txt   -vcodec copy -acodec cop ~/Downloads/out.mp4
```
