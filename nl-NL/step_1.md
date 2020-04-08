GPIO is een afkorting voor **G**eneral **P**urpose **I**nput /**O**utput, aansluit-pinnen voor algemeen gebruik. Een Raspberry Pi heeft 26 GPIO-pinnen. Hiermee kun je aan/uit-signalen van en naar elektronische componenten zoals LED's, motoren en knoppen verzenden en ontvangen.

Als je naar een Raspberry Pi kijkt met de USB-poorten naar je toe gericht, is de lay-out van de GPIO-pinnen als volgt.

|            |            |
| ----------:|:---------- |
|        3V3 | 5V         |
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

Elke pin heeft een nummer en er zijn extra pinnen die 3,3 Volt, 5 Volt en aardverbindingen bieden.

Hier is nog een diagram dat de lay-out van de pinnen toont. Het toont ook enkele van de optionele speciale pinnen.

![pinout](images/pinout.png)

Hier is een tabel met een korte uitleg.

| Afkorting         | Naam       | Functie                                                                                             |
| ----------------- | ---------- | --------------------------------------------------------------------------------------------------- |
| 3V3               | 3,3 Volt   | Alles wat op deze pinnen is aangesloten, krijgt altijd 3,3 V spanning                               |
| 5V                | 5 Volt     | Alles wat op deze pinnen is aangesloten, krijgt altijd 5V spanning                                  |
| GND               | nul        | Nul volt, gebruikt om een circuit te sluiten                                                        |
| GP2               | GPIO-pin 2 | Deze pinnen zijn voor algemeen gebruik en kunnen worden geconfigureerd als invoer- of uitvoerpinnen |
| ID_SC/ID_SD/DNC |            | Pinnen voor speciale doeleinden                                                                     |
