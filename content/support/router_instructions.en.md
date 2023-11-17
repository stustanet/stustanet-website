---
title: General Router Configuration & First Aid
header: General Router Configuration & First Aid
description: Shorts hints how routers should be configured correctly in the StuSta.
type: page
color: none
headerImage: headers/keyboard.jpg
---

{{% alert %}}
On 14. October of 2013, the Max Bill House was switched from static IPs to DHCP, which resulted in the loss of internet. For information on what you need to do to re-establish the connection, see [here]({{< ref "armageddon." >}}).
{{% /alert %}}


## Which router should I buy?

In general, every available router should be usable with the right configuration.
For particularly simple setup, we also sell routers in our [office hours]({{< ref "../officehours." >}}). We also offer support for these.

We unfortunately cannot provide exact instructions, due to the vast amount of models.
Therefore, this site provides more of a guideline and not step-by-step instructions.

## General configuration notes

Important notes for the router configuration:

* If you are not a member of StuStaNet, you must first set up a proxy.
  You can find instructions for this [here for the Studentenstadt](https://dokumente.stustanet.de/netzwerkanleitung/Netzwerkanleitung.pdf) and [here for the Max Bill House](https://dokumente.stustanet.de/netzwerkanleitung/Netzwerkanleitung_mb.pdf). [Here](https://reg.stustanet.de/) you can become a member of StuStaNet and use the internet without a proxy.
* Choose correct network plug on the wall (most rooms have two, of which normally only the left one is functional)
* Select the correct port on the router for the LAN cable
  (often there is a specially marked port (called *WAN*) for the Internet connection, caution: on some routers *WAN* is a DSL port and LAN 1, for example, must be used)
* If the router supports different operating modes, connection to another router and obtaining the IP address (or something similar) must be selected;
  Operation as a modem is incorrect in any case
* Choose right configuration for your router according to its instructions

## It still doesn't work?

Carry out the following points in sequence with the router set up and a device connected to it.

If none of the described approaches solve the problem, you can write us an email.
Please write us all the information listed in our [FAQ about mail]({{< ref "_index.en.md#mail" >}}) and describe exactly what did not work on this page.

### Test 0 - StuStaNet router:

Only for StuStaNet routers:
Go to [Solution 0]({{< ref "#solution_0" >}}).

### Test 1 - Router <-> Computer connection:

Can you access your router's web interface if you are connected to the router via W-LAN or a LAN cable?

This is the page where you can set the router's settings.
It can be accessed via the web browser with the IP address of the router.

The address is often **192.168.1.1** (e.g. StuStaNet router) or also **192.168.0.1**.
The address should also be found in the router's manual.

If you cannot reach the settings, go to [Solution 1]({{< ref "#solution_1" >}}).

### Test 2 - Router <-> Internet connection:

Can you access [selftest.stustanet.de](http://selftest.stustanet.de)?
Possible error codes on the page are described on the [Selftest Help]({{< ref "selftest.en.md" >}}) page.

If the **_Error 1_** listed there occurs, your router is probably not set up correctly.
In this case go to [solution 2]({{< ref "#solution_2" >}})

### Solution 0 - StuStaNet router: {#solution_0}

We have given the StuStaNet routers a number to help distinguish them from each other.

You can find the number on the package, the StuStaNet router manual or on the bottom of the router.
It has four digits and should begin with a **_#_**.

#### Stustanet router LED codes for number #6000 or higher:

StuStaNet routers of number *6000* and newer have an LED code from which you can usually narrow down the error.

**permanent orange light:**

There is no connection to the network.
Check that the router is connected to the correct network port on the wall and that the cable is also plugged into the correct port on the router.

**orange blinking:**

After pressing the WPS button for more than five seconds, the router runs its setup script.
This may take some time.
After that the LED should blink blue irregularly.

**Irregular blue flashing:**

The router has been configured and everything should work at least on the router side.
If there are still problems, it is probably either because of the connection between router and computer or because of a virus lock.
For the latter, run [selftest.stustanet.de](http://selftest.stustanet.de)

**permanent blue-orange irregularly alternating (also slightly purple) light:**

Your router is not or not correctly configured and cannot connect to the Internet.
Carry out the configuration again according to the StuStaNet instructions supplied with the router and make sure that the router flashes orange after you have pressed the *WPS button for more than five seconds* as described above.

If repeating the instructions does not help, you can try resetting the router to its factory default settings.

#### StuStaNet router reset for number #6000 or higher:

If you press the reset button (notch that can only be reached with a pointed object; not the WPS button) for more than 10 seconds, you will trigger the reset to our factory settings.

The router's LED should turn off briefly, then turn orange, followed by orange flashing until the reset is complete.

You can then try again to carry out the enclosed instructions with the StuStaNet logo.

#### StuStaNet router configuration for number #5000 - #5999

The configuration script is triggered by pressing the reset button with a pointed object (pen) for several seconds.

#### StuStaNet router configuration for number smaller #5000

We configure the other routers as described in their StuStaNet instructions using the WPS button.

### Solution 1 - Router <-> Computer connection: {#solution_1}

Find out which IP address your PC uses to connect to the router.

For Windows, search for **cmd** in the Windows search and open the program.

{{< figure src="/support/routerproblem/searchcmd.png" height="400" >}}

At the command prompt, type **ipconfig** and press Enter.

Relevant for you is the default gateway in order to find out the IP address of the router.

{{< figure src="/support/routerproblem/ipconfigcmd.png" height="300" >}}

With the address of the **default gateway**, in the case **192.168.0.1**, you can usually reach the router's configuration page in the browser.

For other operating systems it should be similarly possible.
It is best to search for **default gateway** in combination with your operating system in the search engine of your choice.

If the IP address you have found out is very different from 192.168.**X**.**X** (e.g. 10.**X**.**X**.**X**.**X**), then you have probably set a static IP on your computer and need to change it back to automatic reference.

### Solution 2 - Router <-> Internet connection: {#solution_2}

In this case check and repeat the installation and

* *For StuStaNet routers*: follow the enclosed instructions with StuStaNet logo
* *For normal routers*: note the items on the [General Router Setup]({{< ref "router_instructions.en.md" >}}) page

The other errors with possible solutions are described in more detail on the [Selftest Help]({{< ref "selftest.en.md" >}}) page.
Follow the instructions there and follow the links in the *selftest* error message.

## Other notes

To test if the setup was successful, you can use our tool [selftest.stustanet.de](http://selftest.stustanet.de).
You can find more information on the [Selftest Help]({{< ref "selftest.en.md" >}}) page.

If you want maximum data rate and minimum latency, it might be useful to buy a router with support for the 5 GHz WLAN network (ac standard or newer), assuming you have the appropriate support in your phone and computer.
For normal use, the 2.4 GHz network is sufficient.

Please write us an [E-Mail]({{< ref "/support/_index.en.md#mail" >}}) if you need further help, find an error or if you have a manual that you would like to share with us.
