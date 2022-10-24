# 6S-Pack-Voltage-Level-Indicator

This basic, fully analog voltage gauge shows a full bar at 25.2V (6S Li-ion) and an empty bar at 16.8V. It uses a ladder divider and 16 comparators (4 quad ICs) to drive the LEDs. There are some heating issues with the comparators when kept on for too long, and the input FET Zener protection needs to be placed on the high-side. Thus, a new revision is in progress. I'm making tiny modules that can be connected to create a fully functional solar storage/charger/BMS/Inverter.


![IMG_0243 (1)](https://user-images.githubusercontent.com/15238109/197577640-bf297d20-16ae-49a9-850b-88ae77329540.gif)
