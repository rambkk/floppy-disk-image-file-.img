# floppy-disk-image-file-.img
Floppy disk image files .img with no data formatted using MS-DOS format

Here you can download floppy disk image files .img with no data in different disk sizes

DOS-5 formatted images (added September 2026)
```text
D5_2880.IMG 2.88mb
D5_1440.IMG 1.44mb
D5_1200.IMG 1.2mb
D5_720.IMG  720kb
D5_360.IMG  360kb
```

Older disk images (These have been added before September 2026)
```text
d1440.img 1.44mb
d1200.img 1.2mb
d720.img  720kb
d360.img  360kb
```

Disk information:
```
DOS IMAGE GEOMETRY / FAT INFORMATION
===============================================================================================
Image          Size       Sectors   Cylinders  Heads  Sectors/Track  Bytes/Sector  FAT
-----------------------------------------------------------------------------------------------
D5_360K.IMG    360 KiB       720       40       2          9             512       FAT12
D5_720K.IMG    720 KiB     1,440       80       2          9             512       FAT12
D5_1200K.IMG   1.17 MiB    2,400       80       2         15             512       FAT12
D5_1440K.IMG   1.41 MiB    2,880       80       2         18             512       FAT12
D5_2880K.IMG   2.81 MiB    5,760       80       2         36             512       FAT12
===============================================================================================

DETAILED FAT / BOOT SECTOR INFORMATION
==========================================================================================================
Image          Clust  Reserved  FATs  Root Entries  FAT/Copy  Media   Total Sectors  Label
----------------------------------------------------------------------------------------------------------
D5_360K.IMG      2        1       2       112           2       FD        720         RAMBKK_360
D5_720K.IMG      2        1       2       112           3       F9      1,440         RAMBKK_720
D5_1200K.IMG     1        1       2       224           7       F9      2,400         RAMBKK_1200
D5_1440K.IMG     1        1       2       224           9       F0      2,880         RAMBKK_1440
D5_2880K.IMG     2        1       2       240           9       F0      5,760         RAMBKK_2880
==========================================================================================================
```

Media Byte description:
```
MEDIA DESCRIPTOR BYTE TABLE
================================================================================
Media Byte    Common Meaning                  Typical Format
--------------------------------------------------------------------------------
F0            Removable disk / floppy          1.44 MB, 2.88 MB
F9            Floppy disk                      720 KB, 1.2 MB
FD            Floppy disk                      360 KB
F8            Fixed disk / hard disk           Hard disks
FC            Floppy disk                      180 KB
FE            Floppy disk                      320 KB
FF            Floppy disk                      320 KB / other older formats
================================================================================
```


Should be able to mount these on virtual machine software such as vmware, virtual machine, etc.
VMWARE : mount floppy image
Dosbox, Dosbox-x: can mount to a drive and make modification to the virtual disk, these should get saved to the image
Etc.

If you find this helpful, please let me know by contacting me ram @ pluslab.com or via my web page www.pluslab.net
