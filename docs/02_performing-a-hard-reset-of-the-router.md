# Performing a hard reset of the router

After confirming you cannot connect to Wi-Fi on any devices that normally would connect to the router, please following the instructions below.

!!! warning
    
    By following this, you will perform a hard reset on your router and revert it to factory default settings. Even if you set the same Wi-Fi password during setup after performing this reset, you may need to manually connect your devices to the Wi-Fi network.

On your router, locate the small hole labeled **Reset**. This hole is usually on the back of the router near the connecting ports.

To hard reset the router, insert a pin into the **Reset** hole and press the button inside for 10 seconds. When all the lights on the router turn on, stop pressing the button with the pin. Wait about 30 seconds for the router to reset.

Plug in one end of the ethernet cable into your laptop. Then, plug in the other end of the cable into a numbered ethernet port on the router.

Go to the default IP address for accessing the router. 

!!! note
    
    The IP address of TP-Link Wi-Fi routers tends to be http://192.168.0.1, but if that doesn't work, also try http://192.168.1.1 or https://tplinkwifi.net.

You will be greeted with a screen stating that a firmware upgrade has failed.

!!! note
    
    This is the default message. Even if your router didn't attempt to install a firmware upgrade, the same message will still be displayed.

    ![TP-Link router error message](https://github.com/josh-wong/tplink-router-hard-reset/blob/main/docs/assets/screenshots/tp-link_router_error_message.jpg?raw=true)

Unplug the ethernet cable from the router, then plug it into the modem. This will give you wired Internet access.

As mentioned on the router error page in the previous screenshot, go to the [TP-Link download site](https://www.tp-link.com/us/support/download/). On the download site, search for your router and go to the product's firmware download page.

!!! note
    
    Make sure you go to the correct product page for the country specified on the router's label.

Download the firmware file to your computer. The firmware will be in a compressed .zip file.

Go to the folder where you downloaded the firmware .zip file to. Right-click the .zip file, and click **Extract All** (or similar wording, based on your preferred decompression software). After unzipping the file, a folder with a .bin file will be displayed.

Unplug the ethernet cable from the modem. Then, plug it into a numbered ethernet port on the router. Your computer should now be connected to the router again as in step 3.

Click **Browse**, and go to the folder where the .bin file is located. Click the .bin file, and click **OK**. Then, click **Upgrade**. Installing the firmware takes a few minutes. 

After the router completes the firmware installation, you will be prompted to enter a new password. Enter a password and confirm the same password, then click **Let's Get Started**. The router will then instruct you on configuring the settings as you normally would on initial setup.

![TP-Link router password confirmation](https://github.com/josh-wong/tplink-router-hard-reset/blob/main/docs/assets/screenshots/tp-link_router_password_confirmation.png?raw=true)

If you are still experiencing connection issues after configuring the router, be sure to check the product manual to make sure you have configured all the necessary settings.