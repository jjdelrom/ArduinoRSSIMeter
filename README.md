# A Simple Arduino RSSI Meter

This is a very simple RSSI Meter made with Arduino.
For LCD I prefer the version with I2C for less connections.

| *Pin* | *Descripion* |
| Pin D12 | Config Button |
| Pin D8  | Piezzo Buzzer Signal |
| Pin A0  | RSSI from VRX |

Keep the button in D12 pressed to enter in configuration mode.
- VRX On / VTX Off to set the 0% RSSI signal
- VRX On / VTX On to set the 100% RSSI signal

The values are saved in EEPROM. No need to change the source code
to adjust the values comming from your Video RX.

denys.sene@gmail.com
<p>
<img src="ArduinoRSSIMeter_bb.png">
</p>