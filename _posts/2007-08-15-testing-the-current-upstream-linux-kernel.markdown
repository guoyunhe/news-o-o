---
author: Andreas Jaeger
date: 2007-08-15 09:59:14+00:00

layout: post
link: https://news.opensuse.org/2007/08/15/testing-the-current-upstream-linux-kernel/
title: "Testing the Current Upstream Linux Kernel"
categories:
- Distribution
tags:
- kernel
---
Andrew Morton has spoken at different occasions about testing of the Linux kernel and asked users to test the current development version and report their findings.Â  For our openSUSE releases we have in general a frozen version and add only fixes for bugs that are encountered during testing - but stay with the same version for the lifetime of a release.

With our openSUSE Build Service we build a daily kernel, where we take the current upstream development kernel without any patches (besides those we need for building a RPM).Â  We do call this the vanilla kernel. It can be downloaded from:
[http://download.opensuse.org/repositories/Kernel:/Vanilla/SUSE_Factory/](http://download.opensuse.org/repositories/Kernel:/Vanilla/SUSE_Factory/)

Btw. if you test the vanilla kernel, report any problems to the Linux kernel mailing list (for details check the FAQ at [http://www.tux.org/lkml/](http://www.tux.org/lkml/)) and not to the openSUSE bugzilla.		
