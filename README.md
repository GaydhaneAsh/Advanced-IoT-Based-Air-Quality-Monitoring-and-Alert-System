# Advanced-IoT-Based-Air-Quality-Monitoring-and-Alert-System
An Arduino UNO-based system using the MQ135 sensor to detect harmful gases. Alerts are given via LED and buzzer, with real-time data shown on an LCD and sent to a mobile app via Bluetooth for health-related air quality monitoring.
“MQ135-Based Air Quality Monitoring and Alert System”
A simple Arduino project to monitor air pollution levels using the MQ135 gas sensor. The system displays real-time air quality (in PPM) on an LCD and triggers visual and audio alerts when pollution exceeds safe limits. Ideal for home or classroom or office environments to raise awareness about indoor air quality.

Description:
This project is an Arduino-based air quality monitoring system using the MQ135 gas sensor. It continuously measures the concentration of gases like ammonia (NH₃), nitrogen oxides (NOx), benzene, CO₂, and smoke in the surrounding air. The analog output from the MQ135 is read by the Arduino and converted into PPM (parts per million) values. These values are displayed on a 16x2 LCD, and an LED & buzzer alert is triggered if the air quality crosses a predefined threshold.
The system is useful for:
- Monitoring indoor air pollution
- Creating awareness in homes, schools, or labs
- Learning about sensors, Arduino, and environmental electronics
Before accurate readings can be taken, the MQ135 sensor must be preheated for at least 24–48 hours.

Dependencies:
Before running the project, make sure you have the following:
 Operating System: Windows 10 / 11, macOS, or Linux
 Arduino IDE: Version 1.8.10 or later (or Arduino Web Editor)
 Libraries Required:
  - `LiquidCrystal_I2C` (for 16x2 LCD with I2C)
  - `Wire.h` (built-in)
To install `LiquidCrystal_I2C`:
1. Open Arduino IDE
2. Go to **Sketch > Include Library > Manage Libraries**
3. Search for `LiquidCrystal I2C` and install it

Installing:-
https://github.com/GaydhaneAsh/Advanced-IoT-Based-Air-Quality-Monitoring-and-Alert-System/tree/main)
 
Executing Program:
Follow these steps to run the project on your Arduino:
1. Connect the Hardware
- Plug the MQ135 sensor, LCD,buzzer, and LEDand Bluetooth module( HC-05) into the Arduino according to the circuit diagram.
- Ensure proper 5V power supply (USB, charger, or battery pack).

2. Open the Code
- Launch Arduino IDE.
- Source code : https://github.com/GaydhaneAsh/Advanced-IoT-Based-Air-Quality-Monitoring-and-Alert-System/blob/main/CODE 

3.Select Board and Port
Tools > Board > Arduino Uno
Tools > Port > [Select the correct COM port]

4. Upload the Code
●	Temporarily disconnect the Bluetooth module before uploading.
●	Click ✅ Verify, then 🔼 Upload:
5. Reconnect Bluetooth & Monitor Output
●	After upload, reconnect Bluetooth to D0/D1.
●	Pair with your phone (Default PIN: 1234 or 0000)

Use any Bluetooth terminal app (like Serial Bluetooth Terminal or MIT App Inventor) to receive:
1)PPM values
2)Air quality status (e.g., “AQI Poor”, “AQI Good”)

6. System Behavior
●	LCD displays PPM & status
●	Buzzer + LED trigger above threshold
●	Bluetooth sends real-time data to your phone wirelessly

Help:
- Make sure the MQ135 has been preheated for at least 24–48 hours.
- Ensure you’ve calibrated the sensor properly (set a correct Ro value).
- Keep the sensor in clean air during calibration.
- Make sure the HC-05 module is powered (VCC = 5V).
- Disconnect Bluetooth TX/RX before uploading code.
- Pair the device using PIN `1234` or `0000`.
Authors:
1)	Ashlesha Gaydhane
2)	Mrunal Tambat
3)	Shruti Sharma
