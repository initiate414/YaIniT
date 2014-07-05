YaIniT
======
Version 0.1

(Yet an almost universal INIT Tool)   A tool for initramfs setup and GNU/Linux booting 

Project created at 2014-03-30 on https://github.com/initiate414/
by Dieter Miosga

2014-07-05
Withdrawn by the author for reasons of professional attacks 
beyond the civil law against the personal integrity of his person


ChangeLog:
--------

2014-05-28 : 
resvised scripts with some new functions


2014-04-30 :
some important changes and corrections

2014-04-22 :

1) restructured online project with two more branches
    for being able downloading independently 
    patches, scripts and configurations, and binaries

2) uploaded patches and some more kernel binaries
      
3) revised and corrected YaIniT scripts
    
2014-04-08 : 
1) added files: 
 
   vmlinuz-3.12.4.bfs4444yainitu-2se3   # test kernel with most modules optimized for SSE3-i686/prescott 
   
   System.map-3.12.4.bfs4444yainitu-2se3  

   zp-3.12.4.bfs4444yainitu-2se3-xz.sfs  # squashfs with all modules to mount under /lib/modules/`uname -r`/kernel
   
   yatiny-2se3.gz    #  intrd file containing the squashfs with modules
   
2) applied some corrections for system filesystem management 

    (procfs,sysfs,debugfs,hugtlbfs,tmpfs,shmfs,devtmpfs,devpts)

3)  applied some corrections to scripts

4)  done some tests on automatic module loading 

    kernel should boot now with grub1 into Mageia 3/4 , OpenSuSE-11.x/12.x/13.1, Ubuntu, Fedora


2014-04-02 :
done some corrections and minor logic changes 

2014-03-31 :
done some corrections and additions, experimented with git on github 


  


