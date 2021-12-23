**BluePill_Encoder_Timer**

Just a attempt to program the Bluepill with the STM32CubeIde
Using the timer Encoder Mode functionality to read a rotary encoder
There is no great idea behind but if it can help ...

it uses a CP2102 to communicate via USB to Computer and a E38S6G5-600B-G24N encoder and a Led + integrated PC13 Led

Connections:
**CP2102**\
5V --> Encoder Vcc\
Gnd	--> Gnd\
Txd	--> BluePill PA10\
Rxd --> BluePill PA9\
**Encoder**\
Vcc -->	CP2102 5V\
Gnd --> Gnd\
A -->	BluePill PA0\
B --> BluePill PA0\
**LED**\
Cathode --> BluePill PA6\
Anode --> Gnd\
