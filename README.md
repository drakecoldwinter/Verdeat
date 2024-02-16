# Verdeat
Information about how to reprogram a verdeat hydroponics system to be used under <a href="https://www.home-assistant.io">Home assistant</a> with <a href="https://esphome.io">ESPHome</a>

First you will need a FTDI (<a href="https://www.amazon.com/WWZMDiB-FT232RL-Converter-Adapter-Breakout/dp/B0BJKCSZZW/ref=sr_1_4?crid=2K2KAP1DN290F&keywords=FTDI&qid=1708105548&sprefix=ftdi%2Caps%2C78&sr=8-4">Amazon link</a>) and you will need to connect it to the header on the verdeat board. The wires are:

- power in (VCC, 3.3v)     red wire in photo
- empty
- TX     yellow wire
- RX     green wire
- flash button      blue wire
- reset button      green wire
- ground           black wire in photo

<img src="https://github.com/drakecoldwinter/Verdeat/blob/main/program1.jpg" width="500">
<img src="https://github.com/drakecoldwinter/Verdeat/blob/main/program2.jpg" width="500">

Using the FTDI you will need to put the ESP32 in program mode (press program, click reset, release program) and upload <a href="https://github.com/drakecoldwinter/Verdeat/blob/main/hydra.yaml">hydra.yaml</a> into the ESP32
