# Heart-Rate-Monitor
Measuring the BPM using Arduino and Pulse sensor.

The Board used is the Arduino Nano

The TFT LCD used is the MCUfriend 2.4" TFT LCD.
The driver number of this LCD is - 0x4532

The data pin of the pulse sensor is connected to A6 of the Nano. A5 is used as VCC. The display pins are connected using the following table:

|Arduino Pin |	LCD Shield Pin |
 -----------------------------
|3.3V |	3.3V	|
|5V |	5V |
|GND |	GND |
|A0 |	LCD_RD |
|A1 |	LCD_WR|
|A2	| LCD_RS|
|A3 |	LCD_CS|
|A4	| LCD_RST|
|D2 |	LCD_D2|
|D3	| LCD_D3|
|D4 |	LCD_D4|
|D5	| LCD_D5|
|D6 |	LCD_D6 |
|D7	| LCD_D7 |
|D8 |	LCD_D0	|
|D9	| LCD_D1	|
|D10 | SD_CS	|
|D11	| SD_DI	|
|D12 |	SD_DO	|
|D13	| SD_SCK|
