---
title: StuStaNet Goes WLAN
header: StuStaNet Goes WLAN
description: WLAN in der StuSta
type: page
color: none
headerImage: headers/wifi.jpg
---

Seit April 2019 gibt es nun WLAN für alle Vereinsmitglieder.
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
|EAP-Methode| TTLS|
|Phase 2-Authentifizierung (Falls vorhanden)| PAP|
|CA-Zertifikat| [radius stusta](https://dokumente.stusta.de/zertifikate/TODO.cert.pem)|
|Identität| [_deine Benutzname_](https://account.stustanet.de/login)|
|Anonyme Identität| anon@stusta.net|
|Password| [_dein Passwort_](https://account.stustanet.de/login)|

### Ubuntu
|**FELD**|**Wert**|
|--------|--------|
|SSID| StuStaNet|
|Sicherheit| WPA & WPA2 Enterprise|
|Authentication| Tunneled TLS|
|Anonyme Identität| anon@stusta.net|
|CA-Zertifikat| [radius stusta](https://dokumente.stusta.de/zertifikate/TODO.cert.pem)|
|Inner authentication| PAP|
|Benutzername| [_deine Benutzname_](https://account.stustanet.de/login)|
|Passwort| [_dein Passwort_](https://account.stustanet.de/login)|
