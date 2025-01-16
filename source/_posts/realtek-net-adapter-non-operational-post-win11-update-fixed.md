---
title: Realtek Net Adapter Non-Operational Post Win11 Update (Fixed)
date: 2025-01-11T20:51:47.804Z
updated: 2025-01-16T02:46:42.564Z
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

### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-unleash-the-power-of-zoom-your-win10-journey-begins-here/"><u>[New] 2024 Approved Unleash the Power of Zoom Your Win10 Journey Begins Here</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-from-joiner-writhe-step-by-step-strategy-for-achieving-partner-status-for-2024/"><u>[New] From Joiner' Writhe Step-by-Step Strategy for Achieving Partner Status for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-game-on-selecting-the-finest-displays-for-your-xbox-series-x-console/"><u>[New] Game On Selecting the Finest Displays for Your Xbox Series X Console</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-technical-treasure-trove-mastering-the-art-of-capturing-roblox-adventures-on-apple-devices-for-2024/"><u>[New] Technical Treasure Trove Mastering the Art of Capturing Roblox Adventures on Apple Devices for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-comprehensive-guide-to-mastering-ipogo-for-pokemon-go-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>A Comprehensive Guide to Mastering iPogo for Pokémon GO On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-for-windows-11-update-error-understanding-and-solving-0x80240034/"><u>Master the Fix for Windows 11 Update Error: Understanding and Solving 0X80240034</u></a></li>
<li><a href="https://extra-hints.techidaily.com/precision-polishing-insights-from-vlle-on-apps/"><u>Precision Polishing Insights From VLLE on Apps</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unboxing-and-evaluating-the-samsung-galaxy-s21-ultra-a-leader-in-android-devices/"><u>Unboxing and Evaluating the Samsung Galaxy S21 Ultra – A Leader in Android Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-drone-racings-secrets-and-surpassing-fpv-drones/"><u>Unveiling Drone Racing's Secrets & Surpassing FPV Drones</u></a></li>
</ul></div>

