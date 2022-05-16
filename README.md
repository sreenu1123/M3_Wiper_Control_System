# M3_Wiper_System_Control

![Car-Wiper-Blades](https://user-images.githubusercontent.com/101027579/168482827-1f45bc7a-4cae-47ac-9df9-2db20c11d790.png)
m3_WiperControlSystem

# BADGES
* Codiga - Static Analysis
[![Quality](https://api.codiga.io/project/33313/score/svg)]
* Code quality
[![CodeQL](https://github.com/Stephenj071/M3_Wiper_Control_System/actions/workflows/c-ccpp.yml/badge.svg?branch=main)](https://github.com/Stephenj071/M3_Wiper_Control_System/actions/workflows/c-ccpp.yml)
* Codacy
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/448550b5b1694c37920db27d3267b6c4)](https://www.codacy.com/gh/Stephenj071/M3_Wiper_Control_System/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Stephenj071/M3_Wiper_Control_System&amp;utm_campaign=Badge_Grade)
* Build on Linux
[![Build-Linux](https://github.com/Stephenj071/M3_Wiper_Control_System/actions/workflows/buildonlinux.yml/badge.svg?branch=main)](https://github.com/Stephenj071/M3_Wiper_Control_System/actions/workflows/buildonlinux.yml)


### WORKING PROCESS
* When the button is pressed ONCE, the car will be on ACC mode.

* When the button is pressed TWICE, the car will be on Ignition mode.

* When the button is pressed THREE times, wiper turn on.

* When the button is pressed FOUR times, wiper turn off.


# Requirements
## High level requirements
| ID | Discription | status |
| --- | --- | --- | 
| HR_01 |	Car is in ACC mode |	Implemented |
| HR_02 |	Car is in Ignition mode |	Implemented |
| HR_03 |	Wiper turned on |	Implemented |
| HR_04 |	Wiper turned off |	Implemented |
## Low level requirements
| ID |	Discription |	status |
| --- | --- | --- | 
| LR_01 |	Button pressed ONCE for two seconds - ON LED RED |	Implemented |
| LR_02 |	Button pressed once again times - OFF LED RED |	Implemented |
| LR_03	|Button pressed two time - ON BLUE,GREEN,ORANGE |	Implemented |
| LR_04 |	Button pressed again for two seconds - OFF ORANGE,GREEN,BLUE |	Implemented |

