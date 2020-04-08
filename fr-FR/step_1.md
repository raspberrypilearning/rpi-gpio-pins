GPIO est l'acronyme de **G**eneral **P**urpose **I**nput /**O**utput. Un Raspberry Pi possède 26 broches GPIO. Celles-ci te permettent d'envoyer et de recevoir des signaux marche / arrêt vers et depuis des composants électroniques tels que des LED, des moteurs et des boutons.

Si tu regardes un Raspberry Pi avec les ports USB tournés vers toi, la disposition des broches GPIO est la suivante.

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

Chaque broche a un numéro, et il y a des broches supplémentaires qui fournissent des connexions de 3,3 volts, 5 volts et de masse.

Voici un autre schéma montrant la disposition des broches. Il montre également certaines des broches spéciales en option.

![brochage](images/pinout.png)

Voici un tableau avec une brève explication.

| Abréviation           | Nom complet   | Fonction                                                                                                            |
| --------------------- | ------------- | ------------------------------------------------------------------------------------------------------------------- |
| 3V3                   | 3,3 volts     | Tout ce qui est connecté à ces broches recevra toujours 3,3 V d'alimentation                                        |
| 5V                    | 5 volts       | Tout ce qui est connecté à ces broches recevra toujours 5 V d'alimentation                                          |
| GND                   | ground        | Zéro volt, utilisé pour compléter un circuit                                                                        |
| GP2                   | Broche GPIO 2 | Ces broches sont destinées à un usage général et peuvent être configurées en tant que broches d'entrée ou de sortie |
| ID_SC / ID_SD / DNC |               | Broches à usage spécial                                                                                             |
