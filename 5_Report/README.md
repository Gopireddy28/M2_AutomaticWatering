# AUTOMATIC WATERING PLANTS

## ABSTRACT

Plants, as we all know, are an integral component of our lives. Plants require constant attention in order to thrive. Plants may not be able to survive if the soil and surroundings are deficient in nutrients. As a result of this effort, we will be able to make our gardens self-sustaining. The sensor we used in this project checks the soil moisture and air temperature of the plants, and then starts watering them automatically based on the data obtained from the numerous sensors in our project. It is critical to maintain and monitor our plants and gardens. We must care the plants on a regular basis in order to keep them free of pests. As a result, this endeavour aids the garden's self-care.

## DESCRIPATION

Plants play a vital role in maintaining the carbon dioxide and oxygen in air. Many plants die due to urbanization. But apart from it plants also die due to lack of maintenance. Gardening is a healthiest hobby anyone can adopt. But they need continuous care without break. So the main aim of this project is to provide proper care to the plants. This project will also ease the gardening. It is built using AVR Microcontroller and bunch of electronic sensors.. In this project we have used soil moisture sensor for calculating the moisture in the soil .The controller is interfaced with the LCD display where it displays the data received from various sensors. The controller is programmed using embedded C.

## REQUIREMENTS
 
- HIGH LEVEL REQUIREMENTS

<html>
<body>
<!--StartFragment-->

HLR_ID | High Level Requirements
-- | --
HLR01 | It shall have a Microcontroller
HLR02 | It shall have Sensors
HLR03 | It shall have Switch
HLR04 | It shall have a Display

<!--EndFragment-->
</body>
</html>

- LOW LEVEL REQUIREMENTS

<html>
<body>
<!--StartFragment-->

LLR_ID | Low Level Requirements
-- | --
HLR01_LLR01 | It shall have a Microcontroller(ATmega32) to recieve/transmit the data
HLR02_LLR02 | It shall have a Soil Moisture Sensor to detect the moisture in the soil
HLR02_LLR03 | It shall have a Temperature and Humidity Sensor to detect the humidity in the air
HLR03_LLR04 | It shall have a Relay Module which is used as an automatic switch
HLR03_LLR05 | It shall have a LED which is uesd to blink when the switch ON
HLR04_LLR06 | It shall have a 16x2 LCD which is used to display the moisture of the soil, humidity in the air

<!--EndFragment-->
</body>
</html>

# BLOCK DIAGRAM

![1picture](https://user-images.githubusercontent.com/82794905/164261170-da01159c-dbbd-4e26-ae3a-3ee275c3fe9b.jpg)

# FLOW CHART

![2picture](https://user-images.githubusercontent.com/82794905/164261167-f8cdaebc-40de-4411-a598-516c630eaaab.jpg)

# SYSTEM DESIGN

![3picture](https://user-images.githubusercontent.com/82794905/164261162-0a4a8530-b525-4942-b241-1512c6b44f06.jpg)

# SUB-SYSTEM DESIGN

- TEMPERATURE SENSOR

![4picture](https://user-images.githubusercontent.com/82794905/164261160-181adf81-956c-4cd2-96b3-c28a7452181d.jpg)


- SOIL MOISTURE SENSOR

![5picture](https://user-images.githubusercontent.com/82794905/164261157-eb849679-a0e1-4b2b-8737-2b543096a1b8.jpg)

- LED

![6picture](https://user-images.githubusercontent.com/82794905/164261156-171246c6-a64e-458a-a123-b587dd0afceb.jpg)


- RELAY MODULE

![7picture](https://user-images.githubusercontent.com/82794905/164261152-da9ea9ee-c67a-4e56-9696-4a83a7b32ce1.jpg)

- LCD

![8picture](https://user-images.githubusercontent.com/82794905/164261138-eb005a21-4518-4cb4-8ec4-5bbf686b04a6.jpeg)

# COMPONENTS DESCRIPATION

- ### Microcontroller
An integrated circuit that contains a microprocessor along with memory and associated circuits and those controls some or all the functions of an electronic device (such as a home appliance) or system.

- ### ATmega32
The AVR microController is based on the advanced Reduced Instruction Set Computer (RISC) architecture. ATmega32 microController is a low power CMOS technology based controller. Due to RISC architecture AVR microcontroller can execute 1 million of instructions per second if cycle frequency is 1 MHz provided by crystal oscillator.

- ### Temperature and Humidity Sensor
The DHT11 is a commonly used Temperature and humidity sensor that comes with a dedicated NTC to measure temperature and an 8-bit microcontroller to output the values of temperature and humidity as serial data.

- ### Soil Moisture Sensor
The moisture sensor measures the volumetric water content of the soil with the help of a sensing probe which must be put into the soil. The sensor module operates between voltages of 3.3 V to 5V.

- ### LED
Light-emitting diode (LED) is a widely used standard source of light in electrical equipment. It has a wide range of applications ranging from your mobile phone to large advertising billboards.

- ### Relay Module
A 5v relay is an automatic switch that is commonly used in an automatic control circuit and to control a high-current using a low-current signal. The input voltage of the relay signal ranges from 0 to 5V.

- ### 16X2 LCD
LCD (Liquid Crystal Display) is a type of flat panel display which uses liquid crystals in its primary form of operation. LEDs have a large and varying set of use cases for consumers and businesses, as they can be commonly found in smartphones, televisions, computer monitors and instrument panels.



