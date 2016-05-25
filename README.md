# OpenPLC Arduino Firmware
This is a repository to store firmwares for the Arduino platform to run OpenPLC. The firmware must be uploaded using the Arduino IDE. After uploading the firmware, connect the arduino to the USB port and run the OpenPLC_v2.

Arduino UNO
/******************PINOUT CONFIGURATION*******************

Digital In: 2, 3, 4, 5, 6           (%IX0.0 - %IX0.4)

Digital Out: 7, 8, 12, 13           (%QX0.0 - %QX0.3)

Analog In: A0, A1, A2, A3, A4, A5   (%IW0.0 - %IW0.5)

Analog Out: 9, 10, 11               (%QW0.0 - %QW0.2)

**********************************************************/

Arduino MEGA
/************************PINOUT CONFIGURATION*************************

Digital In: 22, 24, 26, 28, 30, 32, 34, 36,       (%IX0.0 - %IX0.7)
            38, 40, 42, 44, 46, 48, 50, 52,       (%IX1.0 - %IX1.7)
            14, 15, 16, 17, 18, 19, 20, 21        (%IX2.0 - %IX2.7)
			
Digital Out: 23, 25, 27, 29, 31, 33, 35, 37       (%QX0.0 - %QX0.7)
             39, 41, 43, 45, 47, 49, 51, 53       (%QX1.0 - %QX1.7)

Analog In: A0, A1, A2, A3, A4, A5, A6, A7         (%IW0.0 - %IW0.7)
           A8, A9, A10, A11, A12, A13, A14, A15   (%IW0.8 - %IW0.15)
		   
Analog Out: 2, 3, 4, 5, 6, 7, 8, 9,               (%QW0.0 - %QW0.7)
            10, 11, 12, 13                        (%QW0.8 - %QW0.11)
			
*********************************************************************/
