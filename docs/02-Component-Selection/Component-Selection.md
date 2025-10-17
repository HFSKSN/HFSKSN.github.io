---
title: Component Selection
---

**Water Pressure Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://github.com/user-attachments/assets/07846d6b-d679-4beb-993b-fcb20360a954)<br>Option 1.<br>1597-1515-ND surface mount crystal<br>$12.90/each<br>[link to product](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/114991178/7387419)                 | \* Least expensive<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components<br>\* Pressure range is too large<br>\* Slow shipping speed |
| ![](https://github.com/user-attachments/assets/def2d198-ab0b-4397-9a04-52e3b57283db)<br>Option 2.<br>SEN0257 Gravity: Analog Water Pressure Sensor<br>$15.90/each <br>\* [Link to product](https://www.dfrobot.com/product-1675.html) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Requires external components |
| ![](https://github.com/user-attachments/assets/be59a137-4df5-4e03-93eb-a74e59109b44)<br>Option 3.<br>MPX5010DP-ND surface mount oscillator<br>$17.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/nxp-usa-inc/MPX5010DP/464054) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * Most expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

**IR Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
