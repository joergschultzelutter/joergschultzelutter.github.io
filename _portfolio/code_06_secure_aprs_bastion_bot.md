---
title: "Secure APRS Bastion Bot"
excerpt: "Maintain your IT infrastructure via APRS messaging<br/><img src='/images/aprs.gif'>"
collection: portfolio
---

`secure-aprs-bastion-bot` is based on my very own [core-aprs-client](https://github.com/joergschultzelutter/core-aprs-client) framework. It enables users to manage their IT infrastructure using APRS messaging. All possible commands are assigned to specific call signs and additionally secured by TOTP codes; furthermore, the validity of the TOTP code can be freely configured between 30 seconds and 5 minutes. Multiple use of an already used TOTP code within its validity time window is also prevented. In addition, up to nine additional parameters can be transmitted as part of the APRS message and passed on to the script to be executed.

- [secure-aprs-bastion-bot Repository](https://github.com/joergschultzelutter/secure-aprs-bastion-bot)
