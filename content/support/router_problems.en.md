---
title: Router Problems First Aid
header: Router Problems First Aid
description: Problems and solutions for routers.
type: page
color: none
headerImage: headers/keyboard.jpg
---

First make sure that the following tasks have been carried out:

* choose correct network plug at the wall (most rooms have two from which normally only the left one is functional)
* choose correct plug for the LAN cable at the router (most of the time there is a marked plug (called *WAN*) for the internet connection)
* choose right configuration for your router according to its instructions

and if you do not have a StuStaNet router, that you have read the [General Router Configuration]({{< ref "router_instructions.en.md" >}}) page.

Carry out the following steps in order while the router is configured and a device is connected to it.

If none of the described approaches solved the problem, you can send us a mail.
Please write us all the information listed in our [FAQ for the mail]({{< ref "_index.en.md#mail" >}}) and describe accurately what failed on this site.

## Test 0 - StuStaNet router:

Only for StuStaNet routers:
Go to [Solution 0]({{< ref "#solution_0" >}}).

## Test 1 - Router <-> Computer connection:

Can you access your router's web interface if you are connected to the router via W-LAN or a LAN cable?

This is the page where you can set the router's settings.
It can be accessed via the web browser with the IP address of the router.

The address is often **192.168.1.1** (e.g. StuStaNet router) or also **192.168.0.1**.
The address should also be found in the router's manual.

If you cannot reach the settings, go to [Solution 1]({{< ref "#solution_1" >}}).

## Test 2 - Router <-> Internet connection:

Can you access [selftest.stustanet.de](http://selftest.stustanet.de)?
Possible error codes on the page are described on the [Selftest Help]({{< ref "selftest.en.md" >}}) page.

If the **_error 1_** listed there occurs, your router is probably not set up correctly.
In this case go to [solution 2]({{< ref "#solution_2" >}})

## Solution 0 - StuStaNet router: {#solution_0}

We have given the StuStaNet routers a number to help distinguish them from each other.

You can find the number on the package, the StuStaNet router manual or on the bottom of the router.
It has four digits and should begin with a **_#_**.

### Stustanet router LED codes for number #6000 or higher:

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

### StuStaNet router reset for number #6000 or higher:

If you press the reset button (notch that can only be reached with a pointed object; not the WPS button) for more than 10 seconds, you will trigger the reset to our factory settings.

The router's LED should turn off briefly, then turn orange, followed by orange flashing until the reset is complete.

You can then try again to carry out the enclosed instructions with the StuStaNet logo.

### StuStaNet router configuration for number #5000 - #5999

The configuration script is triggered by pressing the reset button with a pointed object (pen) for several seconds.

### StuStaNet router configuration for number smaller #5000

We configure the other routers as described in their StuStaNet instructions using the WPS button.

## Solution 1 - Router <-> Computer connection: {#solution_1}

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

## Solution 2 - Router <-> Internet connection: {#solution_2}

In this case check and repeat the installation and

* *For StuStaNet routers*: follow the enclosed instructions with StuStaNet logo
* *For normal routers*: note the items on the [General Router Setup]({{< ref "router_instructions.en.md" >}}) page

The other errors with possible solutions are described in more detail on the [Selftest Help]({{< ref "selftest.en.md" >}}) page.
Follow the instructions there and follow the links in the *selftest* error message.