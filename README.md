YaIniT
======
Version 0.1

(Yet an almost universal INIT Tool)   A tool for initramfs setup and GNU/Linux booting 

Project created at 2014-03-30 on https://github.com/initiate414/YaIniT
by Dieter Miosga

Changes:
2014-03-31 :
done some corrections and additions, experimented with git on github 
2014-04-02 :
done some corrections and minor logic changes 
2014-04-08 : 
- added files 
   vmlinuz-3.12.4.bfs4444yainitu-2se3   # test kernel with most modules optimized for SSE3-i686/prescott 
   System.map-3.12.4.bfs4444yainitu-2se3  
   zp-3.12.4.bfs4444yainitu-2se3-xz.sfs  # squashfs with all modules to mount under /lib/modules/`uname -r`/kernel
   yatiny-2se3.gz    #  intrd file containing the squashfs with modules
- applied some corrections for system filesystem management (procfs,sysfs,debugfs,hugtlbfs,tmpfs,shmfs,devtmpfs,devpts)
- applied some corrections to scripts
- done some tests on automatic module loading
  kernel should boot with grub1 into Mageia 3/4 , OpenSuSE-11.x/12.x/13.1, Ubuntu, Fedora
  


