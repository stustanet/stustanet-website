---
title: Allgemeine Routereinrichtung
header: Allgemeine Routereinrichtung
description: Kurze Hinweise wie Router in der StuSta korrekt konfiguriert werden können.
type: page
color: none
headerImage: headers/keyboard.jpg
---

## Generelle Hinweise für selbst gekaufte Router

Grundsätzlich sollte mit der richtigen Konfiguration jeder im Handel erhältliche Router funktionieren.

Aufgrund der vielen verschiedenen Modelle und Aktualisierungen können wir leider keine genauen Anleitungen anbieten.
Deshalb sollte diese Seite auch eher als Leitfaden und nicht als Schritt für Schritt Anleitung gesehen werden.

## Generelle Einrichtungshinweise

Wichtig beim Einrichten des Routers ist:

* korrekten Netzwerkanschluss an der Wand auswählen (in den meisten Zimmern sind zwei, wovon in der Regel nur die Linke funktioniert) 
* richtigen Anschluss am Router für das LAN-Kabel auswählen (meistens gibt es eine speziell markierten Anschluss (genannt *WAN*) für den Internetanschluss)
* richtige Konfiguration des Routers nach der jeweiligen beiligenden Anleitung

Letzteres funktioniert ähnlich wie am Computer und die Netzdaten die du auf einem Zettel beim Einzug bekommen hast müssen verwendet werden.

Das heißt es müssen eingestellt werden:

* korrekter Betriebsmodus
* statische IP-Adresse
* Subnetzmaske
* DNS-Server
* Standard-Gateway

Folgendes ist normalerweise standardmäßig schon richtig eingestellt, aktiviert und sollte auch so bleiben:

* DHCP-Server
* Firewall
* NAT

## Herstellerspezifische Hinweise

### TP-Link

Such in der Anleitung deines Routers nach **Statische IP-Adresse** oder **Statische IP** in Zusammenhang mit der Internetkonfiguration.

Bei vielen Modellen gibt es in der **Schnellinstallation/-einrichtung** oder im Reiter **Internet** (oder **Netzwerk**) eine Option die so heißen sollte.

Anschließend kann man die benötigten Parameter eintragen.

#### Beispielschritte

Hier sind Beispielanleitungen für einige Routermodelle.
Auch wenn ein Router hier nicht gelistet ist, kann die Konfiguration trotzdem gleich oder ähnlich sein.
Am besten mal durchschauen, ob es ähnlich aussieht.

- [Archer C6]({{< ref "/support/router/tplink/tplink_c6_manual.de.md" >}})
- [Archer C2]({{< ref "/support/router/tplink/tplink_c2_manual.de.md" >}})
- [Archer C50]({{< ref "/support/router/tplink/tplink_c50_manual.de.md" >}})
- [TL-WR940N]({{< ref "/support/router/tplink/tplink_tl-wr940n_manual.de.md" >}})

### Asus

Such in der Anleitung deines Routers nach **Statische IP** oder **Feste IP** in Zusammenhang mit der Internetkonfiguration.

Bei vielen Modellen gibt es in der **Schnellinstallation/-einrichtung** oder im Reiter **WAN** (oder **Internetverbindung**) eine Option die so heißen sollte.

Anschließend kann man die benötigten Parameter eintragen.

### FRITZ!Box

#### Neuere Modelle

Such in der Anleitung oder der AVM-Wissensdatenbank nach dem Stichwort **kaskadierten Router** in Kombination mit deinem Routermodell und folge der Anleitung.

#### Ältere Modelle

Such in der Anleitung oder der AVM-Wissensdatenbank nach dem Stichwort **Betrieb mit anderem Router einrichten** in Kombination mit deinem Routermodell und folge der Anleitung.

-------------

Wähl dabei die Option **IP-Adresse manuell festlegen** und nicht **IP-Adresse automatisch über DHCP beziehen**.

Anschließend kann man die benötigten Parameter eintragen.

Unser Downstream/Upstream-Rate beträgt gerade ungefähr 100 Mbit/s (100000 kbit/s).

### Andere Routerhersteller

Hier können wir leider nur generelle Hinweise geben:

* such nach **statische IP**, **Betrieb mit anderem Router**, **Betrieb über vorhandenen Internetanschluss**, **kaskadierten Router** oder äquivalenten Begriffen in der Anleitung oder dem Internet
* wenn du nicht die vier Parameter **statische IP-Adresse**, **Subnetzmaske**, **Default Gateway** und **DNS Server** einstellen kannst, hast du wahrscheinlich den falschen Betriebsmodus ausgewählt

## Sonstige Hinweise

Zum Testen, ob die Einrichtung erfolgreich war, kannst du unser Tool [selftest.stustanet.de](http://selftest.stustanet.de) verwenden.
Mehr Informationen dazu findest du auf der [Hilfeseite Selftest]({{< ref "selftest.de.md" >}}).

Wenn man Wert auf maximale Datenrate und minimale Latenz legt kann es sinnvoll sein, einen Router mit Support für das 5 GHz WLAN-Netz (ac Standard oder neuer) zu kaufen, entsprechende Support im Handy und Computer natürlich vorausgesetzt.
Für den normalen Gebrauch ist das 2,4 GHz Netz allerdings vollkommen ausreichend.

Schreib uns gerne eine [E-Mail]({{< ref "/support/_index.de.md#mail" >}}) solltest du mehr Hilfe brauchen, hier einen Fehler finden oder falls du eine Anleitung hast, die du uns gerne zur Verfügung stellen willst.