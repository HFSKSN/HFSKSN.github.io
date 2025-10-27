---
title: Power Budget
---

## Overview
The purpose of this power budget is to record the voltage and current requirements for each component to ensure that our subsystem design can function within the limitations of the system. The four major components, the microcontroller, IR sensor, pressure sensor, and op-amp, all can be placed on the +5V power rail. The rail recieves +5VDC using the LM7805 voltage regulator, which must recieve a supply voltage between +7 and +35 volts and can output a maximum current of 1A. These requirements, as well as the requirements of the three other subsystems which also use the LM7805, limit the type of power supply we can use for our device.

![Power Budget](https://github.com/user-attachments/assets/37a13087-40f1-4316-81be-7bd975c2cf9d)

**Figure 1:** Subsystem Power Budget

## Conclusions

From the prepare Power Budget, our team was able to choose a power supply that allowed for the current draw of each of our boards. Due to the stationary and long active sessions expected of an irrigation system, we choose to use an external power supply over a battery. We chose a wall-mounted power supply of 9V 5A to provide enough power and current for each of our boards, leaving room for any extra components we might add.

## Resources

The power budget as a PDF download is available [*here*](https://github.com/user-attachments/files/23154111/EGR304_PowerBudget.pdf), and a Microsoft Excel Sheet [*here*](https://github.com/user-attachments/files/23154129/EGR304_PowerBudget.xlsx).
