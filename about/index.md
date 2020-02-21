---
title: About
layout: default
has_children: true
nav_order: 40
---

## About the OpenWrt/LEDE project

OpenWrt is a highly extensible GNU/Linux distribution for embedded devices
(typically wireless routers). Unlike many other distributions for these
routers, OpenWrt is built from the ground up to be a full-featured, easily
modifiable operating system for your router. In practice, this means that you
can have all the features you need with none of the bloat, powered by a Linux
kernel that's more recent than most other distributions.

### What is OpenWrt?

Instead of trying to create a single, static firmware, OpenWrt provides
a fully writable filesystem with optional package management. This frees
you from the restrictions of the application selection and configuration
provided by the vendor and allows you to use packages to customize an
embedded device to suit any application. For developers, OpenWrt
provides a framework to build an application without having to create a
complete firmware image and distribution around it. For users, this
means the freedom of full customization, allowing the use of an embedded
device in ways the vendor never envisioned.

### A reboot of the OpenWrt community

In 2016, the LEDE project was founded as a spin-off of the OpenWrt
project and shared many of the same goals. The project aimed at building
an embedded Linux distribution that makes it easy for developers, system
administrators or other Linux enthusiasts to build and customize
software for embedded devices, especially wireless routers. The name
*LEDE* stood for *Linux Embedded Development Environment*.

Members of the project included a significant share of the most active
members of the OpenWrt community and intended to bring new life to
Embedded Linux development by creating a community with a strong focus
on transparency, collaboration and decentralisation.

LEDE's stated goals were:

 * Build a great embedded Linux distribution with focus on stability and functionality.
 * Make regular, predictable release cycles coupled with community provided device testing feedback.
 * Establish transparent decision processes with broad community participation and public meetings.

The formation of the LEDE project was decided to solve long standing
issues that were deemed unfixable from within the OpenWrt
project/community:

 - Number of active core developers at an all time low, no process for getting more new people involved.
 - Unreliable infrastructure, fixes prevented by internal disagreements and single points of failure.
 - Lack of communication, transparency and coordination in the OpenWrt project, both inside the core team and between the core team and the rest of the community.
 - Not enough people with commit access to handle the incoming flow of patches, too little attention to testing and regular builds.
 - Lack of focus on stability and documentation.

To address these issues, the LEDE project was set up in a different way
compared to OpenWrt:

 - All communication channels are public, some read-only to non-members to maintain a good signal-to-noise ratio.
 - Decision making process is more open, with an approximate 50/50 mix of developers and power users with voting rights.
 - Infrastructure is simplified a lot, to ensure that it creates less maintenance work for us.
 - More liberal merge policy, based on our experience with the OpenWrt package github feed.
 - Strong focus on automated testing combined with a simplified release process.

### Announcing the OpenWrt/LEDE merge

As of January 2018, both the OpenWrt and LEDE projects agreed to
re-merge back under the OpenWrt name.

The new, unified OpenWrt project is governed under the [rules
established by the former LEDE project](:rules). Active
members of both the former LEDE and OpenWrt projects contribute to the
unified OpenWrt.

## Joint future

LEDE\'s fork and subsequent re-merge into OpenWrt did not alter the
overall technical direction taken by the unified project. OpenWrt will
continue to work on improving stability and release maintenance while
aiming for frequent minor releases to address critical bugs and security
issues like LEDE did with the 17.01 series and its multiple point
releases until now.

Old pre-15.05 OpenWrt CC releases are not supported by the merged
project anymore, leaving them without any future security or bug fixes.
The OpenWrt CC 15.05 release series did receive a limited amount of
security and bug fixes, but due to its lacking integration in the
release automation, no further binary image releases were made.

The merged project uses the code base of the former LEDE project.
OpenWrt specific patches not present in the LEDE repository but meeting
LEDEs code quality requirements got integrated into the new tree while
the source code has been moved to
[git.openwrt.org](https:*git.openwrt.org/) with a
continuously synchronized mirror hosted at
[Github](https:*github.com/openwrt/openwrt). The original
OpenWrt codebase has been [archived on
Github](https:*github.com/openwrt/archive) for future
reference.

The remerged OpenWrt project is legally represented by the [Software in
the Public Interest (SPI)](https:*www.spi-inc.org/) - an US
501(c)(3) non-profit organization which is [managing our OpenWrt
trademark](https:*www.spi-inc.org/projects/openwrt/),
handling our donations and helping us with legal problems.

Infrastructure formerly available under the lede-project.org domain has
been mostly moved to corresponding openwrt.org subdomains and redirects
were put in place when appropriate.

### Name

  The name *OpenWrt* stems from the beginning of the open wireless router
  movements, starting with the [first White Russian releases](about:history)
  for WRT54G routers, marking the start of future wireless router firmware
  development.    The name *LEDE* is an abbreviation for Linux Embedded
  Development Environment, a reference to its flexibility and embedded
  buildroot origins, making it a solid choice for embedded Linux applications
  far beyond the wireless router and network appliance realm. 

### Meeting Logs

IRC meeting logs done during the LEDE fork can be viewed
[here](http:*meetings.lede-project.org/lede-adm/).

[Real life / F2F meetings](meetings/start)

### People

Here you can find an alphabetically ordered list of the current people
involved in *OpenWrt* Project:

| Developers | Nickname |
| --- | --- |
| Adrian Schmutzler | [adrianschmutzler](developers/adrianschmutzler) |
| Alexander Couzens | [lynxis](developers/lynxis) |
| Álvaro Fernández Rojas | [noltari](developers/noltari) |
| Christian Lamparter | [lach1012](developers/lach1012) |
| Chuanhong Guo | [981213](developers/981213) |
| Daniel Golle | [dangole](developers/dangole) |
| David Bauer | [blocktrron](developers/blocktrron) |
| Felix Fietkau | [nbd](developers/nbd) |
| Florian Fainelli | [florian](developers/florian) |
| Hans Dedecker | [dedeckeh](developers/dedeckeh) |
| Hauke Mehrtens | [hauke](developers/hauke) |
| Imre Kaloz | [kaloz](developers/kaloz) |
| Jo-Philipp Wich | [jow](developers/jow) |
| John Crispin | [blogic](developers/blogic) |
| Jonas Gorski | [jogo](developers/jogo) |
| Kevin Darbyshire-Bryant | [ldir](developers/ldir) |
| Koen Vandeputte | [xback](developers/xback) |
| Luka Perkov | [luka](developers/luka) |
| Mathias Kresin | [mkresin](developers/mkresin) |
| Matthias Schiffer | [neoraider](developers/neoraider) |
| Mirko Vogt | [mirko](developers/mirko) |
| Petr Štetiar | [ynezz](developers/ynezz) |
| Piotr Dymacz | [pepe2k](developers/pepe2k) |
| Rafał Miłecki | [rmilecki](developers/rmilecki) |
| Steven Barth | [cyrus](developers/cyrus) |
| Stijn Tintel | [stintel](developers/stintel) |
| Ted Hess | [thess](developers/thess) |
| Yousong Zhou | [yousong](developers/yousong) |
| Zoltan Herpai | [wigyori](developers/wigyori) |

| Wiki Documentation | Nickname |
| --- | --- |
| Thomas Endt | [tmomas](user/tmomas) |
| Rich Brown | richb-hanover |
| Alberto Bursi | bobafetthotmail |
