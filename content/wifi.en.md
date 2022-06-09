---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
class: wifi
headerImage: headers/outdoor.jpg
---
In the Studentenstadt StuStaNet offers the StuStaNet WLAN for members in outdoor areas and community facilities. On this page, you will learn how to connect your device to the Wi-Fi.

{{% warn %}} StuStaNet Wi-Fi is in the testing phase. Downtimes are to be expected and settings may change.{{% /warn %}}

<div class="callout callout-default">
    <h3>Wi-Fi for your room</h3>
    <img src="/figures/router_m.jpg" class="router">
    <p>Outdoor Wi-Fi is great, but Wi-Fi in your own room would be even better?</p>
    <p>Meet the StuStaNet Wi-Fi Router!</p>
    <ul>
        <li><i class="fa fa-check" aria-hidden="true"></i>Plug & Play: Connect and done.</li>
        <li><i class="fa fa-heart" aria-hidden="true"></i>Our software does all the configuration automatically!</li>
        <li><i class="fa fa-tachometer" aria-hidden="true"></i>450Mbit/s WLAN (IEEE 802.11b/g/n)</li>
        <li><i class="fa fa-euro" aria-hidden="true"></i>Sold at cost price. For members only.</li>
    </ul>
    <p><b>Available in our <a href="{{< ref "officehours.en.md" >}}">office hours</a>.</b></p>
</div>

## Prerequisites
* StuStaNet-Membership - More information [here](/)
* Living in a room the StuSta
* Wifi Access - Can be created on the StuStaNet [account page](https://account.stustanet.de)

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
Select WiFi **StuStaNet**.

|**Option**|**Value**|
|--------|--------|
|Username| [_your username@stusta.de_](https://account.stustanet.de/login)|
|Password| [_your password_](https://account.stustanet.de/login)|

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

