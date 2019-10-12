---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
class: wifi
headerImage: headers/outdoor.jpg
---
Im Areal der Studentenstadt bietet StuStaNet für Mitglieder in Außenbereichen und Gemeinschaftseinrichtungen das StuStaNet WLAN an. Wie du dein Gerät mit dem WLAN verbindest, erfährst du auf dieser Seite.

{{% warn %}} StuStaNet WLAN befindet sich in der Testphase. Verfügbarkeitsprobleme sind zu erwarten und Einstellungen können sich ändern.{{% /warn %}}

<div class="callout callout-default">
    <h3>WLAN fürs eigene Zimmer</h3>
    <img src="/figures/router_m.jpg" class="router">
    <p>Außen-WLAN ist toll, aber WLAN im eigenen Zimmer wäre noch besser?</p>
    <p>Wir stellen vor: Der StuStaNet WLAN Router!</p>
    <ul>
        <li><i class="fa fa-check" aria-hidden="true"></i>Plug & Play: Anschließen und fertig.</li>
        <li><i class="fa fa-heart" aria-hidden="true"></i>Unsere Software konfiguriert sich komplett automatisch!</li>
        <li><i class="fa fa-tachometer" aria-hidden="true"></i>450Mbit/s WLAN (IEEE 802.11b/g/n)</li>
        <li><i class="fa fa-euro" aria-hidden="true"></i>Verkauft zum Selbstkostenpreis. Nur für Mitglieder.</li>
    </ul>
    <p><b>Verfügbar in unseren <a href="{{< ref "officehours.de.md" >}}">Sprechstunden</a>.</b></p>
</div>

## Voraussetzungen
* StuStaNet-Vereinsmitgliedschaft - Siehe [hier](/)
* Mitgliedsausweis - diesen kannst du während einer unserer [Sprechstunden]({{< ref "officehours.de.md" >}}) abholen.

## Wie verbinde ich mich mit dem WLAN?

### <i class="fa fa-android"></i> Android {#android}
Unter _Einstellungen > WLAN_ **StuStaNet** auswählen.
Dann auf **erweiterte Optionen** klicken.

|**Feld**|**Wert**|
|--------|--------|
|EAP-Methode| PWD|
|Identität| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|


### <i class="fa fa-windows"></i> Windows 10 {#windows-10}
WLAN **StuStaNet** auswählen. Auf **Zertifikatdetails** klicken und  den Fingerabdruck vergleichen.

|**Feld**|**Wert**|
|--------|--------|
|Benutzername| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|
|Fingerabdruck|0F E4 C0 60 48 98 41 61 75 7B CD 7A 36 85 C1 86 BC A8 CF F2 CE CC 3B F8 7E 99 EA 27 39 3E 6B 4B|

### <i class="fa fa-linux"></i> Linux NetworkManager {#linux-networkmanager}
|**Feld**|**Wert**|
|--------|--------|
|SSID| StuStaNet|
|Sicherheit| WPA & WPA2 Enterprise|
|Authentication| PWD|
|Benutzername| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|


### <i class="fa fa-linux"></i> Linux NetworkManager Alternative über TTLS {#linux-networkmanager-alternative-via-ttls}
|**Feld**|**Wert**|
|--------|--------|
|SSID| StuStaNet|
|Sicherheit| WPA & WPA2 Enterprise|
|Authentication| Tunneled TLS|
|Anonyme Identität| anon@stusta.net|
|CA-Zertifikat| [radius StuStaNet](/wifi/StuStaNet-wifi.stusta.pem)|
|Inner authentication| PAP|
|Benutzername| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|

### <i class="fa fa-apple"></i> MacOS via Netzwerkprofil  {#macos-via-netzwerkprofil}
|**Option**|**Value**|
|--------|--------|
|SSID| StuStaNet|
|Netzwerkprofil| [StuStaNet.mobileconfig](/wifi/StuStaNet.mobileconfig)|
|Benutzername| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|
