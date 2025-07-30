# 🔌 Home Automation using IoT and Telegram App (ESP8266 + Arduino)

Control your home appliances using a Telegram bot and ESP8266! This project allows remote switching of devices like lights and fans through Telegram with secure access via chat ID filtering.

## 📁 Code File

- `code/home_automation_telegram.ino`

## ⚙️ Features

- Control appliances via Telegram bot
- Status update for each device
- Only authorized chat IDs can use the bot

## 📷 Screenshots

You can add screenshots in the `screenshots/` folder.

## 🧰 Components Used

- ESP8266 (NodeMCU)
- Relay Module
- Arduino IDE
- Telegram App
- WiFi Connection

## 📝 Setup Steps

1. Replace your bot token, WiFi SSID, and password in the `.ino` file
2. Upload the code to ESP8266
3. Start the bot on Telegram and send `/start` and `/switch` commands

## 📚 References

- [Universal Arduino Telegram Bot](https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot)
- [ESP8266 Arduino Core](https://github.com/esp8266/Arduino)