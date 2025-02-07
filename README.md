# PUSH-BUTTON-COUNTER

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : MADHUMITHA K

*INTERN ID* : CT08LRW

*DOMAIN* : EMBEDDED SYSTEMS

*DURATION* : 4 WEEKS

*MENTORS* : NEELA SANTOSH

*Description* :

This program allows for the control of four LEDs connected to an ESP32 board via Bluetooth using the BluetoothSerial library. The ESP32 is set up to communicate over Bluetooth, enabling a user to remotely control the LEDs from a Bluetooth-capable device like a smartphone or computer. The LEDs are linked to pins 27, 26, 25, and 34 of the ESP32, and these pins are designated as outputs in the setup() function. The Bluetooth serial connection is initialized with the name "ESP32_BT_Home_Auto," and the device displays a message on the serial monitor indicating that it is ready for pairing. In the main loop, the program listens for incoming Bluetooth commands. Based on the received character, it turns the corresponding LED on or off. Each command corresponds to a specific character ('1' to '8'): for example, '1' turns LED1 on, '2' turns LED1 off, '3' turns LED2 on, and so forth. After executing each command, the program sends a feedback message to the Bluetooth device confirming the action (e.g., "LED1 ON" or "LED2 OFF"). If an invalid command is received, the program responds with "Invalid Command." This project is a straightforward demonstration of remote control via Bluetooth, ideal for basic home automation or IoT applications.

![Image](https://github.com/user-attachments/assets/748a8547-6340-40c2-924f-75c7a70c564e)
