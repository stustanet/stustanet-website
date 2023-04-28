---
title: Configuring the router
header: How to configure the router
description: Shorts hints how routers should be configured correctly in the StuSta.
type: page
color: none
headerImage: headers/keyboard.jpg
---

If [factory resetting your router]({{< ref "armageddon" >}}) did not restore your connection, try these steps to change the network management protocol to DHCP in your router's settings:
1. Find your router’s IP address.
2. Go to the IP address of your router using an internet browser and log in using credentials printed on the StuStaNet sticker or directly on the router.
3. In general network settings change the WAN “protocol” or “IPv4 assignment method” from “Static” to “Automatic”, “Dynamic” or “DHCP”.

### Finding your router's IP address:
Most probably, the address you need will be one of the default router IP addresses like **192.168.1.1** or **192.168.0.1**. After opening the address in your browser you should be able to log in using the credentials written on your router or its StuStaNet sticker.

If these addresses do not work, you can find the correct one in the network settings of your device:
* [WINDOWS](https://www.howtogeek.com/233952/how-to-find-your-routers-ip-address-on-any-computer-smartphone-or-tablet/#autotoc_anchor_0)
* [LINUX](https://www.howtogeek.com/233952/how-to-find-your-routers-ip-address-on-any-computer-smartphone-or-tablet/#autotoc_anchor_5)
* [MACOS](https://www.howtogeek.com/233952/how-to-find-your-routers-ip-address-on-any-computer-smartphone-or-tablet/#autotoc_anchor_1)


### Changing the IP assignment method:
This step depends greatly on the router's model. You need to navigate to WAN settings (can be under "Network" or "Interfaces") and change the IP assignment method (can be called "Protocol" or "Connection type") to DHCP ("Dynamic" or "Automatic"). After saving the settings the internet connection should be back.

Here are the option for the current StuStaNet Router:
1. navigate to *Network* -> *Interfaces*
2. Edit the Wan interface
3. Select Protocol *DHCP*
4. Save and apply everything

{{< figure src="/support/routerproblem/newips_network_settings.png" width="600" >}}
{{< figure src="/support/routerproblem/newips_interface_settings.png" width="600" >}}


If you still do not have access to the Internet, you can use the self-test tool [(selftest.stusta.de)](http://selftest.stustanet.de) to diagnose the problem yourself.
More information on general router troubleshooting can be found [here](https://stustanet.de/en/support).
You can also contact your house's internet admin [(here's the list)](https://dokumente.stustanet.de/adminliste/adminliste.pdf) or send an email to admins@stustanet.de.



