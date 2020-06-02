---
title: General Router Configuration
header: General Router Configuration
description: Shorts hints how routers should be configured correctly in the StuSta.
type: page
color: none
headerImage: headers/keyboard.jpg
---

## General note for self-bought router

In general, every available router should be usable with the right configuration.

We unfortunately cannot provide exact instructions, due to the vast amount of models.
Therefore, this site provides more of a guideline and not step-by-step instructions.

## General configuration notes

Important notes for the router configuration:

* choose correct network plug at the wall (most rooms have two from which normally only the left one is functional)
* choose correct plug for the LAN cable at the router (most of the time there is a marked plug (called *WAN*) for the internet connection)
* choose right configuration for your router according to its instructions

The latter works similar as the configuration when using only computer and the network information on a page you got when moving has to be used.

You have to configure:

* correct mode of operation
* static IP adress
* subnet mask
* DNS server
* default gateway

The following are normally correct by the default settings, activated and should stay that way:

* DHCP server
* firewall
* NAT

## Vendor specific notes

### TP-Link

Search the manual of your router for **Static IP adress** or **Static IP** in the context of the internet configuration.

For many models, there is an option in the **Quick Install/Quick Setup** or in the **Internet** (or **Network**) tab that should be called like this.

There you can enter the required parameters.

### Asus

Search the manual of your router for **Static IP address** or **Static IP** in the context of the internet configuration.

For many models, there is an option in the **Quick Install/Setup** or in the **WAN** (or **Internet Connection**) tab that should be called like this.

There you can enter the required parameters.

### FRITZ!Box

#### Newer models

Search in the manual or AVM knowledgebase for the keyword **cascaded router** in combination with your router model and follow the instructions.

#### Older models

Search in the guide or AVM knowledgebase for the keyword **setting up for use with another router** in combination with your router model and follow the instructions.

-------------

Select the option **Configure the IP address manually** and not **Obtain the IP address automatically (DHCP)**.

Then you can enter the required parameters.

Our downstream/upstream rate is currently about 100 Mbit/s (100000 kbit/s).

### Other router manufacturers

Unfortunately, we can only give general information here:

* search for **static IP**, **operation with other router**, **operation via existing internet connection**, **cascaded router** or equivalent terms in the manual or the internet
* if you cannot set the four parameters **static IP address**, **subnet mask**, **default gateway** and **DNS server**, you probably selected the wrong operating mode

## Other notes

To test if the setup was successful, you can use our tool [selftest.stustanet.de](http://selftest.stustanet.de).
You can find more information on the [Selftest Help]({{< ref "selftest.en.md" >}}) page.

If you want maximum data rate and minimum latency, it might be useful to buy a router with support for the 5 GHz WLAN network (ac standard or newer), assuming you have the appropriate support in your phone and computer.
For normal use, the 2.4 GHz network is sufficient.

Please write us an [E-Mail]({{< ref "/support/_index.en.md#mail" >}}) if you need further help, find an error or if you have a manual that you would like to share with us.