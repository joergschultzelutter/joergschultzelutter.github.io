---
title: "mowas-pwb (open-source Katwarn clone)"
excerpt: "My open-source katwarn clone<br/><img src='/images/mowas-pwb-image.svg'>"
collection: portfolio
---

__mowas-pwb__ is an open-source reverse-engineered version of Germany's [Katwarn](https://www.katwarn.de/en/) clone. Unlike its official release, __mowas-pwb__ supports additional features such as:

- bilingual language support thanks to optional translation services from German into other languages such as English or Russian
- [APRS](http://www.aprs.org/) support with dynamic positioning
- Unlike [Katwarn](https://www.katwarn.de/en/) which is mainly available as an app-based solution, __mowas-pwb__ can be hosted on your very own infrastructure.
- Additionally, __mowas-pwb__ supports the message distribution to numerous messengers, SMS-based devices, and other messaging services at the same time - thanks to the [Apprise Push Notification](https://github.com/caronc/apprise) module, including APRS, mail, and pager devices, thus increasing the possibility of receiving a warning message in the event of an infrastructure failure. So if an alert is generated for one of your monitoring areas, you can receive this alert via several messenger services such as Telegram, pager or email at the same time.
- Normally, [Katwarn](https://www.katwarn.de/en/) messages contain a lot of explanatory text (a greeting to German bureaucracy). Usually, these texts are not relevant to the end user in their entirety. Furthermore, processing very long standard texts (e.g. 2,000 characters) makes it difficult __mowas-pwb__ to send warnings to devices with limited message length (pagers, SMS, etc.). __mowas-pwb__ uses optional AI-based services to shorten the warning message to an absolute minimum without changing the core of the message.
- In addition, __mowas-pwb__ supports freely configurable standard and emergency threshold values and/or configurations. For example, if you do not want to receive warnings related to “flooding,” these warnings can be disabled. Furthermore, reaching an emergency threshold shortens the intervals at which the program checks for new or updated messages.

Currently, this program is limited to alerts related to Germany. Since there are plans to use [Katwarn](https://www.katwarn.de/en/) for all EU countries, this could change in the future.

- [mowas-pwb Github repository](https://github.com/joergschultzelutter/mowas-pwb)
