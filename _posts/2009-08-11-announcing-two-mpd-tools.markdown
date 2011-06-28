---
layout: post
title: Announcing two mpd tools
categories: [en, blog]
tags: [boogie, hooks, mpd, mpdhooker, python]
uuid: 761e0c0e-b1d2-401f-be18-55831e863b45
---

I've been working on two mpd tools lately,
[mpdhooker](http://github.com/alip/mpdhooker/tree/master) and
[boogie](http://github.com/alip/boogie/tree/master).

Mpdhooker is a daemon that adds hook support to [mpd](http://mpd.wikia.com/).
Upon certain events it executes hooks. This can be used to implement many
things, like notification windows or [last.fm](http://www.last.fm/) clients.
You can check the
[README](http://github.com/alip/mpdhooker/blob/master/README.mkd) for more
information.

Boogie is an mpc replacement written in [Python](http://www.python.org). It has
a console mode to interact with mpd that uses
[IPython](http://ipython.scipy.org/). It uses
[Mako](http://www.makotemplates.org/) templates so its output is fully
configurable.

If you want to contribute, please poke me on IRC.
