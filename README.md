# RFID-Lock-System
RFID Lock System using Arduino

This project is an RFID-based security system that uses an Arduino microcontroller to control access to a secure area. The system utilizes an RFID reader to scan RFID tags/cards, and only authorized tags/cards can unlock the door. This project is ideal for implementing a secure entry system for homes, offices, or other restricted areas.

The Arduino code is written in C/C++ and includes libraries for controlling the RFID reader and servo motor. You can find the complete code in the code directory of this repository.

Libraries Used
MFRC522: For interfacing with the RFID reader.
Servo: For controlling the servo motor

Features
RFID Authentication: Uses RFID technology to authenticate users.
Secure Access: Only pre-registered RFID tags can unlock the door.
Visual Indicators: LEDs indicate the lock/unlock status.
Buzzer Alert: A buzzer sounds for successful or failed authentication attempts.
Easy to Expand: New RFID tags can be easily added or removed from the system.
