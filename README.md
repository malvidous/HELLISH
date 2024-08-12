# HELLISH Deauther ESP8266-(WEMOS d1 Mini)

## Features
1. **Deauthing**: Send deauthentication packets to disconnect network and client.
2. **Evil Twin**: Create a fake access point to mimic another network, Useful for capturing credentials or redirecting traffic.
3. **Deauth All**: Send deauthentication packets to all network and clients in coverage area.
4. **Aggressive Deauth**: More aggressive deauthentication attacks, ensures clients are disconnected and stay disconnected for longer periods.
5. **Beacon Flooding**: Send multiple beacon frames to create fake networks, confuses users by displaying many fake networks in their WiFi list.
6. **Network Extender**: Extends the range of an existing network by creating a secondary access point for improving WiFi coverage.
7. **OTA Updates**: Over-the-Air firmware updates.
8. **File Management**: Upload, view, and delete files from SPIFFS.
9. **Password Logging**: Log and manage passwords, stores and displays passwords entered by clients.
10. **LED Control**: Control the onboard LED.
11. **Web Server**: Serve web pages to control and configure the device, provides a user interface for managing device settings and initiating attacks.
12. **DNS Server**: Redirects clients to a specific web page, useful for captive portals or phishing pages.

### How to get Registered Board
1. Chat me on [Whatsapp](https://wa.me/6287818131314) 💬💬
2. Download [check-id_hellish.bin](https://github.com/malvidous/HELLISH/releases/download/v1.8.1/check-id_hellish.bin) 📁📁
3. or alternate easy way is send me your device(s) MAC Address
4. Flash it to your board and Send me the ID 🃏🃏
5. Done the Payment. 💸💸
6. Wait for me to update the database and Releases 🐬🐬 ≈ 2mins
7. Download the latest [Releases](https://github.com/malvidous/HELLISH/releases) 📁📁
8. Flash it! ⚡️⚡️
9. pwned!

***

## How to Check the ID of Your Board
1. **Download and Flash the Firmware**:
   - Download the firmware file: [check-id_hellish.bin](https://github.com/malvidous/HELLISH/releases/download/v1.8.1/check-id_hellish.bin).
   - Flash this firmware onto your board.

2. **Connect the Board to Power**:
   - Power up your board.
   - It should create a new Access Point (AP) with the name `ESP8266-xxxxx` where `xxxxx` is the ID board.
   
      ![ID_BOARD](https://raw.githubusercontent.com/malvidous/HELLISH/main/id_check.jpeg)
      
3. **Capture a Screenshot**:
   - Once the AP is visible, take a screenshot.

4. **Send the Screenshot**:
   - Send the screenshot to me.

5. **I'll do the rest.**


### Flashing via Smartphone
1. **Install Flashing App:**
	- For ESP8266/ESP32: Install the [ESP8266/ESP32 Flasher](https://play.google.com/store/apps/details?id=com.espressif.esp32_ota) app from the Google Play Store.
	- For Arduino: Install the [ArduinoDroid](https://play.google.com/store/apps/details?id=name.antonsmirnov.android.arduinodroid2) app.
	
2. **Connect Board:**
	- Use an OTG adapter to connect your board to the smartphone.
	
3. **Flash the Bin File:**
	- Open the flashing app and follow the instructions to select and upload the `.bin` file to your board.
	
### Flashing via Computer
1. **Install Flashing Software:**
	- For ESP8266/ESP32: Download the [ESP Flash Download Tool](https://www.espressif.com/en/support/download/other-tools).
	- For Arduino: Install the [Arduino IDE](https://www.arduino.cc/en/software).
	
2. **Connect Board:**
	- Connect your board to the computer using a USB cable.
	
3. **Flash the Bin File:**
	- For ESP8266/ESP32: Open the ESP Flash Download Tool, select the correct COM port, browse to your `.bin` file, and click the "Start" button.
	- For Arduino: Open the Arduino IDE, go to `File > Preferences` to set the location of the `.bin` file, select the correct board and port, and click `Sketch > Upload`.
	
### Flashing via Browser
1. **Install Web Serial API Compatible Browser:**
	- Use a browser that supports the Web Serial API, such as Chrome or Edge.
	
2. **Use Web-based Flasher:**
	- Visit a web-based flashing tool such as [ESP Web Tools](https://esp.huhn.me/) by SpaceHuhn.
	
3. **Connect Board:**
	- Connect your board to the computer using a USB cable.
	
4. **Flash the Bin File:**
	- Follow the instructions on the web-based tool to upload your `.bin` file. This typically involves clicking a "Connect" button, selecting the appropriate COM port, and uploading the `.bin` file.
	
	
	
	
	
	***
	Credit to :
	
	[https://github.com/M1z23R/ESP8266-EvilTwin](https://github.com/M1z23R/ESP8266-EvilTwin)

	[https://github.com/SpacehuhnTech/esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther
	)
	***
