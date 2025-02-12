---
title: "Multi-Purpose APRS Daemon (MPAD)"
excerpt: "My all-in-one APRS bot solution<br/><img src='/images/aprs.gif'>"
collection: portfolio
---

This article describes the use and configuration of the Apprise Multi-Messenger Platform Solution. Apprise is open source and was created in Python. A single call can be used to send messages to a wide variety of end devices via message or SMS; the call can be made either via the command line or via an API call.

__MPAD__ was my introduction to both Python and APRS.

The challenge was manifold:

- most existing APRS bots only support US-specific services. For example, worldwide weather reports etc. were therefore not possible.
- in addition, the bots are usually very specialized and only support 1-2 functions
- I had just acquired my amateur radio license and wanted to give something back to the community
- The APRS documentation was widely distributed, so a lot of reverse engineering was required.
- I was looking for an entry-level project in Python3.

The result of all these points and requirements is __MPAD__, which I run on a Raspberry Pi.

Jason/KM4ACK was kind enough to review my little APRS bot in a dedicated video:
[![MPAD review by Jason/KM4ACK](https://img.youtube.com/vi/75W0UTL5eOY/0.jpg)](https://www.youtube.com/watch?v=75W0UTL5eOY)

__MPAD__ has been part of the APRS Foundation's "State Of The Union" presentation at the Orlando Hamcation 2025:
- [Online version](https://www.aprsfoundation.org/hamcation-2025/)
- [Offline version](/files/20250207---APRS-Foundation---APRS---State-of-the-Union---Orlando-Hamcation-2025.pdf)

Github Repository and __MPAD__ live instance:
- [MPAD Github Repository](https://github.com/joergschultzelutter/mpad)
- [Bot live instance on aprs.fi](https://aprs.fi/#!z=11&call=a%2FMPAD&timerange=3600&tail=3600)
