# Ringtone Library for the [WiFi Pineapple Pager](https://hak5.org/products/wifi-pineapple-pager) by [Hak5](https://hak5.org)

> **Note:** This repository is under construction.

This repository contains **community-developed ringtones** for the Hak5 **WiFi Pineapple Pager**.

Ringtones are defined using the **RTTTL (Ring Tone Text Transfer Language)** format and are used by the Pager for alerts, notifications, events, and other audible feedback.

**[🎵 Preview Ringtones Online](https://hak5.github.io/wifipineapplepager-ringtones/)** - Test and listen to ringtones in your browser before using them on your device.

Developers and musicians are encouraged to submit Pull Requests to add new ringtones or improve existing ones.

**Ringtones here are written for the official WiFi Pineapple Pager audio system.  
Hak5 does NOT guarantee ringtone compatibility across firmware versions.**  
See [Legal and Disclaimers](#legal).

---

<div align="center">
<img src="https://img.shields.io/github/forks/hak5/wifipineapplepager-ringtones?style=for-the-badge"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/github/stars/hak5/wifipineapplepager-ringtones?style=for-the-badge"/>
<br/>
<img src="https://img.shields.io/github/commit-activity/y/hak5/wifipineapplepager-ringtones?style=for-the-badge">
<img src="https://img.shields.io/github/contributors/hak5/wifipineapplepager-ringtones?style=for-the-badge">
</div>

<br/>

<div align="center">
<a href="https://hak5.org/discord"><img src="https://img.shields.io/discord/506629366659153951?label=Hak5%20Discord&style=for-the-badge"></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://youtube.com/hak5"><img src="https://img.shields.io/youtube/channel/views/UC3s0BtrBJpwNDaflRSoiieQ?label=YouTube%20Views&style=for-the-badge"/></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://youtube.com/hak5"><img src="https://img.shields.io/youtube/channel/subscribers/UC3s0BtrBJpwNDaflRSoiieQ?style=for-the-badge"/></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://twitter.com/hak5"><img src="https://img.shields.io/badge/follow-%40hak5-1DA1F2?logo=twitter&style=for-the-badge"/></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://instagram.com/hak5gear"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<br/><br/>
</div>

Join the community on **[Hak5 Discord](https://hak5.org/discord)**

---

## Table of Contents

- [Ringtone Library for the WiFi Pineapple Pager by Hak5](#ringtone-library-for-the-wifi-pineapple-pager-by-hak5)
  - [Table of Contents](#table-of-contents)
  - [Shop](#shop)
  - [Documentation / Learn More](#documentation--learn-more)
  - [Community](#community)
  - [Additional Links](#additional-links)
  - [About the WiFi Pineapple Pager](#about-the-wifi-pineapple-pager)
  - [About Pager Ringtones](#about-pager-ringtones)
  - [About RTTTL](#about-rtttl)
    - [File Format](#file-format)
    - [Design Best Practices](#design-best-practices)
    - [Prohibited Content](#prohibited-content)
  - [Legal](#legal)
  - [Disclaimer](#disclaimer)

---

## Shop

- [WiFi Pineapple Pager](https://hak5.org/products/wifi-pineapple-pager)
- [PayloadStudio Pro](https://hak5.org/products/payload-studio-pro)
- [Shop All Hak5 Tools](https://shop.hak5.org)

## Documentation / Learn More

- [WiFi Pineapple Pager Documentation](https://docs.hak5.org)

## Community

Got questions or want feedback on your ringtone?

- [Hak5 Discord](https://hak5.org/discord)

---

## Additional Links

**Follow the creators**

- [Korben on Twitter](https://twitter.com/notkorben) | [Instagram](https://instagram.com/hak5korben)
- [Dragorn on Mastodon](https://infosec.exchange/@kismetwireless)
- [Darren on Twitter](https://twitter.com/hak5darren) | [Instagram](https://instagram.com/hak5darren)

---

## About the WiFi Pineapple Pager

A WiFi Pineapple built for hackers who don’t stay put.

The **WiFi Pineapple Pager** combines Hak5’s PineAP engine with a fast, highly optimized embedded UI.  
Ringtones provide audible feedback for alerts, recon activity, payload events, and system notifications — even when the device isn’t being actively watched.

---

## About Pager Ringtones

Pager ringtones are **short audible sequences** used by the device to communicate state, alerts, and activity.

They are:

- Authored in **RTTTL**
- Parsed and played directly by the Pager
- Used for alerts, notifications, and event feedback
- Lightweight and efficient for embedded hardware

Ringtones in this repository are the **source definitions** used directly by the device — **no compilation required**.

You can **[preview and test ringtones](https://hak5.github.io/wifipineapplepager-ringtones/)** in your browser to hear how they sound before uploading them to your device.

---

## About RTTTL

RTTTL (Ring Tone Text Transfer Language) is a simple text-based format originally designed for early mobile phones.

**[Preview ringtones online](https://hak5.github.io/wifipineapplepager-ringtones/)** to hear how they sound before using them on your device.

A typical RTTTL ringtone looks like:

---

### File Format

- Ringtones must be written in **RTTTL**
- Files should contain **only** the RTTTL definition
- No binary or encoded audio formats are allowed

---

### Design Best Practices

- Keep ringtones short and distinct
- Avoid extremely high or low frequencies
- Ensure tones are clearly audible on the Pager speaker
- Avoid excessive repetition or long melodies
- Test at multiple volume levels

Ringtones that are excessively long, annoying, or disruptive may be rejected.

---

### Prohibited Content

The following will **not** be accepted:

- Audio intended to deceive or mislead users
- Offensive or inappropriate content
- Copyrighted melodies without permission
- Content that violates Hak5 community standards

---

## Legal

Ringtones from this repository are provided for **educational and customization purposes only**.

Hak5 gear is intended for authorized auditing and security analysis purposes only where permitted by local and international law. Users are solely responsible for compliance.

WiFi Pineapple and DuckyScript are trademarks of Hak5 LLC.  
Copyright © 2010 Hak5 LLC. All rights reserved.

Ringtones are subject to the Hak5 Software License Agreement:  
https://hak5.org/license

Hak5 LLC products and technology are only available to BIS recognized license exception ENC favorable treatment countries pursuant to US 15 CFR Supplement No 3 to Part 740.

---

## Disclaimer

**Ringtones are provided AS-IS without warranty.**

While Hak5 makes a best effort to review submitted ringtones, there is no guarantee of compatibility, playback quality, or correctness across firmware versions or hardware revisions.

Use at your own risk.
