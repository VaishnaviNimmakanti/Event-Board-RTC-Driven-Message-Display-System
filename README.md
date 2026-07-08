# Event-Board-RTC-Driven-Message-Display-System
Overview
The EventBoard – RTC-Driven Message Display System is an embedded systems project developed using the LPC2148 (ARM7) microcontroller. It automatically displays predefined event messages on a 16×2 LCD based on the current date and time using the built-in Real-Time Clock (RTC). The system also provides a secure Admin Mode that allows authorized users to update the RTC time and enable or disable scheduled messages. During idle periods, the LCD displays the current time, date, and room temperature measured using the LM35 temperature sensor, making it a smart and efficient real-time information display system.
Objective
*Develop an RTC-based automated event display system.
*Display scheduled messages automatically at predefined times.
*Provide password-protected Admin Mode for secure system configuration.
*Display real-time clock and room temperature when no event is scheduled.
*Demonstrate the integration of multiple embedded peripherals using LPC2148.
Hardware Requirements
*LCD2148 Microcontroller
*16x2 Character LCD
*RTC Module(or LPC2148 internal RTC)
*Matrix Keypad
*LM35 Temperature Sensor
*Red LED
*Green LED
Software Requirement
*Keil 
Features
*RTC-based automatic message scheduling.
*Displays 10 predefined scrolling event messages.
*Password-protected Admin Mode using keypad and switch.
*User can edit RTC time and manage scheduled messages.
*Real-time display of date, time, and temperature.
*LM35 sensor integration for room temperature monitoring.
*Green LED indicates active event display.
*Red LED indicates normal/idle mode.
*Smooth scrolling text on 16×2 LCD.
*Developed using Embedded C in Keil IDE.
Application
*Colleges and educational institutions.
*Offices and corporate buildings.
*Training centers and laboratories.
*Hospitals and healthcare facilities.
*Factories and industrial workplaces.
*Public information display boards.
*Event management systems.
*Smart notice boards for organizations.
Future Scope
*Add Wi-Fi or IoT connectivity for remote message updates.
*Integrate GSM for SMS-based event scheduling.
*Store schedules in EEPROM or SD card for larger memory.
*Develop a mobile or web application for remote management.
*Support multiple languages for message display.
*Add voice announcements for scheduled events.
*Integrate cloud-based event synchronization.
*Upgrade to a graphical TFT display for improved user experience.
Conclusion
The RTC-Driven EventBoard demonstrates an efficient real-time embedded system capable of automatically displaying scheduled messages without manual intervention. By integrating the LPC2148 RTC, LCD, keypad, LM35 temperature sensor, LEDs, and secure Admin Mode, the project showcases practical applications of embedded systems in automation. It provides a reliable, user-friendly, and scalable solution for smart event notification systems used in educational institutions, offices, industries, and other public environments.
