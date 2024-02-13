---
title: "How to Avoid Phishing or Hacking with Binance Apps"
categories: [exchanges, security]
header:
  teaser: /posts-images/hacked.png
---

#### Website 

I am truly paranoid when it comes to OPSEC. Because website checkers come and go. I check certificates myself if site is genuine. In Chrome, after going to 
Binance.com, you click the "view site information" icon and then click "connection is secure" and then click "certificate is valid". You should see
SHA-256 Fingerprints.

Currently Binance.com is:

`Validity until: February 11, 2025 SHA-256: a26834e9071cbf6a00fc6936c9955f4fe345fc83c03960cc289e3642041ce512)`

I named my Binance website browser shortcut as a26-512 to note fingerprint. So everytime I log in I check.

#### Windows Desktop App

Download only at <https://www.binance.com/en/download> or check <https://github.com/binance/desktop/releases>

Download the installer and right-click check properties. Click digital signatures tab, pick sha-1 or sha-256 and click details, click view certificate,
note validity period of signature and then click details tab and then scroll down to thumbprint, you should see the below:

`Validity until: December 31, 2024 SHA-256: 9e0dd4fea8e343c257076fb506ceed9c48b32a7f`

This will be the thumbprint for all versions until end of year.

#### Binance Android App

I prefer to download from Binance itself, not sure if Google Playstore is hackproof in the future. Anyway, download the android app at [Binance](https://www.binance.com/en/download) 
Check the checksum of the APK for reference. I use 7-ZIP to check:

`Name: BNApp64.apk
Size: 187865441 bytes (179 MiB)
HA256: 57C48A6D87F59FB9C11D8B9729F90CC27BE4294346564B7C97F4C3DDD1F6276A
SHA1: 8DA40E91467EAE6FB1B7CFE13049EAF1EB5B0E34)`

According to Google Playstore, this version is 2.78.5. Install apk and then disable auto-updating the app in Playstore.

**PS: I will update this post if checksum values change in the future.**