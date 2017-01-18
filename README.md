# ITP Unconference ::: DIY sensors

This is a workshop to instigate you to use textile conductive materials to create capacitive sensors
For the purpose of this workshop we'll create a strech sensor with conductive thread (an alpha version of what was seen [here](https://renatagaui.com/in-the-silence-of-my-lonely-room/) ). 


### for this workshop you'll need:
- Conductive thread on a slipknot chain (or whatever arrangement/mechanism you feel could work)
- Arduino + breadboard + usb cable
- Resistor between 50k - 50M (we'll be using a 10M)
- Alligator clips
- Multimeter
- Arduino IDE and CapacitiveSensor Library

1. Get a piece of conductive thread and do the loose loops/knots
2. Connect the tip of the conductive thread to your multimeter to check the resistance of it.

## Getting our breadboard ready

1. Download and install CapacitiveSense library [here](https://github.com/arduino-libraries/CapacitiveSensor/zipball/master).
2. Connect the resistor between digital pins 02 & 04.
3. Open CapacitiveSensorSketch (on this repo)
4. Upload the code on the board.
5. Test if the capacitive sensor is working by touching the resistor and seeing values change on the serial monitor.

## Connect your sensor to your circuit!

1. Just connect one of the thread tips to pin 02
2. See if the stretch sensor is working through the serial monitor.
3. taran! Go make your own sensors =)

## References
- [Kobakant DIY Session](http://www.kobakant.at/DIY/)
- [Syscom advanced materials](http://www.metalcladfibers.com/product-overview/)
