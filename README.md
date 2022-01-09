# How to perform a hard reset of a TP-Link Wi-Fi router
This tutorial describes how to perform a hard reset on a TP-Link Wi-Fi router. 

Since performing a hard reset on a router may have serious negative effects on your network environment, these instructions should be considered only after you've exhausted other troubleshooting methods. 

Some reasons for needing a hard reset include:
- Forgotten password
- Failed firmware upgrade
- Inability to access the administrator panel of the router

## Prerequisites
- Desktop or laptop PC with an ethernet port (or USB-to-ethernet adapter)
- Ethernet cable
- Modem
- Router
- Small pin

## Preparation
Before following the instructions below, confirm that you do not have Wi-Fi connection on multiple devices. 
- If only one device doesn't cannot connect to Wi-Fi, the problem may be based on the device instead of the router.
- If none of your devices can connect to Wi-Fi, the problem is likely with the router. In this case, please proceed with the following if you have exhausted all other troubleshooting methods.

## How to reset your TP-Link router
After confirming you cannot connect to Wi-Fi on any devices that normally would connect to the router, please following the instructions below.

> **Attention!:** Following the steps below will perform a hard reset your router to factory default settings. Even if you set the same Wi-Fi password during setup, you may need to manually connect your devices to Wi-Fi.

1. On your router, locate the small hole labeled **Reset**. This hole is usually on the back of the router near the connecting ports.

2. To hard reset the router, insert a pin into the **Reset** hole and press the button inside for 10 seconds. When all the lights on the router turn on, stop pressing the button with the pin. Wait about 30 seconds for the router to reset.
3. Plug in one end of the ethernet cable into your laptop. Then, plug in the other end of the cable into a numbered ethernet port on the router.
4. Go to the default IP address for accessing the router. 

> **Note:** The IP address of TP-Link Wi-Fi routers tends to be http://192.168.0.1, but if that doesn't work, also try http://192.168.1.1 or https://tplinkwifi.net.

You will be greeted with a screen stating that a firmware upgrade has failed.

> **Note:** This is the default message. Even if your router didn't attempt to install a firmware upgrade, the same message will still be displayed.

<img src="https://github.com/josh-wong/tplink-router-hard-reset/blob/main/images/tp-link_router_error_message.jpg?raw=true" style="zoom:50%;" />

5. Unplug the ethernet cable from the router, then plug it into the modem. This will give you wired Internet access.
6. As mentioned on the router error page in the previous screenshot, go to https://www.tp-link.com/us/support/download/.
7. On the TP-Link download site, search for your router and go to the product's firmware download page.

> **Note:** Make sure you go to the correct product page for the country specified on the router's label.

7. Download the firmware file to your computer. The firmware will be in a compressed .zip file.
6. Go to the folder where you downloaded the firmware .zip file to.
7. Right-click the .zip file, and click **Extract All** (or similar wording, based on your preferred decompression software). After unzipping the file, a folder with a .bin file will be displayed.
8. Unplug the ethernet cable from the modem. Then, plug it into a numbered ethernet port on the router. Your computer should now be connected to the router again as in step 3.
9. Click **Browse**, and go to the folder where the .bin file is located.
10. Click the .bin file, and click **OK**.
11. Click **Upgrade**. Installing the firmware takes a few minutes. 
12. After the router completes the firmware installation, you will be prompted to enter a new password. Enter a password and confirm the same password, then click **Let's Get Started**. The router will then instruct you on configuring the settings as you normally would on initial setup.

<img src="https://github.com/josh-wong/tplink-router-hard-reset/blob/main/images/tp-link_router_password_confirmation.png?raw=true" style="zoom:50%;" />

If you are still experiencing connection issues after configuring the router, be sure to check the product manual to make sure you have configured all the necessary settings.

## Conclusion
As mentioned at the beginning of this tutorial, performing a hard reset on a router is not ideal. However, doing so may be the most efficient solution depending on your network environment.

# Support
Did you find this documentation helpful? Let me know!💬

Donations are greatly appreciated as well🙏

- Bitcoin Cash (BCH)🟢
<img src="https://github.com/josh-wong/tplink-router-hard-reset/blob/main/images/bitcoin_cash_qr_code_github_tp-link_router_hard_reset_tutorial.png?raw=true" style="zoom: 10%;" width="18%" height="18%" />

- Ko-Fi☕ [josh_haha](https://ko-fi.com/josh_haha)
- PayPal.me💰 [@tokyojosh](https://paypal.me/tokyojosh?country.x=JP&locale.x=en_US)
