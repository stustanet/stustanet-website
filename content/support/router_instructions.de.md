---
title: Allgemeine Routereinrichtung & Erste Hilfe
header: Allgemeine Routereinrichtung & Erste Hilfe
description: Kurze Hinweise wie Router in der StuSta korrekt konfiguriert werden können sowie erste Hilfe bei Problemen.
type: page
color: none
headerImage: headers/keyboard.jpg
---


{{% alert %}}
Am 14.10.23 wurde das Max-Bill-Haus von statischen IPs auf DHCP umgestellt, was zum Verlust des Internets geführt hat. Zu Informationen, was du machen musst, um die Verbindung wieder herzustellen, schau [hier]({{< ref "armageddon." >}}).
{{% /alert %}}

## Welchen Router soll ich mir kaufen?

Grundsätzlich sollte mit der richtigen Konfiguration jeder im Handel erhältliche Router funktionieren.
Für besonders einfache Einrichtung, verkaufen wir auch in unseren [Sprechstunden]({{< ref "../officehours." >}}) Router. Für diese bieten wir auch Support.

Aufgrund der vielen verschiedenen Modelle und Aktualisierungen können wir leider keine genauen Anleitungen anbieten.
Deshalb sollte diese Seite auch eher als Leitfaden und nicht als Schritt für Schritt Anleitung gesehen werden.

## Generelle Einrichtungshinweise

Wichtig beim Einrichten des Routers ist:

* Falls du kein Mitglied im StuStaNet bist, musst du erst einen Proxy einrichten.
Eine Anleitung dazu findest du [hier für die Studentenstadt](https://dokumente.stustanet.de/netzwerkanleitung/Netzwerkanleitung.pdf) und [hier fürs Max-Bill-Haus](https://dokumente.stustanet.de/netzwerkanleitung/Netzwerkanleitung_mb.pdf). [Hier](https://reg.stustanet.de/) kannst du Mitglied im StuStaNet werden und Internet ohne Proxy nutzen.
* korrekten Netzwerkanschluss an der Wand auswählen (in den meisten Zimmern sind zwei, wovon in der Regel nur die Linke funktioniert)
* richtigen Anschluss am Router für das LAN-Kabel auswählen
  (oft gibt es eine speziell markierten Anschluss (genannt *WAN*) für den Internetanschluss, Vorsicht: bei manchen Routern ist *WAN* ein DSL Port und es muss z. B. LAN 1 verwendet werden)
* Falls der Router verschiedene Betriebsmodi unterstützt, muss Anschluss an einen anderen Router und Bezug der IP-Adresse (oder etwas Vergleichbares) ausgewählt werden;
  Betrieb als Modem ist auf jeden Fall falsch
* richtige Konfiguration des Routers nach der jeweiligen beiliegenden Anleitung

## Es funktioniert trotzdem nicht?

Führe die folgenden Punkte in Reihenfolge mit eingerichtetem Router und einem damit verbundenen Gerät aus.

Sollte keine der beschriebenen Ansätze das Problem lösten, kannst du uns eine Mail schreiben.
Schreib uns dazu bitte alle Informationen die in unserem [FAQ zur Mail]({{< ref "_index.de.md#mail" >}}) aufgelistet sind und beschreibe genau was auf dieser Seite nicht funktioniert hat.

### Test 0 - StuStaNet-Router:

Nur für StuStaNet-Router:
Gehe zu [Lösung 0]({{< ref "#solution_0" >}}).

### Test 1 - Router <-> Computer Verbindung:

Kannst du das Webinterface deines Routers erreichen, wenn du mit dem Router per W-LAN oder einem LAN-Kabel verbunden bist?

Das ist die Seite auf der man die Einstellungen des Routers festlegen kann.
Sie ist über den Webbrowser mit der IP-Adresse des Routers erreichbar.

Die Adresse ist oft **192.168.1.1** (z.B. StuStaNet-Router), **192.168.0.1** oder auch **192.168.178.1** (z. B. FRITZ!Box).
Die Adresse sollte auch in der Anleitung des Routers zu finden sein.

Falls du die Einstellungen nicht erreichen kannst, gehe zu [Lösung 1]({{< ref "#solution_1" >}}).

### Test 2 - Router <-> Internet Verbindung:

Kannst du [selftest.stustanet.de](http://selftest.stustanet.de) aufrufen?
Mögliche Fehlercodes auf der Seite sind auf der Seite [Hilfe Selftest]({{< ref "selftest.de.md" >}}) beschrieben.

Sollte es zu dem dort gelisteten **_Fehler 1_** kommen, ist dein Router wahrscheinlich nicht korrekt eingerichtet.
Gehe in dem Fall zu [Lösung 2]({{< ref "#solution_2" >}})

### Lösung 0 - StuStaNet-Router: {#solution_0}

Die StuStaNet-Router haben von uns zur Unterscheidung eine Nummer bekommen.

Die Nummer kannst du auf der Packung, StuStaNet-Routeranleitung oder Routerunterseite finden.
Sie hat vier Stellen und sollte mit einem **_#_** beginnen.

#### Stustanet-Router LED-Codes für Nummer #6000 oder höher:

Die StuStaNet Router der Nummer *6000* und neuer haben einen LED Code aus dem man meistens den Fehler eingrenzen kann.

**dauerhaftes oranges leuchten:**

Es besteht keine Verbindung zum Netzwerk.
Kontrolliere, ob der Router mit dem korrekten Netzwerkanschluss an der Wand verbunden ist und ob das Kabel auch am Router im richtigen Anschluss steckt.

**oranges blinken:**

Nachdem die WPS-Taste für mehr als fünf Sekunden gedrückt wurde, führt der Router sein Setupskript aus.
Das kann etwas dauern.
Danach sollte die LED unregelmäßig blau blinken.

**unregelmäßiges blaues blinken:**

Der Router wurde konfiguriert und alles sollte zumindest auf Seiten des Routers funktionieren.
Sollte es noch immer zu Problemen kommen liegt es wahrscheinlich entweder an der Verbindung zwischen Router und Computer oder an einer Virensperrung.
Für letzteres führe [selftest.stustanet.de](http://selftest.stustanet.de) aus.

**dauerhaftes blau-oranges unregelmäßig abwechselndes (auch leicht lila) leuchten:**

Dein Router ist nicht oder nicht korrekt konfiguriert und kann keine Verbindung zum Internet aufbauen.
Führe die Konfiguration noch einmal nach der beiligenden StuStaNet-Anleitung aus und achte besonders darauf, dass der Router nachdem du den *WPS-Knopf für mehr als fünf Sekunden* gedrückt hattest orange blinkt wie oben beschrieben.

Sollte ein wiederholen der Anleitung keine Besserung bringen, kannst du versuchen den Router auf Werkszustand zurückzusetzen.

#### StuStaNet-Router Reset für Nummer #6000 oder höher:

Wenn du den Resetknopf (Einkerbung die nur mit spitzen Gegenstand erreichbar ist; nicht WPS-Knopf) für mehr als 10 Sekunden drückst, löst du den Reset auf unsere Werkseinstellungen aus.

Dabei sollte die LED des Routers kurz ausgehen, dann orange leuchten, gefolgt von orangen blinken bis der Reset fertig ist.

Anschließend kannst du nochmal versuchen die beiliegende Anleitung mit dem StuStaNet-Logo durchzuführen.

#### StuStaNet-Router Konfiguration für Nummer #5000 - #5999

Das Konfigurationsskript wird durch das drücken der Reset-Taste mit einem spitzen Gegenstand (Stift) für mehrere Sekunden ausgelöst.

#### StuStaNet-Router Konfiguration für Nummer kleiner #5000

Die anderen Router von uns werden wie in deren StuStaNet-Anleitung beschrieben mit der WPS-Taste konfiguriert.

### Lösung 1 - Router <-> Computer Verbindung: {#solution_1}

Finde heraus über welche IP-Adresse sich dein PC mit dem Router verbindet.

Bei Windows suche dazu in der Windows-Suche nach **cmd** und öffne das Programm.

{{< figure src="/support/routerproblem/searchcmd.png" height="400" >}}

In der Eingabeaufforderung tippe den Befehl **ipconfig** ein und drücke Enter.

Für dich relevant ist das Standardgateway, um damit die IP-Adresse des Routers herauszufinden.

{{< figure src="/support/routerproblem/ipconfigcmd.png" height="300" >}}

Mit der Adresse des **Standardgateway**, in dem Fall **192.168.0.1**, kannst du normalerweise im Browser die Konfigurationsseite des Routers erreichen.

Für andere Betriebssysteme sollte es ähnlich möglich sein.
Such am besten in der Suchmaschine deiner Wahl nach **Standardgateway** in Kombination mit deinem Betriebssystem.

Wenn die IP-Adresse die du rausgefunden hast sich stark von 192.168.**X**.**X** unterscheiden (z.B. 10.**X**.**X**.**X**), dann hast du wahrscheinlich eine statische IP auf deinem Computer eingestellt und musst diese wieder auf automatischen Bezug ändern.

### Lösung 2 - Router <-> Internet Verbindung: {#solution_2}

Kontrolliere und wiederhole in dem Fall noch einmal die Einrichtung und

* *Für StuStaNet-Router*: beachte die beiliegende Anleitung mit StuStaNet-Logo
* *Für normale Router*: beachte die Punkte auf der Seite [Allgemeine Routereinrichtung]({{< ref "router_instructions.de.md" >}})

Die anderen Fehler mit Lösungsansätze sind auf der Seite [Hilfe Selftest]({{< ref "selftest.de.md" >}}) genauer beschrieben.
Befolge die dortigen Anweisungen und folge den Links in der Fehlermeldung von *selftest*.


## Sonstige Hinweise

Zum Testen, ob die Einrichtung erfolgreich war, kannst du unser Tool [selftest.stustanet.de](http://selftest.stustanet.de) verwenden.
Mehr Informationen dazu findest du auf der [Hilfeseite Selftest]({{< ref "selftest.de.md" >}}).

Wenn man Wert auf maximale Datenrate und minimale Latenz legt kann es sinnvoll sein, einen Router mit Support für das 5 GHz WLAN-Netz (ac Standard oder neuer) zu kaufen, entsprechende Support im Handy und Computer natürlich vorausgesetzt.
Für den normalen Gebrauch ist das 2,4 GHz Netz allerdings vollkommen ausreichend.

Schreib uns gerne eine [E-Mail]({{< ref "/support/_index.de.md#mail" >}}) solltest du mehr Hilfe brauchen, hier einen Fehler finden oder falls du eine Anleitung hast, die du uns gerne zur Verfügung stellen willst.
