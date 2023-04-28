---
title: Konfiguration des Routers
header: Wie man den router auf DHCP umstellt
description: Wie konfiguriert man die Router jetzt in der StuSta
type: page
color: none
headerImage: headers/keyboard.jpg
---

Falls [das zurück setzen deines Routers]({{< ref "armageddon" >}}) die Internet Verbindung nicht wieder hergestellt hat, führe diese Schritte aus, um den Router auf DHCP zu ändern:
1. Finde die IP Addresse deines Routers. Diese ist üblicherweise [http://192.168.1.1](http://192.168.1.1) oder [http://192.168.0.1](http://192.168.0.1)
2. Nutze einen Browser um die Website des Routers zu besuchen und logge dich mit den Daten von der Rückseite des Routers ein.
3. In den Netzwerkeinstellungen ändere das WAN *protokoll* bzw die *IPv4 Einstellungen* von *statisch* auf *DHCP*

### Ändern der IP Addresse:
Navigiere zu den WAN-Einstellungen unter *Netzwerk*, *Interfaces* und ändere die IP Zuweisungsmethode auf *DHCP*. Nach dem Speichern sollte das Internet wie gewohnt funktionieren.

Hier die konkreten Schritte für den StuStaNet Router:
1. Gehe zu *Network* -> *Interfaces*
2. Editiere das WAN Interface
3. Wähle als Protkoll *DHCP*
4. *Save and apply*

{{< figure src="/support/routerproblem/newips_network_settings.png" width="600" >}}
{{< figure src="/support/routerproblem/newips_interface_settings.png" width="600" >}}

