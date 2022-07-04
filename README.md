# iot_door_lock

This is an 3D printed IOT door lock based on NodeMCU. It uses a servo motor for locking and unlocking the door. It also has an oled screen in the front to display the status of the device.
<br><br>
When a breach occurs it alerts the owner via:<br>
1. Email
2. Phone Call
3. Text Message

<br>
It uses RFID cards or NFC or a mobile app to lock/unlock the door.
<br>

<br>
It has a built in backup battery which can last upto 10 hours. If the device restarts when locked because of tampering, it will give a 10 second timer to place a verified RFID card or authenticate via the mobile app to avoid sending the alert.
<br>
<br>
The mobile app is built using Blynk.
<br><br>
Requirements are:
<br><br>
1. ESP-8266 board.<br>
2. Li-ion Battery with charging circuit.<br>
3. OLED display to display information.<br>
4. Servo to lock/unlock the door and a magnetic sensor to know the position of
the door.<br>
5. RFID chip with SPI interface.<br>
6. 3D printer to print the body and other
components.<br>
7. We will be programming the
microcontroller using Arduino IDE which is
based on C language.<br>
8. We will be using Blynk software in
conjunction to make an app for the door
lock.<br>
