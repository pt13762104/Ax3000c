---
title: OS
---
The router runs OpenWRT but heavily modified (19.07-SNAPSHOT (security issues?, as of version 0.2.7), OpenWRT have no support for this chip).

* The OS is immutable, the configs were stored in `/aeimnt`.

* The control panel is `oui`, not LuCI (closed source)

* Opkg does not work, since 19.07-SNAPSHOT is unsupported

* No real OpenWRT support

* Only 430MB of RAM is available, only 180MB is available to external apps (Avail+Used seems to sum to 310MB)

* Kernel version: `5.4`
