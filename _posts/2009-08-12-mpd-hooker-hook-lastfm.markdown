---
layout: post
title: MpdHooker Hook for last.fm
categories: [en, blog]
tags: [hook, lastfm, mpdhooker, mpd, ruby, scrobbler]
uuid: 2520d3ff-0521-4ed9-96cc-b5308dd2662c
---

I wrote a sample hook for [mpdhooker](http://github.com/alip/mpdhooker/tree) to
submit songs to [last.fm](http://last.fm). It's written in
[Ruby](http://www.ruby-lang.org/) and requires
[scrobbler](http://scrobbler.rubyforge.org/).  It's very simple, doesn't do any
caching of songs that couldn't be submitted.

The hook is
[here](http://github.com/alip/mpdhooker/blob/master/conf/hooks/lastfm.rb). To
use it copy it to <tt>~/.mpdhooker/hooks/song</tt> and make it executable. Its
configuration file is <tt>~/.mpdhooker/lastfm.yaml</tt> which looks like:

    # Sample configuration file for lastfm hook.
    verbose: false
    lastfm:
        user: USERNAME
        password: PASSWORD
