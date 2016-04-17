# shushh-speaker
The shush spekaer uses an Arduino uno with the Adafruit MP3 shield and a micrphone to detect if someone is being too loud. It then plays a custom pre-recorded track that has a salty and sassy additude. The tracks is different base on the different readings. It  will also keep playing the track if the sound being detective does not drop to a certain range. The speaker  can also be used as a regular speaker through bluetooth connection.


Step 1: Time to go shopping

You'll need the following items for the project:

1-Arduino Uno (or similar)

1-Adafruit "Music Maker" MP3 Shield for Arduino w/3W Stereo Amp - v1.0 (http://www.adafruit.com/products/1788)

1-Micro SD card for MP3 files

1-speaker. In the proejct, I used the 20W 4 Ohm Full Range Speaker - XS-GTF1027 from adafruit (https://www.adafruit.com/products/1732)

1-CNC cut dibond box  or any sort of container

1-Bluetooth reciever. Mine are the H - 266 Wireless NFC Bluetooth Music Audio Receiver in the colour black

1-Amp. I picked up the AUDIO AMPLIFIER MODULE TDA7297 from Lee's Electronic (http://leeselectronic.com/product/15466.html?search_query=amp&results=187)

1-Voice activation breakout (http://leeselectronic.com/product/20092.html?search_query=voice+activation+breakout&results=1)

10-wires or more if needed. 

1-1K Resisdor 

1-2222 Transistors 

1-Relay

1-ARDUINO PROTOSHIELD W/ MINI BREADBOARD KIT (http://leeselectronic.com/product/20131.html?search_query=breadboard+shield&results=8)

1-5 VDC 1000mA regulated switching power adapter (or similiar for the amp)

1-9 VDC 1000mA regulated switching power adapter (or similar, arduino compatible)




Step 2: Assemble Arduino, PIR Sensor, Speaker, and Shield


MP3 Shield

The shield comes un-assembled so I replaced the header pins with stack-able headers so I stack a protoshield on top and easily prototype other items.


Voice activation breakout

The breakout is connected with the following pins / colors:

Red (VCC) > 5v

Black(GND) > Ground

Yellow (OUT) > Digital Pin 2
  


Bluetooth, Mp3 shield, Amp, Relay and Transistors 

Cut the bluettooth 3.5mm cable input into half, so one end of the cable connect to the bluetooth(BT) another end connect to the mp3 shield(mp3). Strip the 3 wires inside the cable. the wires should be blue (B), red(R) and  yellow(Y).

The Relay is connected with the following colour wire/pin:

BT Yellow wire and MP3 Yellow wire and Amp brown wire (GND)> Ground

BT Red wire       --  Mp3 Blue wire

MP3 Blue wire     --  BT red wire

Amp IN1 red wire  --  Amp IN2 Orange wire

Transistors pin E --  orange wire to 5v  

1k resisdor connect to Transistors PIN B (MP3/BT pin) > digital pin 5

Transistors PIN C  > ground


Speaker

Connect the speaker to the Amp to the 2pin terminal blocks.


Battery / Power

Wall plug power adapter for both amp and ardunio as the speaker is designed to be wall mounted



Video:

https://youtu.be/sUawIe9fNpk

https://youtu.be/WKYH9EBVjV0

https://youtu.be/TZY_0IJMwsE
