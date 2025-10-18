---
title: Component Selection
---

**Water Pressure Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://github.com/user-attachments/assets/07846d6b-d679-4beb-993b-fcb20360a954)<br>Option 1.<br>1597-1515-ND Water Pressure Sensor<br>$12.90/each<br>[Link to product](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/114991178/7387419)                 | \* Least expensive<br>\* No additional wiring needed<br>\* Designed to be integrated into pipe system                                               | \* Requires external components<br>\* Pressure range is too large<br>\* Slow shipping speed |
| ![](https://github.com/user-attachments/assets/def2d198-ab0b-4397-9a04-52e3b57283db)<br>Option 2.<br>SEN0257 Gravity: Analog Water Pressure Sensor<br>$15.90/each <br> [Link to product](https://www.dfrobot.com/product-1675.html) | \* Pressure range is ideal <br>\* No additional wiring needed <br>\* Designed to be integrated into pipe system <br>\* Many online resources on how to use this sensor | * Expensive <br>\* Requires external components |
| ![](https://github.com/user-attachments/assets/be59a137-4df5-4e03-93eb-a74e59109b44)<br>Option 3.<br>MPX5010DP-ND Pressure Sensor<br>$17.90/each <br> [Link to product](https://www.digikey.com/en/products/detail/nxp-usa-inc/MPX5010DP/464054) | \* Very accurate sensor <br>\* Most throughly detailed datasheet <br>\* Through-hole pins <br>\* Many online resources on how to use this sensor | * Most expensive <br>\* Slow shipping speed<br>\* Has three no connect pins according to datasheet<br>\* Not easily integrated into pipe system<br>\* Pressure range may be to small                                                  |

**Choice:** Option 2: SEN0257 Gravity: Analog Water Pressure Sensor

**Rationale:** An industrial pressure transducer designed for microchip use is better suited to our device than non-industrial pressure sensors such as the MPX5010DP-ND because of its larger range and being specifically designed to work with pipes and liquid flow. Despite not being found on Digikey and being more expensive, the SEN0257 sensor is designed for small-scale microcontroller projects and is able to be calibrated according to our device needs, making it the most suitable option for our team.

**Ultrasonic Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://github.com/user-attachments/assets/a3c08e46-b917-4de3-b181-35975784f562)<br>Option 1.<br>HC-SR04 Ultrasonic Distance Sensor<br>$3.95/each<br>[Link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3942/9658069)                 | \* Inexpensive<br>\* Many online resources on how to use this sensor<br>\* Through-hole                                               | \* Not Waterproof<br>\* Digikey datasheet is lacking in detail |
| ![](https://github.com/user-attachments/assets/d1ef8ca1-b297-42fb-b3d6-cec85f0d6423)<br>Option 2.<br>RS485 750CM Ultrasonic Level Sensor<br>$21.90/each <br>[Link to product](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/101991041/19285435) | \* Waterproof <br>\*  | * Very expensive<br>\* Minimum range is too large |
| ![](https://github.com/user-attachments/assets/2ba1f030-5df4-42ee-a766-e8479a13186f)<br>Option 3.<br>MA40S4S Ultrasonic Sensor<br>$5.77/each <br>[Link to product](https://www.digikey.com/en/products/detail/murata-electronics/MA40S4S/4358147) | \* Through-hole <br>\* Humidity resistant | * Expensive <br>\* Only two pins<br>Voltage rating too high                                                         |

**Choice:** Option 1: HC-SR04 Ultrasonic Distance Sensor

**Rationale:** This cheap ultrasonic distance sensor 
