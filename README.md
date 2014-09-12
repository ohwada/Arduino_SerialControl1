Arduino_SerialControl1
======================

Arduino skech which control LED and button with PC or Android

## Feature
This skech recieve the command and send the message using USB serial.<br>

Command : PC -> Arduino<br>
"L0" : trun off LED<br>
"L1" : trun on LED<br>
"Pxxx" : control the brightness of LED<br>
　xxx ; three digits 000 - 255<br>

Message : PC <- Arduino<br>
"B0" : buton is off<br>
"B1" : buton is pushed<br>
"Axxxx" : analog value<br>
　xxxx ; one to three digits 0 - 1023<br>

This skech is used with Android app.<br>
Android_UsbSerialArduino1<br>
https://github.com/ohwada/Android_UsbSerialArduino1

## blog (in Japanese)
http://android.ohwada.jp/archives/5117
