---
layout: post
title: pyrasdialer
date: 2016-04-20
---

I've been slowsly working on another useful (i think) tool to assist with managing Windows VPN connections: [pyrasdialer](https://github.com/pyface-net/pyrasdialer)

[pyrasdialer](https://github.com/pyface-net/pyrasdialer) leverages the rasdial inbox tools in Windows to connect, disconnect, and monitor your VPN connection in an automated fashion. Depending on how its configured, pyrasdialer can be used to keep your VPN connection up by monitoring it and reconnecting if dropped. Also, pyrasdialer can be provided a list of servers and each re connection can be randomized to a different VPN server.

There are some subtle annoyances with out `rasdial.exe` uses and dials phonebook entires -- and I'm still working through those. Regardless, I've been successfully using [pyrasdialer](https://github.com/pyface-net/pyrasdialer) to  monitor my VPN connections so I felt it would be useful to share now as I continue to work through some minor issues.

Enjoy.. and please report back any bugs!


