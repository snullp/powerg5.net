---
layout: post
title:  "G5 Linux support as of 2020"
date:   2020-01-21 22:16:40 -0800
---
At year 2020, the 15-year-old PowerMac G5 is not a first-class citizen:

* OS X that support G5 are completely outdated: the latest compatible version is OS X 10.6 Leopard. They are slow, insecure, and incompatible with anything online.
* Its big-endian ppc64 architecture is a relic. Modern software support for POWER is focusing on ppc64le, the little-endian flavor now adopted by IBM for all new POWER processors.

Fortunately, there are still ways to install modern Linux distros on your G5:

* Gentoo
* Debian Jessie (support ended for ppc64)
* Debian Sid ppc64 port (aka unstable)
* Ubuntu 16.04 LTS (still receiving security LTS)

I recommend Ubuntu (including its siblings Lubuntu, Xubuntu for lower resource consumption) for average users. But if you want newest kernel / software, which also means constantly broken, you can choose the Debian Sid rabbit hole.

## G5 Ubuntu Installation
TBD

## G5 Debian Sid installation
Sid is the alias of Debian code name 'unstable'. Generally the repo contains newest build of packages, but they may be buggy.
Sid or 'unstable' will not freeze for stability, thus, keeping track of Sid turns Debian into a rolling release distribution.

The installation of Debian is a bit tricky, which is TBD
