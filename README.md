# Verdeat
Information about how to reprogram a verdeat hydroponics system to be used under Home assistant with ESPHome

First you will need a FTDI (<a href="https://www.amazon.com/WWZMDiB-FT232RL-Converter-Adapter-Breakout/dp/B0BJKCSZZW/ref=sr_1_4?crid=2K2KAP1DN290F&keywords=FTDI&qid=1708105548&sprefix=ftdi%2Caps%2C78&sr=8-4">Amazon link</a>) and you will need to connect it to the verdeat board. The wires are:

- power in (VCC, 3.3v) red wire in photo
- empty
- TX yellow
- RX green
- flash button blue
- reset button green
- ground black in photo

<img src="https://github.com/drakecoldwinter/Verdeat/blob/main/program1.jpg" width="500">

The yaml for ESPHOME is in the files of this page
