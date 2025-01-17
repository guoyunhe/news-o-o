---
author: Andreas Jaeger
date: 2007-09-18 13:55:39+00:00

layout: post
link: https://news.opensuse.org/2007/09/18/open-source-driver-for-ati-radeon-r5xxr6xx/
title: "Open Source Driver for ATI Radeon R5xx/R6xx"
categories:
- Distribution
---
[![amd-ati.jpg]({{ site.baseurl }}/assets/amd-ati.jpg)](http://ati.amd.com) AMD has recently released register specifications for the ATI  Radeon R5xx and R6xx  graphic devices.  Engineers  from Novell have now released a first alpha quality Open Source driver which currently supports initial mode settings. Next steps are adding support for more hardware, RandR 1.2 support, video overlay support and 2D acceleration.

The developers are now seeking for help to extend support for all graphics cards and motherboards out there. You can get the alpha driver from the multi-distribution packages (Fedora, Mandriva, SUSE Linux Enterprise, and of course openSUSE) in the [openSUSE Build Service](http://opensuse.org/Build_Service) at:

[http://download.opensuse.org/repositories/X11:/Drivers:/Video:/radeonhd/](http://download.opensuse.org/repositories/X11:/Drivers:/Video:/radeonhd/)

If you like to check out the latest source code, clone it via git with:

`git://anongit.freedesktop.org/git/xorg/driver/xf86-video-radeonhd`

A mailing list has been created at [radeonhd@opensuse.org](http://lists.opensuse.org/radeonhd/) ([subscribe](mailto:radeonhd+subscribe@opensuse.org)).  The developers are also discussing the development on the IRC channel: [#radeonhd](irc://irc.freenode.net/radeonhd) on _irc.freenode.net_.

Bugs can be filed at [http:/bugs.freedesktop.org](http:/bugs.freedesktop.org) under the _X.Org_ product, component _radeonhd_.

Thanks to  [Egbert Eich](http://archive.fosdem.org/2007/schedule/speakers/egbert+eich), Luc Verhaegen and [Matthias Hopf](http://en.opensuse.org/User:Mhopf) for their great work!

I'm looking forward to seeing the driver in the openSUSE 11.0 release next year.

Andreas		
