---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
class: wifi
headerImage: headers/wifi.jpg
---

In the Studentenstadt area StuStaNet provides the Wi-Fi "StuStaNet" for StuStaNet members. On this page, you will learn how to connect your device to the Wi-Fi. If you have any questions or comments you can [write us](https://stustanet.de/mail/admins).

<span style="background:#FFDADA; margin:20px 0 0; padding:6px 0; width:100%; max-width:100%;">StuStaNet Wi-Fi is under development. Expect downtime. Settings may change.</span>

## Prerequisites
* StuStaNet-Membership - More information [here](../index.html)
* Member Card - Can be picked up during one of our [office hours](../index.html).

## How do I connect to the Wi-Fi?

### Android
Go to _Settings > Wifi_ and choose **StuStaNet**.
Then choose **more options**.

|**Option**|**Value**|
|--------|--------|
|EAP-Method| PWD|
|Identity| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

### Windows 10
Select WiFi **StuStaNet**. Click on **Certificate details** and compare the Fingerprint.

|**Option**|**Value**|
|--------|--------|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|
|Fingerprint|0F E4 C0 60 48 98 41 61 75 7B CD 7A 36 85 C1 86 BC A8 CF F2 CE CC 3B F8 7E 99 EA 27 39 3E 6B 4B|

### Linux NetworkManager
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Security| WPA & WPA2 Enterprise|
|Authentication| PWD|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

### Linux NetworkManager alternative via TTLS
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Security| WPA & WPA2 Enterprise|
|Authentication| Tunneled TLS|
|Anonymous identity| anon@stusta.net|
|CA-Certifikate| [radius stusta](/wifi/StuStaNet-wifi.stusta.pem)|
|Inner authentication| PAP|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

### MacOS via Networkprofile
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Networkprofile| [StuStaNet.mobileconfig](/wifi/StuStaNet.mobileconfig)|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

