# m5stack-cryptoticker - ༼ つ ◕_◕ ༽つ

This is a basic Arduino code for a M5Stack device.
It will display the BTC/ETH price in real-time on your screen⠀(*and also, the 24h price variation in the v2*)⠀


![test](https://github.com/frittna/Crypto_Coin_Ticker/assets/128156494/75fa61b8-2a4e-4ec6-8d28-a671bd996e5e)
⠀⠀⠀⠀⠀⠀⠀

**Prerequisites :**

Before running the program, make sure you have the following:

- M5Stack device
- Arduino IDE
- M5Stack library
- WiFi library
- HTTPClient library
- ArduinoJson library

**Installation :**

- Connect your M5Stack to your computer
- Open the Arduino IDE
- Install the required libraries: M5Stack, WiFi, HTTPClient, ArduinoJson
- Copy the code
- Set the correct values for your WiFi network (SSID + Password)
- Upload it

**Usage :**

- Power on your M5Stack device
- The device will attempt to connect to the specified Wi-Fi network. The connection status will be displayed on the serial monitor
- It will retrieve the prices of Bitcoin and Ethereum from the CoinGecko API
- The prices will be updated every 10 seconds (v1) 30 seconds (v2)
