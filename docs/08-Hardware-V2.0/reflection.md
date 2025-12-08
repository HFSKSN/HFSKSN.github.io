---
title: Version 2.0
---

## Reflection & Lessons Learned

If I were to create a second version of the design with more time and resources, I would have added more sensors to the subsystem as well as improved the code for my primary and secondary sensors to better suit the needs of the project. 

Sensors that our team had in mind while going through the project but weren't able to implement included a moisture sensor, a UV distance sensor, and a solenoid valve. This was because of several reasons, but the most major of them being that they contained daughterboards and were not approved as a result. Extra time may have given Team 211 a chance to look into making our own custom sensors as a subsitute.

As for the code, there was an issue with the value of the IR Sensor analog output to the main subsystem displayed on the LCD not matching the UART print of the same pin from my microcontroller. Our team concluded that this likely due to the travel from one pin to the other through the traces and wires between them. This may have had to be solved by instead programming the microcontroller to output a digital signal when the sensor output reaches a certain range or threshold (empty/not empty based on distance). Internal timers were also an aspect of the project that we unfortunately had not be able to implement due to time constraints, but I believe it would have greatly improved our overall design.

Additionally, one goal I had in mind when first designing the project was creating a physical prototype with limited mechanical function so that we could see the project in action. While this was not included in the scope of the project, it was something that Team 211 wanted to try as practice for EGR 314. Two things slowed down our software and PCB development considerably, however, making us unable to start the development of the physical model. The first was that multiple sensors that were necessary for our original design to function mechanically had daughterboards, and the second was that PCB printing at ASU suddenly became unavailable. These experiences taught me that one should carefully consult the requirements and constraints of the project before creating a design to avoid having to make last minute changes and that, in the future, it may best to order PCBs instead of printing them in house due to their fasting printing and shipping options.

I do believe that Team 211's project was highly successful and met our team goals. We not only learned engineering skills that will likely prove invaluable to our later courses and careers, but we were also able to deliver a design that passed for basic functionality and fufilled the requirements of the EGR 304. These potential improvements to the overall project and my subsystem that I have listed will guide my thought process and development for my next engineering project in EGR 314. 

## Recommendations for Future Students

1. **Complete labs/assignments ASAP:** Things will go wrong in your labs and project, so give yourself plenty of time to figure out what the problem is and solve it.
2. **Brainstorm your project early:** Our group had to redo many assignments because it took us a long time to figure out what our project was going to do. Answering this question early while consulting the project description and future assignments will put you far ahead.
3. **Talk to your Professor/TAs:** They will be happy to give you insight and feedback on labs, your datasheet, and your project if you ask them whatever questions you have in advance. 
4. **Do external research:** When the course resources and TAs aren't able to answer all your specific questions, try searching it up instead of waiting to ask the professor. There are plenty of videos and articles on soldering, C coding, and pcb design.
5. **Ask your teammates for help:** 
