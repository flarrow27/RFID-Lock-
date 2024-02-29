# RFID Access Control System using Arduino

This project demonstrates an RFID access control system using Arduino. It allows access to a door or any other mechanism based on the authentication of RFID tags/cards. Authorized users can gain access by presenting their RFID tags, while unauthorized attempts trigger an alert.

## Components

- Arduino board
- MFRC522 RFID reader module
- Servo motor
- LEDs (green and red)
- Buzzer

## Wiring

Connect the MFRC522 module to the Arduino according to the pin configuration specified in the code. Connect the servo motor to the designated pin (pin 3 in this code). Connect the LEDs and buzzer to the respective pins (pins 4, 5, and 2 in this code).

## Installation

1. Clone this repository to your local machine or download the code files.
2. Open the Arduino IDE and upload the code to your Arduino board.

## Usage

1. Ensure that the Arduino is powered on and connected to the RFID reader and other components.
2. Present an authorized RFID tag/card to the RFID reader.
3. If the RFID tag is authorized, the green LED will light up, the buzzer will produce a tone, and the servo motor will unlock the mechanism for a predefined duration.
4. If the RFID tag is unauthorized, the red LED will light up, the buzzer will produce a different tone, and the mechanism will remain locked.

## Customization

- Modify the UID of the authorized RFID tags/cards in the code to grant or revoke access as needed.
- Adjust the duration for which the mechanism remains unlocked by changing the delay in the code.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests via GitHub.

## Acknowledgements

- Thanks to the developers of the MFRC522 library for Arduino.
- Special thanks to the Arduino community for their support and contributions.

Enhance your security with the RFID Access Control System!
