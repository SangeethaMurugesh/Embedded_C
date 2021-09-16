# Embedded C Programming - Seat Heating Application


# Requirements
# Introduction
The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats. In European countries, the temperature is very low and any electronic designer should make sure that his equipment should work efficiently in that whether. In our project, the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. The Heater will generate the heat and a LCD display will show requested the temperature. In our project we have used ATmega328 microcontroller along with temperature sensor, Switches, Heat generator,and LCD diplay,etc.

# Features
The System will sense is driver or passenger seated or not.
Driver or Passenger has the access to modify the temperature in the vehicle.
As per Drivers request, Heater will generate the heat accordingly.
It is best for European Countries.
Low cost and robust system. *Modular Approach.
## SWOT- Strengths, and Weakness, Opportunities Threats
# Strengths
User Friendly
Easy to alter the temperature inside the vehicles.
Modular Approach
Low cost and Robust system.
# Weakness
Its only applicable for those countries which are having low temperature.
# Opportunities
It can be implemented by having both Heater and AC.
# Threats
Not suitable for average or high temperature places.



## Activity-1 In Action

|OFF|OFF|OFF|ON|
|:--:|:--:|:--:|:--:|
|![OFF](https://user-images.githubusercontent.com/80662569/116460814-1e747f00-a885-11eb-9361-7d70ba90e82d.PNG) |![OFF](https://user-images.githubusercontent.com/80662569/116460808-1c122500-a885-11eb-8023-4ab0ec876fa6.PNG)|![OFF](https://user-images.githubusercontent.com/80662569/116460810-1ddbe880-a885-11eb-9460-5a43f89de00e.PNG)|![ON](https://user-images.githubusercontent.com/80662569/116460813-1ddbe880-a885-11eb-90f1-d0da5705cd19.PNG)|

## Activity-2 In Action

|ADC_00|ADC_11|
|:--:|:--:|
|![ADC_00](https://user-images.githubusercontent.com/80662569/116461383-d0ac4680-a885-11eb-84b5-dc8d17cff3dc.PNG) |![ADC_11](https://user-images.githubusercontent.com/80662569/116461375-cdb15600-a885-11eb-805c-2dc73d198a3d.PNG)|

## Activity-3 In Action

|PWM_20%|PWM_40%|
|:--:|:--:|
|![PWM_20%](https://user-images.githubusercontent.com/80662569/116461901-72cc2e80-a886-11eb-8525-42061d74f693.PNG) |![PWM_40%](https://user-images.githubusercontent.com/80662569/116461893-7069d480-a886-11eb-859b-1ec11c368164.PNG)|
|PWM_70%|PWM_95%|
|![PWM_70%](https://user-images.githubusercontent.com/80662569/116461897-72339800-a886-11eb-9006-369b7be40d44.PNG)|![PWM_95%](https://user-images.githubusercontent.com/80662569/116461900-72339800-a886-11eb-8eea-43aeae327bea.PNG)|

## Activity-4 In Action

|20 DEGREES|25 DEGREES|
|:--:|:--:|
|![20](https://user-images.githubusercontent.com/80662569/116462498-20d7d880-a887-11eb-827d-3c4601f65f82.PNG) |![25](https://user-images.githubusercontent.com/80662569/116462506-22a19c00-a887-11eb-9f96-e03d69035c7e.PNG)|
|29 DEGREES|33 DEGREES|
|![29](https://user-images.githubusercontent.com/80662569/116462509-233a3280-a887-11eb-9b8f-c925bc36cdcd.PNG)|![33](https://user-images.githubusercontent.com/80662569/116462511-233a3280-a887-11eb-91a9-a11098dc7529.PNG)|

### CI and Code Quality

|Build|Cppcheck|Codacy|
|:--:|:--:|:--:|
|[![Compile-Linux](https://github.com/KaaviyaP/EmbeddedC_255944/actions/workflows/Compile.yml/badge.svg)](https://github.com/KaaviyaP/EmbeddedC_255944/actions/workflows/Compile.yml)|[![Cppcheck](https://github.com/KaaviyaP/EmbeddedC_255944/actions/workflows/CodeQulaity.yml/badge.svg)](https://github.com/KaaviyaP/EmbeddedC_255944/actions/workflows/CodeQulaity.yml)|[![Codacy Badge](https://app.codacy.com/project/badge/Grade/e266b3e9afb5440aa83ddbeb4ac95dbe)](https://www.codacy.com/gh/KaaviyaP/EmbeddedC_255944/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=KaaviyaP/EmbeddedC_255944&amp;utm_campaign=Badge_Grade)|


# badges
https://www.code-inspector.com/project/28783/score/svg
https://www.code-inspector.com/project/28783/status/svg
