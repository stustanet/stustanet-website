---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
headerImage: headers/wifi.jpg
---

Since May 2019 we offer Wi-Fi for all StuStaNet members. 
You can find it under the name _StuStaNet_.

On this page, you will learn how to connect your device to the Wifi.
If you have any questions or comments you can [write us](mailto:admins@stusta.de).

## Prerequesites
* StuStaNet-Membership - More information [here](../index.html)
* member card - Can be picked up during one of our [office hours](../index.html).

## How do I connect to the Wi-Fi?

### Android
Goto _Settings > Wifi_ and choose **Stustanet**.
Then choose **more options**.

|**Option**|**Value**|
|--------|--------|
|EAP-Method| PWD|
|identity| [_your username_](https://account.stustanet.de/login)|
|password| [_your password_](https://account.stustanet.de/login)|

### Windows 10
Select WiFi **Stustanet**. Click on **Certificate details** and compare the Fingerprint.

|**Option**|**Value**|
|--------|--------|
|username| [_your username_](https://account.stustanet.de/login)|
|password| [_your password_](https://account.stustanet.de/login)|
|Fingerprint|0F E4 C0 60 48 98 41 61 75 7B CD 7A 36 85 C1 86 BC A8 CF F2 CE CC 3B F8 7E 99 EA 27 39 3E 6B 4B|



### Linux NetworkManager
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Security| WPA & WPA2 Enterprise|
|Authentication| PWD|
|Username| [_your username_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

### Linux NetworkManager alternative via TTLS
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Security| WPA & WPA2 Enterprise|
|Authentication| Tunneled TLS|
|CA-Zertifikat| [radius stusta](https://dokumente.stusta.de/zertifikate/TODO.cert.pem)|
|Inner authentication| PAP|
|Username| [_your username_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|
