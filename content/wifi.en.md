---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
headerImage: headers/wifi.jpg
---

Since April 2019 we offer Wi-Fi for all StuStaNet members. 
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
|Phase 2-Authentification (If required)| None|
|CA-certificate| _choose nothing_|
|user-certificate| _choose nothing_|
|identity| _your membership number_|
|anonymous identity| _leave emmpty_|
|password| _your password (can be found on the member card)_|

### Ubuntu
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Authentication| Tunneled TLS|
|Inner authentication| PAP|
|No CA certificate is required| _Haken setzen_|
|username| _your membership number_|
|password| _your password (can be found on the member card)_|
