# BluePill_Encoder_Timer

# Description
Connectiong an encoder to a BluePill and using the Timer Encoder Mode capabitily to read a prosition.
It is also a trial for me to learn how to use the STM32CubeIde and other STM tools.

# Prerequisities
You must have STM32CubeIde installed as well as STM32CubeProgrammer

# Hardware needed
- a CP2102 USB-Serial converter,
- an Encoder (here I used a cheap E38S6G5-600B-G24N encoder)
- a led (I used a led with **integrated resistor**)
- and obviously a BluePill module

# Connections:
| CP2102 | BluePill | Encoder | Led |
| :----- | :------: | :-----: | ---:|
| 5v     | nc       | Vcc     | nc  |
| Gnd    |          | Gnd     | -   |
| Txd    | PA9      | nc      | nc  |
| Rxd    | PA10     | nc      | nc  |
| nc     | PA0      | A       | nc  |
| nc     | PA1      | B       | nc  |
| nc     | PA6      | nc      | +   |

