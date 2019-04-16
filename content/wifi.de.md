---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
headerImage: headers/wifi.jpg
---

Seit Mai 2019 gibt es nun WLAN für alle Vereinsmitglieder.
Vom Atrium bis zum Brotladen ist das WLAN unter dem Namen _StuStaNet_ erreichbar.

Wie du dein Gerät mit dem WLAN verbindest, erfährst du auf dieser Seite.
Falls du sonst noch Probleme oder Fragen hast, kannst du uns immer gerne eine [Mail](mailto:admins@stusta.de) schreiben.

## Voraussetzungen
* StuStaNet-Vereinsmitgliedschaft - Siehe [hier](../index.html)
* Mitgliedsausweis - Diesen kannst du während einer unseren [Sprechstunden](../index.html) abholen.

## Wie verbinde ich mich mit dem WLAN? 

### Android
Unter _Einstellungen > WLAN_ **Stustanet** auswählen.
Dann auf erweiterte Optionen klicken.

|**FELD**|**Wert**|
|--------|--------|
|EAP-Methode| PWD|
|Identität| [_dein Benutzername_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|


### Windows 10
WLAN **Stustanet** auswählen. Auf **Zertifikatdetails** klicken und  den Fingerabdruck vergleichen.

|**FELD**|**Wert**|
|--------|--------|
|Benutzername| [_dein Benutzername_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|
|Fingerabdruck|0F E4 C0 60 48 98 41 61 75 7B CD 7A 36 85 C1 86 BC A8 CF F2 CE CC 3B F8 7E 99 EA 27 39 3E 6B 4B|

### Linux NetworkManager 
|**FELD**|**Wert**|
|--------|--------|
|SSID| StuStaNet|
|Sicherheit| WPA & WPA2 Enterprise|
|Authentication| PWD|
|Benutzername| [_dein Benutzername_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|


### Linux NetworkManager alternative über TTLS
|**FELD**|**Wert**|
|--------|--------|
|SSID| StuStaNet|
|Sicherheit| WPA & WPA2 Enterprise|
|Authentication| Tunneled TLS|
|Anonyme Identität| anon@stusta.net|
|CA-Zertifikat| [radius stusta](https://dokumente.stusta.de/zertifikate/TODO.cert.pem)|
|Inner authentication| PAP|
|Benutzername| [_dein Benutzername_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|
