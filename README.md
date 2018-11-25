# EmergencyBelt
This is a project that was made for the subject/course CPE 006 - Microprocessor Systems. The ATTINY85 microcontroller program was written in C/C++ using Arduino and the mobile application was made using MIT2 app inventor.

The hardware components are:
* ATTINY85 microcontroller
* HC-05 Bluetooth module
* 1 Tactile Push Button
* 1 Led
* Resistors
* USB plug
* Powerbank or any 5V supply (Lithium-ion 18650 batteries or others)
* Connecting wires

This project basically does two things:
1. Wait for the button to be pressed so that the ATTINY85 will send a signal to a connected/paired phone via Bluetooth module.
2. When the phone recieves a signal it will send a text message to selected contacts in phone. You can add/delete persons in your SOS list.
