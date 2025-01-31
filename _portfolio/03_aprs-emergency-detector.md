---
title: "APRS Emergency Detector"
excerpt: "Detects APRS 'Emergency' messages and alerts the user<br/><img src='/images/aprs.gif'>"
collection: portfolio
---

While working towards my marine [LRC](https://en.wikipedia.org/wiki/Long_Range_Certificate), [SRC](https://en.wikipedia.org/wiki/Short_Range_Certificate), and [UBI](https://de.wikipedia.org/wiki/UKW-Sprechfunkzeugnis_f%C3%BCr_den_Binnenschifffahrtsfunk) radio licenses, I learned a lot about [GMDSS](https://en.wikipedia.org/wiki/Global_Maritime_Distress_and_Safety_System) and how it can be used for automated emergency signal communication. Since APRS is capable of sending out messages with a specific message type (e.g. 'Emergency'), the idea was born to write a bot which constantly listens to [APRS-IS](https://www.aprs-is.net/) and reports such messages whenever they occur.

The program supports a variety of messenger targets (via [Apprise](https://github.com/caronc/apprise/)) and is also capable of providing both full-length location messages as well as abbreviated messages that are compatible with services such as APRS.

- [APRS-Emergency-Detector Github repository](https://github.com/joergschultzelutter/aprs-emergency-detector)
