---
layout: post
title: First tool ... pyshowrss
date: 2016-03-10
---

Today I'm releasing my first (of hopefully many) simple python tool to the world: [pyshowrss](https://github.com/pyface-net/pyshowrss)

[pyshowrss](https://github.com/pyface-net/pyshowrss) is a simple tool that leverages your personal [ShowRSS](https://new.showrss.info/) feed to download your .torrent files to a directory of your choosing and can also post process those .torrent files.

With other Torrent tools like [SickBeard](http://sickbeard.com/) and [FlexGet](http://flexget.com/) being readily available, you might ask, why do you need another tool? To be honest, I just wanted a *simpler* Torrent downloading tool that would work well for [ShowRSS](https://new.showrss.info/).

Some quick googling led me to [this tool](https://github.com/jbmorley/showrss) which almost fit the bill, but wasn't quite what I was looking for. So I saw this as an opportunity to tinker with some python and make some changes/improvements...  [pyshowrss](https://github.com/pyface-net/pyshowrss) is the result of that. Hopefully some of you will find it useful.. or take it upon yourselves to modify/fork it for your own needs.

For those of you on Windows, I've provided a [setup program](https://github.com/pyface-net/pyshowrss/raw/master/installer/windows/pyshowrss_setup_0.1.exe) to install the tool. Run it and then modify the `user_id` value in the `pyshowrss.ini` file to whatever your ShowRSS user id is:

<html>
<!-- HTML generated using hilite.me --><br><div style="background: #ffffff; overflow:auto;width:auto;border:solid gray;border-width:.1em .1em .1em .8em;padding:.2em .6em;"><pre style="margin: 0; line-height: 125%">; a valid showrss user <span style="color: #007020">id</span>
; replace <span style="color: #4400EE; font-weight: bold">00000</span> <span style="color: #008800; font-weight: bold">with</span> your user <span style="color: #007020">id</span> <span style="color: #008800; font-weight: bold">from</span> <span style="color: #0e84b5; font-weight: bold">showrsss</span>
user_id <span style="color: #333333">=</span> <span style="color: #4400EE; font-weight: bold">00000</span>
</pre></div><br>
</html>


Once thats done, simply running `pyshowrss.exe` with not arguments will download the .torrent files from your ShowRSS feed into a `torrents` sub folder by default.


