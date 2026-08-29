## Event Board RTC Driven Message Display System

## 📑 Table of Contents

🖼️ **Project Overview**

🎯 **Project Objective**

🔧 **Hardware Components**

💻 **Software Tools**

📊 **Block Diagram**

⚙️ **Working**

📟 **LCD Display Example**

📸 **Project Images and Videos**

🌐 **Applications**

🚀 **Future Enhancement**

✅ **Conclusion**

## 📌 Project Overview

EventBoard – RTC-Driven Message Display System is a real-time embedded system developed using the LPC2148 ARM7 microcontroller to automatically display predefined messages on a 16×2 LCD at scheduled times. The system uses the microcontroller’s Real-Time Clock (RTC) to manage time-based message scheduling and displays messages with a scrolling mechanism.

The system stores 10 predefined messages in the controller’s memory. An Admin Mode provides secure access through a switch, keypad, and password protection, allowing the administrator to edit the current time and select the messages that should be active for the day.

During normal operation, when the RTC time matches a scheduled message, the corresponding message is displayed on the LCD and a green LED indicates the active display. When there is no scheduled message, the LCD displays the current time and room temperature, which is measured using an LM35 sensor through the LPC2148’s built-in ADC. A red LED indicates the idle display mode.

## 🎯 Project Objective

1. To develop a real-time automated event/message display system using the LPC2148 ARM7 microcontroller.
2. To display predefined messages automatically at specific times using the on-chip Real-Time Clock (RTC).
3. To implement a scrolling mechanism for displaying messages on a 16×2 LCD.
4.To provide a secure Admin Mode using a switch, keypad, and password protection.
5. To allow the administrator to edit the RTC time and select the messages that should be active for the day.
6. To monitor and display room temperature using an LM35 sensor and the LPC2148's built-in ADC.
7. To use LED indicators to differentiate between active message display and idle display modes.

## 🔧 Hardware Components

| No. | Component | Purpose |
|---:|---|---|
| 1 | **LPC2148 ARM7 Microcontroller** | Main controller for managing all system operations |
| 2 | **16×2 LCD Display** | Displays scheduled messages, time, and temperature |
| 3 | **4×4 Keypad** | Used for password entry and Admin Mode operations |
| 4 | **RTC (Real-Time Clock)** | Maintains current time and controls time-based message scheduling |
| 5 | **LM35 Temperature Sensor** | Measures the room temperature |
| 6 | **Green & Red LEDs** | Indicate active message and idle display modes |
| 7 | **Buzzer** | Provides audio alerts |
| 8 | **Admin Mode Switch** | Used to enter Admin Mode |

