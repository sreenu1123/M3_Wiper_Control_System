## M3_WIPER_CONTROL_SYSTEM
This project can benefit from the addition of a speed-controlling mechanism, which will allow it to operate in accordance with the intensity and speed of the water flowing through the sensor. The fundamental manoeuvring is done merely to make it more cost-effective and reliable in the long run.
The idea i have been implemented is completly in working condition these can be used in any type of cars.We can also make this wiper system automatic by adding sensors for rain water falling on the wind shiled,dust resistance sensor,etc.So,there is no need to control the wiper system manually while driving the car.It can be more convinient we add the additional features to the wiper system and it can be done in near future.People around the world still working on this project so that we can make  a system that works requires less human intervention.


# COMPONENTS AND SUPPLIES:
1.STM32F407 Discovery Board
2.LEDs
3.Push Button
4.Resistors
5.Power Supply

# ADVANTAGES:
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* It is quite simple to use.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* Individual rain sensors are fairly inexpensive.
* Rain sensor-based systems are extremely simple to install.
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.

# DISADVANTAGES:
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.
* The entire system cost rises when more components, including a rain sensor, are required.
* When water falls squarely on the rain sensor, the mechanism activates.

# 4W & H (WHO,WHAT,WHEN,WHERE,HOW):

# WHAT:
* The functional speed of a vehicle wiper is constrained by a wiper speed control instrument in view of downpour conditions. To produce, the control framework consolidates a downpour sensor (30) that identifies downpour conditions. The adequacy of a simple sign relies upon the identified downpour conditions.

# WHY:
* To keep the windscreen clean enough to give adequate view at all times. 
* The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.

# WHO:
* A wiper speed control system for an automobile manages the wiper's functioning speed in response to weather conditions.

# HOW:
* You can adjust the speed of the car wiper system according to the rainfall.


# SWOT ANALYSIS:
# STRENGTH:
* Good Reputation
* Big Influence on the Market
* High Bargaining Power Supliers
* Low Budget

# WEAKNESS:
* Week Focus on Process Innovations
* High Transaction Cost
* Structural Inertia
* No Focus on Private Sector

# OPPRONUTIES:
* Technological Lock in of Product
* Technological Development
* Demand for Saver Equipments
* Emerging New Markets

# THREATS:
* Highly REgulated Industry
* Ethical Pressure
* Low Bargaining Power Buyers
* Econimical Crisis

# Exploring STM32F407 Discovery Board:
![image](https://user-images.githubusercontent.com/101699116/168215005-061df6d3-4596-4639-8eea-13b069ee27cb.png)
This venture gives practically all the fundamental data expected to begin with STM32F407 Discovery Board and furthermore advancement of driver code.
* Hardware Used : STM32F4 DISCOVERY kit, for more information visit: STM32F4 DISCOVERY
* Software Tool : STM32cubeIDE, for more information visit: STM32CubeIDE
* For installation of STM32CubeIDE refer Youtube
* Note : As this microcontroller has many advanced features and the main aim of this project is to get all basic insights, during the driver development only the required functionalities are added and other advanced functionality is not added. I may update the driver and other functionality in the future.
Please find the STM32F4 Discovery User Manual,STM32F4xxx Reference Manual (RM0090) and other related documents inside a folder called Documents. I will be referring to these documents for information such as block diagrams, register details ect.

# Overview of STM32F407VGT6 Microcontroller:
![image](https://user-images.githubusercontent.com/101699116/168215163-99ec0ff2-693d-4425-8061-783fa20e6fb0.png)
The STM32F407 Discovery board utilizes STM32F407VGT6 Microcontroller which has ARM Cortex-M4F Processor, which is fit for running upto 168Mhz. This MCU has numerous peripherals, for example, GPIO ports, TIMERS, ADCs, DACs, Flash Memory, SRAM, SPI, UART ect. The processor and peripherals talk by means of BUS-Interface. There are three transports accessible

I-BUS (Instruction Bus) D-BUS (Data Bus) S-BUS (System Bus) I-BUS This transport interfaces the Instruction transport of the Cortex®-M4 with FPU(Floating point unit) center to the BusMatrix. This transport is utilized by the center to bring directions. The objective of this transport is a memory containing code (inward Flash memory/SRAM or outer recollections through the FSMC/FMC).

D-BUS This transport associates the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM information RAM to the BusMatrix. This transport is utilized by the center for strict burden and troubleshoot access. The objective of this transport is a memory containing code or information (inward Flash memory or outer recollections through the FSMC/FMC).

S-BUS This transport interfaces the framework transport of the Cortex®-M4 with FPU center to a BusMatrix. This transport is utilized to get to information situated in a fringe or in SRAM. Directions may likewise be brought on this transport (less productive than ICode). The objectives of this transport are the inward SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the outside recollections through the FSMC/FMC.

So guidelines and information use I-transport and D-transport individually, All the other fringe utilizes System transport. The Cortex-M4 processor contains three outside Advanced High-execution Bus (AHB)- Lite transport connection point and one Advanced Peripheral Bus (APB) interface. The GPIOs are associated with AHB1 transport which has a most extreme speed of 150Mhz and is isolated into two transports as APB1 and APB2. APB1 runs at 42Mhz(max) and APB2 runs at 82Mhz(max). The various peripherals like SPI, UART, TIMERs, ADCs, DACs, and so on are associated with either APB1/APB2 transports. Also, the AHB2(168Mhz max) is associated with Camera and USB OTG interfaces, AHB3 is associated with External memory regulator.

# OUTPUT IMAGES:
1.user button and hold it for two seconds
![image](https://user-images.githubusercontent.com/101699116/168215381-5ecc8142-9d24-4736-8735-bc312903aa7d.png)

2.WIPER SPEED LOW
![image](https://user-images.githubusercontent.com/101699116/168215423-e3d86028-68c5-47ce-aecc-96c930a879df.png)

3.WIPER SPEED MEDIUM
![image](https://user-images.githubusercontent.com/101699116/168215452-9ec26809-fa7a-445d-a48c-f0a421172afe.png)

4.WIPER SPEED IS HIGH
![image](https://user-images.githubusercontent.com/101699116/168215482-7f1316c6-23bf-4b6a-ad76-59bd2606e306.png)


5.user button is pressed and held for 2 seconds, the red LED is off
![image](https://user-images.githubusercontent.com/101699116/168215572-07fc1962-aa78-46a6-a1e3-71e4326f809d.png)
