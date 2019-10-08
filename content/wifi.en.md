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

<div class="callout callout-default">
    <h3>Wi-Fi for your room</h3>
    <img src="/router.jpg" class="router">
    <p>Outdoor Wi-Fi is great, but Wi-Fi in your own room would be even better?</p>
    <p>Meet the StuStaNet Wi-Fi Router!</p>
    <ul>
        <li><i class="fa fa-check" aria-hidden="true"></i>Plug & Play: Connect and done.</li>
        <li><i class="fa fa-heart" aria-hidden="true"></i>Our software does all the configuration automatically!</li>
        <li><i class="fa fa-tachometer" aria-hidden="true"></i>450Mbit/s WLAN (IEEE 802.11b/g/n)</li>
        <li><i class="fa fa-euro" aria-hidden="true"></i>Sold at cost price. For members only.</li>
    </ul>
    <p><b>Available in our <a href="{{< ref "/#next-office-hours" >}}">office hours</a>.</b></p>
</div>

## Prerequisites
* StuStaNet-Membership - More information [here](../)
* Member Card - Can be picked up during one of our [office hours](../).

## How do I connect to the Wi-Fi?

### <i class="fa fa-android"></i> Android {#android}
Go to _Settings > Wifi_ and choose **StuStaNet**.
Then choose **more options**.

|**Option**|**Value**|
|--------|--------|
|EAP-Method| PWD|
|Identity| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

### <i class="fa fa-windows"></i> Windows 10 {#windows-10}
Select WiFi **StuStaNet**. Click on **Certificate details** and compare the Fingerprint.

|**Option**|**Value**|
|--------|--------|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|
|Fingerprint|0F E4 C0 60 48 98 41 61 75 7B CD 7A 36 85 C1 86 BC A8 CF F2 CE CC 3B F8 7E 99 EA 27 39 3E 6B 4B|

### <i class="fa fa-linux"></i> Linux NetworkManager {#linux-networkmanager}
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Security| WPA & WPA2 Enterprise|
|Authentication| PWD|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

### <i class="fa fa-linux"></i> Linux NetworkManager Alternative via TTLS {#linux-networkmanager-alternative-via-ttls}
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

### <i class="fa fa-apple"></i> MacOS via Networkprofile {#macos-via-networkprofile}
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Networkprofile| [StuStaNet.mobileconfig](/wifi/StuStaNet.mobileconfig)|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

