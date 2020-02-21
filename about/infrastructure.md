---
title: Infrastructure
layout: default
parent: About
nav_order: 42
---

# Infrastructure

The OpenWrt/LEDE Project relies on the considerable efforts of its volunteer
developers, the core documentation team, the forum moderators, and the host of
people who're actively using and testing the products.  The OpenWrt/LEDE team
has also provisioned many physical and virtual servers that "make the OpenWrt
(and former LEDE) Project go."

## Resources

We run the following resources and services to support the OpenWrt Project.

-   The main [OpenWrt Site](:start) and [OpenWrt Documentation](:docs:start) run on a Dokuwiki platform so that they are easy to update.
-   The [OpenWrt Forum](https://forum.openwrt.org/) (using the Discourse platform) provides a place for people to ask and answer questions about using OpenWrt, developing it, and other topics.
-   [Git servers](https://git.openwrt.org/) are the primary source code repositories for the firmware. These are cloned to [Github servers](https://github.com/openwrt) for redundancy.
-   [Bug trackers](https://bugs.openwrt.org/) are the place where bugs and feature requests are tracked
-   The [Download site](:downloads) hosts all the current and released images, sorted by architecture, vendor, and model.
    -   [KeyCDN](https://www.keycdn.com/) has graciously provided their content delivery network, so all project downloads are backed by their CDN.
-   Mailing lists: [openwrt-adm](https://lists.openwrt.org/mailman/listinfo/openwrt-adm) and [openwrt-devel](https://lists.openwrt.org/mailman/listinfo/openwrt-devel) handle the lion's share of communication for developers and the core administrative team that doesn't go through the forum.

### Buildbot

Buildbot machines detect updates to the source and kick off the build process
for each supported device.

| Version | Phase 1 - Images                                                   | Phase 2 - Packages                                                     | Fail logs                                                           | Image downloads                                                          |
| ------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| master  | [Phase 1 - Images](https://buildbot.openwrt.org/master/images/)    | [Phase 2 - Packages](https://buildbot.openwrt.org/master/packages/)    | [Fail logs](https://downloads.openwrt.org/snapshots/faillogs/)      | [images](https://downloads.openwrt.org/snapshots/targets/)               |
| 19.07   | [19.07 Images](https://buildbot.openwrt.org/openwrt-19.07/images/) | [19.07 Packages](https://buildbot.openwrt.org/openwrt-19.07/packages/) | [Fail logs](https://downloads.openwrt.org/releases/faillogs-19.07/) | [images](https://downloads.openwrt.org/releases/19.07-SNAPSHOT/targets/) |
| 18.06   | [18.06 Images](https://buildbot.openwrt.org/openwrt-18.06/images/) | [18.06 Packages](https://buildbot.openwrt.org/openwrt-18.06/packages/) | [Fail logs](https://downloads.openwrt.org/releases/faillogs-18.06/) | [images](https://downloads.openwrt.org/releases/18.06-SNAPSHOT/targets/) |
| 17.01   | [17.01 Images](http://release-builds.openwrt.org/17.01/images/)    | [17.01 Packages](http://release-builds.openwrt.org/17.01/packages/)    | TODO                                                                | [images](https://downloads.openwrt.org/releases/17.01-SNAPSHOT/targets/) |

### Servers

All these services run on machines devoted to the OpenWrt/LEDE Project.

-   We currently employ three powerful servers ([Hetzner](https://www.hetzner.de/hosting/produkte_rootserver/ex40)) to run the buildbot process, and host the downloads, Git, and mail services.
-   [Digital Ocean](https://github.com/tessel/project/issues/169) has graciously provided servers for our Documentation/wiki and Forum as part of their support for open source projects.
-   In the near future it will be important to have two more of the Hetzner servers, as we will have more buildbots and need more disk space.

### Finances

-   Each of the Hetzner servers costs about 50 Euros per month, for a total of 150 Euros/month.
-   There is a small annual charge (20-40 Euros) for registering the domain names, etc. 
-   As of late 2016, two core team members are personally covering the costs of the Hetzner servers while another core team member picks up the other fees. So far, no one has stepped up to fund the new servers that will be required in the coming months.
-   Other private parties generously donate their time & compute cycles, you know who you are and we thank you.

### Donations

There is a private discussion about possibilities of some sort of crowdfunding
to allow the community to pay back the core team for their expenses, and fund
the project going forward, but there is no public news yet.
