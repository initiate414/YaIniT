Files:

.  yatiny.gz
   gzip-compressed uucp archive with the last running version
   to put into your preinstalled distro's boot/ directory for execution with a kernel,
   which must have builtin the bockdevice drivers to find your
   rootfilesystem and the filesystem drivers to mount it.  
   yatiniy.gz is nothing other than 
   `mkyainitrd gz` 
   from the yainit-init folder.  
   With bultin keyboard dirvers and specifying 'debug' 
   at the kernel commandline, yainit's  yatiny initial ramdisk 
   will stop the system boot at halt marks and allow you to copy 
   the well matching and optimized BusyBox executable for your machine
   in your boot directory. 
    
.  yatiny-2se3.gz 
   same as yatiny.gz but containing the kernel modules for
   kernel 3.12.4.bfs4444yainitu-2se3
   
.  vmlinuz-3.12.4.bfs4444yainitu-2se3
   latest kernel with "allmodconfig" from scratch, running with yatiny
   
.  zp-3.12.4.bfs4444yainitu-2se3-xz.sfs
   squashfs file with all modules to mount to the 
   /lib/modules/3.12.4.bfs4444yainitu-2se3/kernel
   directory
   
.  vmlinuz-3.12.17.bfs4444yainitu-3se3
   latest kernel with all local block device drivers compiled in
   and support for the SSSE3 instruction set compatible x86 processors
   
.  zp-3.12.17.bfs4444yainitu-2se3-xz.sfs
   squashfs file with all modules to mount to the 
   /lib/modules/3.12.17.bfs4444yainitu-3se3/kernel
   directory   
   
.  vmlinuz-3.12.14.bfs4444yainitu-2se3
   latest kernel with all local block device drivers compiled in
   and support for the SSE3 instruction set compatible x86 processors
   
.  zp-3.12.14.bfs4444yainitu-2se3-xz.sfs
   squashfs file with all modules to mount to the 
   /lib/modules/3.12.14.bfs4444yainitu-2se3/kernel
   directory   
