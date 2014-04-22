This is the patchset for the actual YaIniT 
linux-3.12.17 kernel

It consists of patches, alphabetically to sort for patching, 
which are mostly taken from OpenSuSE, Mageia, Redhat and Ubuntu.

Specials:
- The HPC-Scheduler BFS-444 is available and does make a real RT-Desktop.  
- overlayfs, unionfs and aufs are selecteable as modules and coexist
  nicely. For simultaneous use at runtime, no warranty!
  I do not have any experiences, you have been warned!
- The NVIDIA-Nouveau driver is set back to the state of 3.12.9, 
  where with the current X-Windows and XFCE Version from OpenSuSE-13.1
  the system console did start correctly and without a long wait 
- DOT.config-3se3: This configuration is for a generic version of SSSE3
  capable processors, covering the Atom and Core2 from Intel 
  (included MID, Medfield) and the AMD Bobcat, Zambezi (K15,K16).
  Block device drivers such as ATA/PATA/SATA disks, MMC-SmartDisks, PCI-E
  Flash HDDs and Sony Memorysticks are compiled in, such that after 
  installation the kernel can be directly booted into the installed
  system with the kernel commandline parameter
  root=PARTUUID=<hexvalues>-<0><Partitionnumber>
  Then no YaIniT or other preliminary init will run and the boot 
  will be fastest. Find out the PartitonUUID with "fdisk -l"

The precompiled kernel is dwonloadable under the binary branch and
is tested to boot into preinstalled versions of 
OpenSuSE, PUPPYLINUX and QUIRKYLINUX

