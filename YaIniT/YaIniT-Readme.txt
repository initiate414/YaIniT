YaIniT (Yet an almost universal INIT Tool)
###
    Version 0.1 , still U N D E R     C O N S T R U C T I O N  ! ! !
###
This is a tool for automatization and customization of 
the boot process of a GNU/Linux system.

YaIniT is designed to alleviate the architectural lacks of the Linux kernel
architecture concerning hybrid processor adapation, 
by using a selection mechanism to choose automatically 
precompiled and well adapted versions of the Linux kernel and 
the BusyBox excecutable, and therewith resulting in a faster operating system. 
  
YaIniT will require only 
1)  an executable of BusyBox,  and
2)  a Linux kernel as of greater or equal 3.2 with kexec-jumping configured, and
3)  a running kexec executable   
to boot almost every running GNU/Linux operating system.
There is a customization possibility, which allows like with the good old
SystemV-INIT, to specify an own ASH-script which does set all necessary
parameters to satisfy the target system's configuration needs and boot
into it, if necessary with an own YaIniT-Kernel.     

   
Folders:

.  yainit-init
   contains an executable of BusyBox at bin/
   configuration files to customize at ./ with
   all scripts in form of BASH and ASH readable shellcode
   
.  tools-scripts
   contains all ASH scripts and configuration files for
   1) setup  the init system
   2) build the BusyBox executables for every processor
      family, for now only for the x86 suite
   3) build the Linux kernel for the relevant processor
      families by automatized patching of the Makefile, for now
      only for the x86 suite
      
.  document 
   contains the files with the system documentation
   

Dieter Miosga, 2014-04-22, last changed 2014-07-02 

