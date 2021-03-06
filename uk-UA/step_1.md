GPIO – це абревіатура для **G**eneral **P**urpose **I**nput/**O**utput (інтерфейс введення/виведення загального призначення). Raspberry Pi має 26 або 40 GPIO-пінів. Вони дозволяють надсилати та приймати сигнали вмикання/вимикання до та від електронних компонентів, таких як світлодіоди, двигуни та кнопки.

Якщо подивитися на Raspberry Pi з USB-портами, повернутими до тебе, розташування GPIO-пінів буде виглядати наступним чином.

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

Кожен пін має номер, а також є додаткові піни, які забезпечують 3,3 вольта, 5 вольтів і заземлення (GND).

Ось ще одна схема, яка показує розташування пінів. Також вона показує деякі додаткові спеціальні піни.

![схема розміщення пінів](images/pinout.png)

Ось таблиця з коротким поясненням.

| Скорочення        | Повна назва | Призначення                                                                                    |
| ----------------- | ----------- | ---------------------------------------------------------------------------------------------- |
| 3V3               | 3,3 вольта  | Все, що підключено до цих пінів, постійно отримуватиме напругу 3,3 В                           |
| 5V                | 5 вольтів   | Все, що підключено до цих пінів, постійно отримуватиме напругу 5 В                             |
| GND               | заземлення  | Нуль вольтів, які використовуються для замкнення ланцюга                                       |
| GP2               | пін 2 GPIO  | Ці піни призначені для загального використання і можуть бути налаштовані як вхідні або вихідні |
| ID_SC/ID_SD/DNC |             | Піни спеціального призначення                                                                  |
