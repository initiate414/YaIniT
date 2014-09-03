YaIniT
======
Version 0.1

(Yet an almost universal INIT Tool)   A tool for initramfs setup and GNU/Linux booting 

Project created at 2014-03-30 on https://github.com/initiate414/
by Dieter Miosga

2014-09-03

Last possible financial support was cut with the following message:

####################################################################
X-Account-Key: account2
X-UIDL: 0LkB1C-1Y0ZYF1qBO-00c91L
X-Mozilla-Status: 0001
X-Mozilla-Status2: 00000000
X-Mozilla-Keys:                                                                                 
Return-Path: ktk@netlabs.org
Received: from r2-d2.netlabs.org ([213.238.45.90]) by mx-ha.gmx.net (mxgmx107)
 with ESMTPS (Nemesis) id 0LkB1C-1Y0ZYF1qBO-00c91L for <dieter.miosga@gmx.de>;
 Tue, 02 Sep 2014 11:43:57 +0200
Received: (qmail 81728 invoked by uid 89); 2 Sep 2014 09:43:51 -0000
Received: from unknown (HELO eternal.metropolis.netlabs.org) (ktk@netlabs.org@213.144.156.18)
  by 0 with ESMTPA; 2 Sep 2014 09:43:51 -0000
Message-ID: <54059151.8050205@netlabs.org>
Date: Tue, 02 Sep 2014 11:43:45 +0200
From: Adrian Gschwend <ktk@netlabs.org>
Organization: netlabs.org
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.9; rv:17.0) Gecko/20130801 Thunderbird/17.0.8
MIME-Version: 1.0
To: ktk@netlabs.org
Subject: CH Open Source Award 2014 shortlist
X-Enigmail-Version: 1.6
Content-Type: multipart/signed; micalg=pgp-sha512;
 protocol="application/pgp-signature";
 boundary="KtEKHKaBDP4EkC2oNafbVQPlSOMgiPVkM"
Envelope-To: <dieter.miosga@gmx.de>
X-GMX-Antispam: 0 (Mail was not recognized as spam); Detail=V3;
X-GMX-Antivirus: 0 (no virus found)

This is an OpenPGP/MIME signed message (RFC 4880 and 3156)
--KtEKHKaBDP4EkC2oNafbVQPlSOMgiPVkM
Content-Type: text/plain; charset=ISO-8859-1
Content-Transfer-Encoding: quoted-printable

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

#############################################################################



If you want an alternative or own INIT for your system's startup, 
get yourself through the following projects and informations. 

They made it! 

http://en.wikipedia.org/wiki/Init
systemd   :  https://github.com/systemd/systemd
upstart   :  http://upstart.ubuntu.com/
sysvinit  :  http://savannah.nongnu.org/projects/sysvinit
u-root    :  https://github.com/rminnich/u-root
OpenRC    :  https://github.com/OpenRC/openrc

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


  


