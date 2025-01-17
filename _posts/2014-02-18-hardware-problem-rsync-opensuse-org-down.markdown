---
author: Lars Vogdt
date: 2014-02-18 14:50:59+00:00

layout: post
link: https://news.opensuse.org/2014/02/18/hardware-problem-rsync-opensuse-org-down/
title: "[Update] Hardware problem: rsync.opensuse.org down "
categories:
- Infrastructure
tags:
- downtime
- Infrastructure
---
({{ site.baseurl }}/assets/m3geeko-150x150.jpg) Geeko at work

[Update]: the problem seems to be a broken hard disk - and a hardware controller who can not really handle this degraded RAID array. For the moment, everything is up and running again, but we are now actively searching for replacement hardware...

Looks like the hardware behind rsync.opensuse.org now finally reaches it "end of life" status: we did not see any output on the serial console any more and even a power cycle did not reanimate the system.

As the hardware is located in the data center of our sponsor IP Exchange, we apologize for the delay it will take to fix the problem: we just need a field worker at the location who has the appropriate permissions and skills.

During the downtime (and maybe also a good tip afterward), please check on [http://mirrors.opensuse.org/](http://mirrors.opensuse.org/) for the closest mirror nearby your location that also offers rsync for you.		
