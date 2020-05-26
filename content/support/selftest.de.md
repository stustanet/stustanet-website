---
title: Selftest
header: Selftest
description: Kurze Erklärung von selftest und möglicher Fehlermeldungen
type: page
color: none
headerImage: headers/keyboard.jpg
---

Die Seite [selftest.stustanet.de](http://selftest.stustanet.de) führt verschiedene Checks aus um häufige Netzwerkprobleme zu erkennen.

**Es ist sehr wichtig diese Seite über deinen StuStaNet-Internetanschluss und nicht über dein Smartphone aufzurufen.**

Die Checks werden automatisch beim Aufrufen der Seite ausgeführt und im Idealfall sind sie alle positiv.

{{< figure src="/support/selftest/selftestok.png" title="Selftest OK" height="250" >}}


Falls du Probleme hast die Seite zu verwenden oder nicht weißt was du mit den Meldungen tun sollst, schau dir bitte die folgende Liste möglicher Fehlermeldungen an.

***

## Fehler 1: Seite nicht aufrufbar

{{< figure src="/support/nointernetchrome.png" title="Beispiel: Chrome" height="150" >}}

oder

{{< figure src="/support/nointernetfirefox.png" title="Beispiel: Firefox" height="150" >}}

Es liegt wahrscheinlich ein Problem mit deiner Router-Konfiguration oder deiner PC-Konfiguration vor.

Solltest du das nicht lösen können, dann kontaktiere bitte die Netzwerkadmins. Eine Link dazu findest du am Ende der Seite.

***

## Fehler 2: Externe IP

{{< figure src="/support/selftest/selftestextern.png" title="Fehler: Externe IP" height="300" >}}

Stelle sicher, dass du die Seite über den Netzwerkanschluss in deinem Zimmer aufrufst und nicht über dein Smartphone.

Bitte schalte VPNs und Proxys temporär ab.

***

## Fehler 3: Virensperrung

{{< figure src="/support/selftest/selftestvirus.png" title="Fehler: Virensperrung" height="70" >}}

Du wurdest virengesperrt. Dies kann mehrere Ursachen haben. Für die Gründe warum wir Virensperrungen durchführen müssen, sieh dir bitte die [FAQ]({{< ref "/support/_index.de.md#faq" >}}).

Bitte folge dem in der Fehlermeldung angezeigten Link und folge den angezeigten Schritten, um die Sperrung wieder aufzuheben.

***

## Fehler 4: Kein Mitglied

{{< figure src="/support/selftest/selftestnomember.png" title="Fehler: Kein Proxy und kein StuStaNet-Mitglied" height="70" >}}

Um von deinem Zimmer Zugriff auf das Internet zu haben, musst du entweder einen von uns bereitgestellten Proxy nutzen oder bei uns Mitglied werden.

Zur Zeit scheinst du keines von beiden zu haben.

Um den Proxy korrekt einzurichten folge bitte dem Link in der Fehlermeldung.

Zu den Vorteilen einer Mitgliedschaft kannst du dich [im Wiki](https://wiki.stusta.de/StuStaNet-Dienste) informieren. Der für dich wahrscheinlich wichtigste Vorteil ist, dass keine Proxy-Einrichtung mehr notwendig ist.

## Andere Probleme:

{{< figure src="/support/selftest/selftestunknown.png" title="Unbekannter Fehler" height="70" >}}

Bitte schicke den Log von [selftest.stustanet.de](http://selftest.stustanet.de). Siehe dazu die Seite [Supportmail]({{< ref "/support/_index.de.md#mail" >}}).
