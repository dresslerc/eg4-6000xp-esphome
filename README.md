# Control EG4 6000XP through Home Assistant through a ESP32 Microprocessor with ESPHome

First of all, the initial code came from this repo:
https://github.com/adamksmith/ESPHome-Projects/blob/main/EG4-6000-XP/Parent-Inverter.yaml

I've modified the code above so it works with Lilygo T-CAN485:
https://lilygo.cc/products/t-can485

The end results look like this (in my Home Assistant):
![image](https://github.com/user-attachments/assets/08ebc7a5-cad1-4831-bcb7-bba3962e99c7)

The philosophy for this project is that Home Assistant does most of the 6000XPs controls (AC First, AC Charge Based On, Charge Current, Discharge Control, etc).

I'll add more documentation later....
