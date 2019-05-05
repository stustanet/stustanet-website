---
title: Support
header: Support
description: Erste Hilfe bei Problemen mit deinem Internetanschluss in der StuSta
type: page
color: none
headerImage: headers/keyboard.jpg
---

## Problem (WIP)
Du hast einen angeschlossenen StuStaNet Router.

Du bist per W-Lan mit dem Router verbunden, aber hast keine Verbindung zum Internet, d.h. die Website [selftest.stusta.de](http://selftest.stusta.de) lädt überhaupt nicht über deinen Internetanschluss.

Stattdessen wird dir eine Fehlermeldung angezeigt.

{{< figure src="/support/nointernetchrome.png" title="Beispiel Chrome" height="150" >}}

oder

{{< figure src="/support/nointernetfirefox.png" title="Beispiel Firefox" height="150" >}}


Bitte führe die folgenden Schritte auf einem mit deinem Internetanschluss verbundenen Gerät aus und **nicht** über dein Smartphone.
***

## Wichtig:
Hat dein Routernummer eine 5000er Routernummer, also die Nummer die auf der Rückseite des Routers auf dem StuStaNet Aufkleber nach dem #-Zeichen steht ist #5XXX (oder auf der Schachtel), dann wird das Konfigurationsskript durch das drücken der Reset-Taste mit einem spitzen Gegenstand (Stift) für mehrere Sekunden drückt.

Dies trifft nur auf die Router der 5000er Reihe zu. Die Anderen werden wie in der Anleitung beschrieben mit der WPS-Taste konfiguriert.

## Tests um die Fehlerquelle zu finden:
### Test 1:
Kannst du deinen Router über das Webinterface erreichen?

Um das zu versuchen rufe über die Adresszeile deines Webrowsers die Adresse `192.168.1.1` auf.

Falls du die Login-Page erreichst gehe zu xxxx.

Falls nicht:

### Test 2:
Finde heraus über welche IP sich dein PC mit dem Router verbindet.

Für Windows führe dafür den Befehl `ipconfig` in der Eingabeaufforderung aus.

Suche dazu in der Windows-Suche nach `cmd`.

{{< figure src="/support/searchcmd.png" title="CMD Suche" height="400" >}}

Tippe in dem sich öffnenden Fenster `ipconfig` ein und drücke Enter. Suche in der Ausgabe des Befehls nach der Zeile

{{< figure src="/support/ipconfigcmd.png" title="IPconig output" height="200" >}}

Unterscheidet sich die IP-Adresse rechts von `IPv4-Adresse` von `192.168.1.`**X**, wobei X eine beliebige Zahl sein kann, dann gehe zu xxxxxx.
