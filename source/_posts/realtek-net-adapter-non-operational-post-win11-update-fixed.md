---
title: Realtek Net Adapter Non-Operational Post Win11 Update (Fixed)
date: 2025-01-03T08:24:17.967Z
updated: 2025-01-09T19:00:15.497Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Realtek Net Adapter Non-Operational Post Win11 Update (Fixed)
excerpt: This Article Describes Realtek Net Adapter Non-Operational Post Win11 Update (Fixed)
thumbnail: https://thmb.techidaily.com/3d2f504c7a28917e2aef95be2fd0b9c5130c134ee668702387fa9476707bc049.jpg
---

## Realtek Net Adapter Non-Operational Post Win11 Update (Fixed)

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

 Hopefully the tips above help you fix the Realtek Ethernet Controller driver not working issue. If you have any questions or ideas, feel free to leave your comments below, please.

* [Realtek](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-dissecting-ajey-nagars-2023-youtube-economic-landscape/"><u>[New] Dissecting Ajey Nagar's 2023 YouTube Economic Landscape</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-conquering-competition-crafting-standout-youtube-advertising-banners-for-2024/"><u>[Updated] Conquering Competition Crafting Standout YouTube Advertising Banners for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-live-on-air-how-to-broadcast-on-youtube-and-twitch-using-obs/"><u>[Updated] In 2024, Live on Air How to Broadcast on YouTube & Twitch Using OBS</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-detailed-pokemon-go-pvp-tier-list-to-make-you-a-pro-trainer-for-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>A Detailed Pokemon Go PvP Tier List to Make you a Pro Trainer For Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/bring-your-work-inside-out-accessing-ms-office-tools-via-quest-vr-devices-word-presentations-and-spreadsheets/"><u>Bring Your Work Inside-Out: Accessing MS Office Tools via Quest VR Devices - Word, Presentations, and Spreadsheets!</u></a></li>
<li><a href="https://games-able.techidaily.com/easing-device-freeze-unraveling-the-0x887a0006-problems/"><u>Easing Device Freeze - Unraveling the 0X887A0006 Problems</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>How Can I Catch the Regional Pokémon without Traveling On Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-enter-the-ispoofer-discord-server-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>How to enter the iSpoofer discord server On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/is-mega-mewtwo-the-strongest-pokemon-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>Is Mega Mewtwo The Strongest Pokémon On Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/most-asked-questions-about-pokemon-go-battle-league-rewards-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Most Asked Questions about Pokemon Go Battle League Rewards On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/reducing-auditory-intensity-with-careful-adjustments-in-logic-pro/"><u>Reducing Auditory Intensity with Careful Adjustments in Logic Pro</u></a></li>
<li><a href="https://fox-useful.techidaily.com/setup-environment-variables-via-edit-window-in-installation-package/"><u>Setup Environment Variables via Edit Window in Installation Package</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-leveraging-preview-capabilities-on-a-mac/"><u>The Ultimate Guide to Leveraging Preview Capabilities on a Mac</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-productivity-apps-for-ipad-streamline-your-task-management-and-boost-efficiency-insights/"><u>Top Productivity Apps for iPad: Streamline Your Task Management & Boost Efficiency - Insights</u></a></li>
</ul></div>

