---
title: Selftest Help
header: Selftest Help
description: Short description of selftest and possible error messages
type: page
color: none
headerImage: headers/keyboard.jpg
---

The page [selftest.stustanet.de](http://selftest.stustanet.de) performs several checks to detect common network problems.

**It is very important to access this page via your StuStaNet internet connection and not via your smartphone.**

The checks are performed automatically when you visit the site and ideally they are all positive.

{{< figure src="/support/selftest/selftestok.png" height="250" >}}

If you have problems with the site or if you are unsure what to do with the resulting message, please have a look at the following potential errors.

***

## Error 1: Page not accessible

{{< figure src="/support/selftest/nointernetchrome.png" height="150" >}}

oder

{{< figure src="/support/selftest/nointernetfirefox.png" height="150" >}}

There is probably a problem with your router configuration or your PC configuration.
For instructions on how to configure routers you can find more information on the the page [Router Instructions]({{< ref "router_instructions.en.md" >}}).

If you are not able to solve this yourself, please contact the network admins. Just follow the instructions on the link at the end of the page.

***

## Error 2: External IP

{{< figure src="/support/selftest/selftestextern.png" height="300" >}}

Make sure you access the page from the network port in your room and not your smartphone.

Please temporarily disable VPNs and proxies.

***

## Error 3: Virus Blocked

{{< figure src="/support/selftest/selftestvirus.png" height="70" >}}

You've been virus-blocked. This can have several reasons. For the reasons why we have to block, if we suspect there might be a virus infection, take a look at the [FAQ]({{< ref "/support/_index.en.md#faq" >}}).

Please follow the link shown in the error message and follow the steps shown to get unblocked.

***

## Error 4: Not a Member

{{< figure src="/support/selftest/selftestnomember.png" height="70" >}}

In order to access the Internet from your room, you must either use a proxy provided by us or become a member.

At the moment you don't seem to have either of them.

To set up the proxy correctly, please follow the link in the error message.

You can find out about the advantages of a membership [in the Wiki](https://wiki.stusta.de/StuStaNet-Services). Probably the most important advantage for you is that no proxy setup is necessary anymore.

## Other Problems:

{{< figure src="/support/selftest/selftestblock.png" height="250" >}}

If you use a *data saver*, *mobile booser* or similar extension or function, that redirects the Internet traffic to another server, then please turn it off for the test.

Please send us the log of [selftest.stustanet.de](http://selftest.stustanet.de). For that have a look at the section [support mail]({{< ref "/support/_index.en.md#mail" >}}).
