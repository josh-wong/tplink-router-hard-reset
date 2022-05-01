# Performing a hard reset of the router

After confirming you cannot connect to Wi-Fi on any devices that normally would connect to the router, please following the instructions below.

> **Attention!:** By following this, you will perform a hard reset on your router and revert it to factory default settings. Even if you set the same Wi-Fi password during setup after performing this reset, you may need to manually connect your devices to the Wi-Fi network.

1. On your router, locate the small hole labeled **Reset**. This hole is usually on the back of the router near the connecting ports.

2. To hard reset the router, insert a pin into the **Reset** hole and press the button inside for 10 seconds. When all the lights on the router turn on, stop pressing the button with the pin. Wait about 30 seconds for the router to reset.

3. Plug in one end of the ethernet cable into your laptop. Then, plug in the other end of the cable into a numbered ethernet port on the router.

4. Go to the default IP address for accessing the router. 

    > **Note:** The IP address of TP-Link Wi-Fi routers tends to be http://192.168.0.1, but if that doesn't work, also try http://192.168.1.1 or https://tplinkwifi.net.

    You will be greeted with a screen stating that a firmware upgrade has failed.

    > **Note:** This is the default message. Even if your router didn't attempt to install a firmware upgrade, the same message will still be displayed.

    ![TP-Link router error message](https://github.com/josh-wong/tplink-router-hard-reset/blob/main/docs/assets/screenshots/tp-link_router_error_message.jpg?raw=true)

5. Unplug the ethernet cable from the router, then plug it into the modem. This will give you wired Internet access.

6. As mentioned on the router error page in the previous screenshot, go to [https://www.tp-link.com/us/support/download/](https://www.tp-link.com/us/support/download/).

7. On the TP-Link download site, search for your router and go to the product's firmware download page.

    > **Note:** Make sure you go to the correct product page for the country specified on the router's label.

8. Download the firmware file to your computer. The firmware will be in a compressed .zip file.

9. Go to the folder where you downloaded the firmware .zip file to.

10. Right-click the .zip file, and click **Extract All** (or similar wording, based on your preferred decompression software). After unzipping the file, a folder with a .bin file will be displayed.

11. Unplug the ethernet cable from the modem. Then, plug it into a numbered ethernet port on the router. Your computer should now be connected to the router again as in step 3.

12. Click **Browse**, and go to the folder where the .bin file is located. 

13. Click the .bin file, and click **OK**.

14. Click **Upgrade**. Installing the firmware takes a few minutes. 

15. After the router completes the firmware installation, you will be prompted to enter a new password. Enter a password and confirm the same password, then click **Let's Get Started**. The router will then instruct you on configuring the settings as you normally would on initial setup.

    ![TP-Link router password confirmation](https://github.com/josh-wong/tplink-router-hard-reset/blob/main/docs/assets/screenshots/tp-link_router_password_confirmation.png?raw=true)

If you are still experiencing connection issues after configuring the router, be sure to check the product manual to make sure you have configured all the necessary settings.