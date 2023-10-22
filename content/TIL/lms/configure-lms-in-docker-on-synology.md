---
title: "Configure LMS in Docker on Synology"
date: 2023-10-22T16:23:52+02:00
draft: false
bookCollapseSection: false
---

Because Synology DSM comes with an old version of Logitech Media Server, I chose to move away from the native package and run the newer, community-maintained edition within a Docker container. The image can be found in Hub under [https://hub.docker.com/r/lmscommunity/logitechmediaserver](https://hub.docker.com/r/lmscommunity/logitechmediaserver).

Configuration required some tweaking to get working (especially permissions), but once set up it runs well.

![LMS Docker Configuration](/til/images/docker-lms.png)
