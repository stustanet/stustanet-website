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

## Wie verbinde ich mich mit dem WLAN?

1. Du musst Mitglied beim StuStaNet sein - siehe [hier] (https://stustanet.de/de/)
2. Du brauchst deine Mitgliedsnummer. Du kannst sie in deiner Registrierungsmail finden oder bei vorstand[at]stustanet.de erfragen.
3. Geh auf die [Account Seite](https://account.stustanet.de) und resette dein Passwort. Dafür musst du mit dem Internet in deinem Zimmer verbunden sein.
4. Dann klicke auf Services - Reset Passwords for Services - WLAN (Mitglieder WLAN) - Reset
5. Die Seite generiert ein Passwort für dich.
6. Danach kannst du dein Gerät so verbinden:

### <i class="fa fa-android"></i> Android {#android}
Unter _Einstellungen > WLAN_ **StuStaNet** auswählen.
Dann auf **erweiterte Optionen** klicken.

|**Feld**|**Wert**|
|--------|--------|
|EAP-Methode| PWD|
|Identität| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|


### <i class="fa fa-windows"></i> Windows 10 {#windows-10}
WLAN **StuStaNet** auswählen.

|**Feld**|**Wert**|
|--------|--------|
|Benutzername| [_dein Benutzername@stusta.de_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|

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
