# ESP32Pro_SHT30_ePaper
Displays temperature and humidity on ePaper without flashing
The Arduino-Programm measures the Temperature (Temp) and Humidity (Humi) with 
 *  LOLIN WEMOS SHT30 and displays the values on a 
 *  LOLIN WEMOS 2.13 Inch e-Paper.
Uses a LOLIN D32 Pro Board.
 
Features & Notes:
1) Digits are predefined on unsigned char-arrays like I_zero[128] to use the (LOLIN_EPD)-partDisplay.
 By using the new partDisplay and partUpdate funktion there is no flashing! 
2) All digits (grafic bitmaps (32x32)) are listed in the array Number[] for better adressing the digits.
3) The measured values are updated digitwise.

How nice the smooth update :-)
![Setup](/LolinPro_SHT30_ePaper.gif)
