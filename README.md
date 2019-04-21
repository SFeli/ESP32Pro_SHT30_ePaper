# ESP32Pro_SHT30_ePaper
Display temperature and humidity on ePaper without flashing
Programm to measure the Temperature (Temp) and Humidity (Humi) with 
 *  LOLIN WEMOS SHT30 and display the values on a 
 *  LOLIN WEMOS 2.13 Inch e-Paper display.
Uses a LOLIN D32 Pro Board.
 
Features & Notes:
1) Digits are predefined by unsigned char-arrays like I_zero[128] for the use of (LOLIN_EPD)-partDisplay as a 32x32 bitmap.
 By using the new partDisplay and partUpdate funktion there is no flashing! 
2) All digits (graficbitmaps) are in another array Number[] 
3) The measured values are updated digitwise.

How nice the smooth update :-)
![Setup](/LolinPro_SHT30_ePaper.gif)
