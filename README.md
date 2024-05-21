# ESPHome project: Domino Keypad
_Version: 2024.5 stable_

## Simple 4x4 matrix keypad that sends a code to HA
Usage cases are numerus, alarm system, IoT control etc
Press A and enter to arm the alarm
Press the code 1234 to disarm the alarm (example)
press 1 to turn on the lights
press 2 to open the curtains
press 4321 as a fake disarm code to telegram an SOS message (call for help)

Based on an ordinary ESP32 dev board. Configuration is fully adoptable.
It includes a buzzer and a single addressable RGB led plus soft-switches for audio/visual confirmation of actions
Keypad rows and columns connection config is inside keypad.h custom library. Look at lines 24,25 for PINS of ESP32 to use.

### Bonus: A lot of rtttl songs and a service for playing whatever 
### To do: upload scematics and stl files

_Future(?): [2-factor-auth] a bluetooth proxy could be used for "friendly" person detection (up to 3 users) to avoid code theft and miss-use of the keypad
use more than 1 led just to spice up the looks
use a media player intergration and a good amplified speaker to anounce various messages
intergrate a full voice assistant ...or not!
There is some room for including an NFC tag reader
Fingerprint sensor(?)
Camera(?)_
