# What are GPIO pins?

GPIO is an acronym for *G*eneral *P*urpose *I*nput/*O*utput. On a Raspberry Pi there are 26 GPIO pins. These pins allow you to send and receive on/off signals to and from electronic components such as LEDs, motors and buttons.

If you look at a Raspberry Pi, with the USB ports facing towards you, the layout of the GPIO pins is as follows.

|            |            |
|-----------:|:-----------|
|    3V3     | 5V         |
|  **GPIO2** | 5V         |
|  **GPIO3** | GND        |
|  **GPIO4** | **GPIO14** |
|        GND | **GPIO15** |
| **GPIO17** | **GPIO18** |
| **GPIO27** | GND        |
| **GPIO22** | **GPIO23** |
|        3V3 | **GPIO24** |
| **GPIO10** | GND        |
|  **GPIO9** | **GPIO25** |
| **GPIO11** | **GPIO8**  |
|        GND | **GPIO7**  |
|        DNC | DNC        |
|  **GPIO5** | GND        |
|  **GPIO6** | **GPIO12** |
| **GPIO13** | GND        |
| **GPIO19** | **GPIO16** |
| **GPIO26** | **GPIO20** |
|        GND | **GPIO21** |

Each pin has a number, and there are additional pins that provide 3.3 Volts, 5 Volts and Ground connections.

Here's another diagram showing the layout of the pins.

![pinout](images/pinout.png)

This shows some of the optional special pins as well.

Here's a table with a brief explanation.

|   |   |   |
|---|---|---|
| 3V3 | 3.3 volts | Anything connected to these pins will always get 3.3V of power |
| 5V | 5 volts | Anything connected to these pins will always get 5V of power |
| GND | ground | Zero volts, used to complete a circuit |
| GP2 | GPIO pin 2 | These pins are for general-purpose use and can be configured as input or output pins |
| ID_SC/ID_SD/DNC | Special purpose pins ||
