Here are all patches for busybox

tune-gcc482-busybox.diff      :        
The patch needed to make the compilings with gcc-4.8.2
successfull to match the gcc-parameters given in the 
BusyBox-ASH Scripts. 

The 1st hunk removes an obsolete restriction for the compilation
with gcc-4.8.2.

The 2nd hunk contains the change necessary to make a VFAT32 volume
in a >= 1 TB hard disk drive completely visible. With the small 
buffer size, VFAT volumes do not appear with their volume name.
This is a temporary hack, not a workover for 
dynamically seizing the buffer according the block device size!
