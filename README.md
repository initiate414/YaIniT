This project's contents have moved to :
https://github.com/yainit/

There is:

documentation in branch  
yainit/document

kernel build sets in branch 
yainit/kernels

prebuild kernel binaries in branch 
yainit/binaries

initramfs and scripts in branch
yainit/init

some useful and general scripts in branch
yainit/tools

the used toolchain and BusyBox with patches in branch
yainit/toolchain 


For any further information,
Contact the author under dmiosga6200@gmail.com


  YaIniT
===========
Version 0.2

(Yet an almost universal INIT Tool)   A tool for initramfs setup and GNU/Linux booting 

The effort to create an almost universal init system to boot into GNU/Linux
distributions with using only 
1) BusyBox and the therein contained Almquist Shell (ASh)
2) an unified Linux kernel that should be runnable under all commonly forked and rather open distributions
3) a defined toolchain, recognizable by links or downloadable from this site


Project created at 2014-03-30 on https://github.com/initiate414/
by Dieter Miosga
continued at 2015-01-25 on https://github.com/yainit


ChangeLog of the initial version 0.1:
=====================================

@2015-01-25:
Renewed project publication and created branches for easier download


@2014-09-03:
deleted the binary- and patchsets-branches 
continued and published work until 2014-07-05

@2014-09-03:
My application for the 2014 Swiss Open Source Award was answered with: 

----------------------------------------------------------------------------

Dear CH Open Source Award 2014 participant,

Last week we thanked and/or congratulated you for your
participation/nomination. The jury did their work and made the first
difficult choice to select the projects that made it on the shortlist.

Unfortunately your project did not make it. There were various criteria
and vivid discussions, in the end the jury gave out points around the
following topics:

* Relevance of the project
* Is the project closing a gap in the OSS environment?
* Is it really open or is there a downgraded community version only?
* Does it have a vivid community of supporters & contributors?
* What's the innovation of the project?
* In case it's a small and/or early stage project, how much potential
does it have?
* How inspiring is the project?
* Does it highlight power and benefits of Open Source Software?
* Is it an active project? Amount of commits, committers, releases etc.

Your project didn't get enough points to make it to the list. Some
projects looked promising but it was hard to judge how vivid the
project/community/relevance is. The jury explicitly said some projects
should apply another year again if there is ongoing progress in the
project. If you would like to know more, you can get back to me and I
will try to give a better idea of what was missing.

Thanks again

Kind regards

Adrian Gschwend & the CH Open Source Awards Jury
------------------------------------------------------------------------------



If you want an alternative or own INIT for your system's startup, 
get yourself through the following projects and informations. 

They made it! 
  
  http://en.wikipedia.org/wiki/Init

  systemd   :  https://github.com/systemd/systemd

  upstart   :  http://upstart.ubuntu.com/

  sysvinit  :  http://savannah.nongnu.org/projects/sysvinit

  u-root    :  https://github.com/rminnich/u-root

  OpenRC    :  https://github.com/OpenRC/openrc


@2014-07-05:
Withdrawn by the author for reasons of professional attacks 
beyond the civil law against the personal integrity of his person


@2014-05-28: 
revised scripts with some new functions


@2014-04-30:
some important changes and corrections

@2014-04-22:

1) restructured online project with two more branches
    for being able downloading independently 
    patches, scripts and configurations, and binaries

2) uploaded patches and some more kernel binaries
      
3) revised and corrected YaIniT scripts
    
@2014-04-08: 
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


@2014-04-02:
done some corrections and minor logic changes 

@2014-03-31:
done some corrections and additions, experimented with git on github 


