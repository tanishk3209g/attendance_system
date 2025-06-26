# 📋 RFID Attendance System with Google Sheets Logging

This project is a **smart RFID-based attendance system** that allows users to scan RFID cards for marking attendance. The data is **automatically logged to a Google Sheet in real time** using a Wi-Fi-enabled microcontroller.

## 🚀 Features

- ✅ Scan RFID cards to mark attendance
- 📤 Sends attendance data directly to **Google Sheets**
- 🕒 Real-time timestamp logging
- 💾 Records name, date, and time
- 📶 Works over Wi-Fi (Node MCU/ESP8266/ESP32)
- 🖥️ Serial Monitor support for debugging
- 🧾 Duplicate scan prevention within a session
- 

---

## 📽️ Demo

Demo available on Youtube
https://youtu.be/ZLKsQ3MEE7Y
---

## 🛠️ Tech Stack

- **Microcontroller**: ESP8266 / NodeMCU / ESP32
- **RFID Module**: RC522
- **Platform**: Arduino IDE
- **Database**: Google Sheets via Google Apps Script
- **Connectivity**: Wi-Fi

---

---

## 🔌 Circuit Diagram

- **RFID RC522** connected to ESP8266:
  - SDA → D2
  - SCK → D5
  - MOSI → D7
  - MISO → D6
  - RST → D1
  - GND → GND
  - 3.3V → 3.3V

---

## 🧠 How It Works

1. A user taps their RFID card/tag on the scanner.
2. The ESP8266 reads the **UID** from the card.
3. A POST request is made to a **Google Apps Script Web App**.
4. The script logs the UID, name, date, and time in a Google Sheet.

---


## 🎯 Use Cases

- Schools and Colleges
- Offices and Startups
- Event Check-ins
- Lab Access Control

---

## 📚 Future Improvements

- Buzzer when entry
- Add LCD display for name confirmation
- Admin dashboard for analytics
- Email/SMS alerts for attendance
- Google Sheet formatting (auto sort, color code)

---

## 📜 License

This project is open-source and free to use under the MIT License.

---

## 🙌 Credits

Made with ❤️ by Tanishk


