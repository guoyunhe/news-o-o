---
author: News Team
date: 2007-09-17 00:29:48+00:00

layout: post
link: https://news.opensuse.org/2007/09/17/jacklab-project-announces-its-first-public-release/
title: "JackLab Project Announces its First Public Release"
---
[![jacklab.jpg]({{ site.baseurl }}/assets/jacklab.jpg)](http://jacklab.org) The technical manager of the [JackLab project](http://jacklab.org/), Oliver Bengs, released the [final 1.0 version of the JackLab Audio Distribution (JAD)](http://jacklab.net/jacklaborg/english/?Releases:JAD_1.0_final_release) today after a development period of over eight months. JAD 1.0 is based upon openSUSE 10.2 with the addition of a real-time Kernel for fast audio processing with the professional audio server [JACK](http://jackaudio.org/). JackLab 1.0 is the most comprehensive selection of open source audio and multimedia software to date. The [Enlightenment](http://www.enlightenment.org/) D17 window manager (with 'KDE-lite' tweaks) is used by default, with the option of using the full KDE 3.5.7 instead.

<!-- more -->
JAD 1.0 aims to lower the Linux entry barriers, making things as easy as possible for musicians and multimedia content creators and it offers complete compatibility with openSUSE 10.2. The [Smart package manager](http://smartpm.org) is included for quickly and easily updating or adding new software and [YaST](http://opensuse.org/YaST) is included for easy graphical system administration. The system is immediately operational after installation for tasks such as multi-track recording with [Ardour 2](http://ardour.org/), real time audio synthesis with [ZynAddSubFX](http://zynaddsubfx.sourceforge.net/), MIDI sequencing with [Rosegarden](http://www.rosegardenmusic.com/), as well as video editing with [KDEnlive](http://www.kdenlive.org/) and graphics manipulation with programs such as [Inkscape](http://www.inkscape.org/) and [Gimp](http://www.gimp.org/).



[![JAD - Ardour 2]({{ site.baseurl }}/assets/jad_ardour2_thumb.jpg)]({{ site.baseurl }}/assets/jad_ardour2.png) [![JAD - WINE ASIO]({{ site.baseurl }}/assets/jad_wineasio_thumb.jpg)]({{ site.baseurl }}/assets/jad_wineasio.png) [![JAD - Reaper]({{ site.baseurl }}/assets/jad_reaper_thumb.jpg)]({{ site.baseurl }}/assets/jad_reaper.png)
See [more JAD screenshots](http://jacklab.net/jacklaborg/english/?JAD_1.0_Screenshots)



Unlike other existing Linux audio distributions (_64studio, Ubuntustudio, Musix, dynebolic_) JAD 1.0 offers complete support for [ASIO](http://en.wikipedia.org/wiki/Audio_stream_input_output). Thanks to WINE you can use Windows VST host programs such as Reaper or EnergyXT2 with a very large number of VST Plugins but with latency as good as Linux native JACK audio applications. The user must first add the WINEASIO driver to the WINE register and can these applications then easily as used from Windows. This is easily done and documented on the JackLab wiki.

In addition, native VST for Linux is supported by 'JOST', a small modular host. Some native Linux VST Plugins are included with the distribution but there more that can't be included for legal reasons. JOST also supports [LADSPA](http://www.ladspa.org/), the native LinuxAudioDeveloper plugin format. JackLab comes with over 300 LADSPA plugins.

JAD 1.0 is the result of a collaboration of musicians and free software developers and enthusiasts. This community was started by musician and media producer Michael Bohle in order to improve and promote the development of pro-audio under SUSE Linux. openSUSE was selected as the basis of JAD because it is the world's most user-friendly and easy-to-use version of Linux. The project is independent from openSUSE but intends to give back to the community by improving SUSE's support for pro-audio and multimedia creation. Recently, JackLab and [PackMan](http://packman.links2linux.de) have joined forces to offer JAD access to the PackMan repositories so that up-to-date audio software, non-audio software and multimedia codecs are available to JAD users. In future updates of JAD, the new openSUSE buildserver repository 'Audiophile', will be used for. 'Audiophile' is maintained by Takashi Iwai in assistance with JAD dev Oliver Bengs and contains ALSA updates, pro audio software and later a rt-kernel.

For taking part in providing user support, there is a web based forum, [forum.JackLab.net](http://forum.jacklab.net/), and an IRC channel, [#jad](irc://irc.freenode.net/jad) on _irc.freenode.net_. It is also an essential part of the development process to see feedback.

In order to safeguard JAD and its future development, a registered promotion association, _JackLab e.V._, is planned. JackLab e.V. will sponsor the activities of the JackLab community such as workshops, participating in events and holding developer conferences and hopefully it will also fund the development of exciting open source audio projects.

The project would like to thank all the testers and early adopters for their assistance in creating JAD 1.0. Not to forget all the good discussions in blogs, forums and magazines. The overwhelmingly positive response from musicians was very encouraging. We received feedback from the whole world, where JAD 1.0 is now used in recording studios, schools, workshops and youth centers.

On behalf of the JackLab Team,
Michael Bohle.	
