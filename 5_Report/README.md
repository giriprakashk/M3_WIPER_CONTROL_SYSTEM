# Abstract
A wiper is an important component that removes rain or any other liquid from a vehicle's windscreen. The former system needed manual wiper activation, which was difficult to do. As a result, this technology is being touted as a potential solution to these issues. The project's aims are to provide wiping systems for older cars, enhance the system with actuators and pull switches (using the same switch for many purposes by stepwise switching), and control engine and wiper speed with a single switch. This system adjusts the wiper speed in response to the quantity of rain falling.The functioning speed of a vehicle wiper is controlled by a wiper speed control system in response to rain conditions. A rain sensor detects rain conditions in the control system to create. The amplitude of an analogue signal is dependent on the measured rain conditions. A converter converts the analogue sensor output to a digital pulse signal, which is then used in a digital circuit system. By digitally processing the pulse wave, a control signal is created.The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it. A wiper driver circuit receives the control signal and adjusts the operational speed or timing to match it.The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions. A converter converts the analogue sensor signal into a digital pulse signal for use in a digital circuit system.
# Introduction
In vehicles, a wiper control system uses an electronic component to replace the typical wiper blade. A single switch in the ACC position will control the ignition button (on the motor) with this design. With a second push, switch on the wiper system, then change the wiper speed with a third press, and then turn off the motor with a fourth press. LEDs and a simulation tool were used to accomplish this. A wiper is an important component that removes rain or any other liquid from a vehicle's windscreen. The former system needed manual wiper activation, which was difficult to do. As a result, this technology is being touted as a potential solution to these issues.The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions. A converter converts the analogue sensor signal into a digital pulse signal for use in a digital circuit system. The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it.
# Aim
To avoid accidents when driving in the Rain.
# Goal
Prevent accidents by creating a safe atmosphere.
In bad weather, you can see clearly.
# Features
* The car will be locked when the button is pressed ONE time.
* The car will open when the button is pressed TWO times.
* It will turn on and move clockwise after being pressed THREE times.
* It will wiper off and travel in an anticlockwise direction after being pressed FOUR times.
* The wiper will finish one cycle if the button is pressed FIVE times.
# Software Requirements
STM32 IDE
# Components
STM32F407VG Microcontroller Board.
# STM32F407VG
The STM32F405xx and STM32F407xx families are built on the high-performance Arm® Cortex®-M4 32-bit RISC processor, which runs at up to 168 MHz. All Arm single-precision data-processing commands and data formats are supported by the Cortex-M4 core's Floating point unit (FPU) single precision. It also has a memory protection unit (MPU) and a full set of DSP commands to improve application security. High-speed embedded memories (Flash memory up to 1 Mbyte, up to 192 Kbytes of SRAM), up to 4 Kbytes of backup SRAM, and an extensive range of enhanced I/Os and peripherals connected to two APB buses, three AHB buses, and a 32-bit multi-AHB bus matrix are all included in the STM32F405xx and STM32F407xx families.
# Features Of STM32F407VG
* Flash memory of up to 1 megabyte.
* OTP memory of 512 bytes.
* Compact Flash, SRAM, PSRAM, NOR, and NAND memories are supported by this flexible static memory controller.
* Sleep, Stop, and Standby modes are low-power modes.
* 16-stream DMA controller with FIFOs and burst support for general-purpose DMA.
* Up to 54 Mbytes/s 8- to 14-bit parallel camera interface.
* Generator of true random numbers.
* Hardware calendar, CRC calculating unit, 96-bit unique ID RTC, subsecond accuracy.
# Applications of STM32F407VG
* These are some of the most notable STM32F407 applications, which are detailed here.
* It's employed in a variety of control applications, including motor control.
* It's also employed in medical devices.
* This module is utilised in a variety of industrial applications, such as PLC controllers.
* This gadget is utilised in printing and scanning equipment.
* This gadget is also utilised in heat ventilation, air conditioning, and security systems.
* This module can be found in a variety of household products.
# Working Principle
Assume the microcontroller is the vehicle. When the button is pressed, the first led (red) turns on, the wiper starts, and the second led (blue) turns on at the appropriate pace. The third led (green) will turn on if the button is pressed again, and the wiper speed will be increased in contrast to the previous one. The fourth press will activate the fourth led (orange) and raise the wiper speed in line with the previous one. After the fifth click, the microcontroller (vehicle) is turned off.The wiper blades on your windshield are in charge of keeping it clean. They function like a squeegee, wiping water, snow, wiper fluid, and other liquids or debris off the windshield in a back-and-forth motion. An electric motor drives the wipers on the windshield. The wiper arms are moved by an electric motor connected to a worm gear that provides the necessary force to a long rod. The worm gear can create the force needed to move the wipers at their maximum speed. The arms control the actual wiper blades on the windshield. The rubber blades must provide sufficient pressure to the windscreen to remove all moisture without leaving streaks.
# Uses
* Effective dirt, water, and snow removal.
* Operation between 243 and 353 degrees Celsius.
* Passing the stall and snow load tests.
* Around 1500 000 wipe cycles throughout service life.
* Corrosion resistance to acids, alkalis and ozone.
# Advantages
* The wiper cleans the front and rear windshields of the automobile.
* The wiper system's principal goal is to keep the windscreen clean enough to enable adequate view at all times.
* Wiper cleans the windshield by removing oil, dust, moisture, and grime that have become attached.
* It enables passengers to travel in safety and elegance.
# Disadvantages
* Water or ice consumption might cause hinges to become immovable.
* Wiper frames have not been updated and are rusted, making an equal wipe as the blades pass over a curved windshield impossible.
* It is corrosion susceptibility.
* The wiper blades will be damaged if the snow or ice is not removed.
# Scope
* The use of this redesigned wind screen wiper reduces human effort, eliminates wear adjustment.
* It is a simple operating principle, all of which were issues with the previous wind screen wiper.
* This sort of mechanism ensures that drivers may concentrate on their primary responsibility of driving.
* Engineers are now looking towards completely automated systems that adjust the wiper blade speed based on the rate of rainfall and the vehicle's speed.
# Limitation
* The windshield's surface is damaged (chip/crack), contains debris, or is waxed or treated with a glass treatment.
* The wiper arm is misaligned, and the blade should be at a 90-degree angle to the windshield. Attempting to run frozen wipers might cause this.
* Blades that have not been inserted properly may flop/wiggle freely when operating, resulting in irregular wipes.
* Wipers are worn out. Blades will wear/dry out as a result of exposure to the sun, heat, cold, time, debris, and use.
* Leaving the rubber edge protectors on the blades during installation.
# SWOT Analysis
![image](https://user-images.githubusercontent.com/101519714/168157929-b73db80f-8024-45f5-a0d7-5569bddf8277.png)
# 4 W&H (What,Why,Who,When,How)
![image](https://user-images.githubusercontent.com/101519714/168166028-e789ff4d-823c-4163-881c-7924025f4d4d.png)
# Requirements
## High Level Requirements
ID | Description | Status
-- | -- | --
HR_01 | It will LOCK the vehicle. | Implemented
HR_02 | It will unlock the vehicle. | Implemented
HR_03 | It will turn on the wiper system. | Implemented
HR_04 | It will turn off the wiper system. | Implemented
## Low Level Requirements
ID | Description | Status
-- | -- | --
LR_01 | ON LED RED - if the button is pushed ONCE. | Implemented
LR_02 | OFF RED LED - if the button is pushed TWICE | Implemented
LR_03 | ON BLUE,GREEN,ORANGE LEDS - if the button is pushed THREE TIMES | Implemented
LR_04 | ON ORANGE, GREEN, and BLUE LEDS - if the button is pushed FOUR times | Implemented
# Diagram
## Block Diagram
![image](https://user-images.githubusercontent.com/101519714/168298001-2a4df5e1-0bcf-4cb4-b70b-53254c53596d.png)
## Flow Chart
![image](https://user-images.githubusercontent.com/101519714/168226528-0dcfcbec-9ef9-4bd9-aaac-e9df9dba1f7d.png)
## Data Flow Diagram
![image](https://user-images.githubusercontent.com/101519714/168229964-cfbc1919-6c60-48f9-b2c8-08541dc14543.png)
## Class Diagram 
![image](https://user-images.githubusercontent.com/101519714/168235684-2b319b28-f5c9-4c5d-87f0-e4c31df2f106.png)
## State Transmission Diagram 
![image](https://user-images.githubusercontent.com/101519714/168292145-a6e651b5-2e4e-49a3-a9c2-40bb7c4b25d6.png)
# Test Cases and Corresponding Output
## High Level Test Cases 
Test ID |	Description |	Exp.i/p |	Exp.o/p |	Actual o/p |	STATUS
-- | -- | -- | -- | -- | --
1	| check if the Button is pressed |	program execution |	Microcontroller/Engine starts  |	LED ON(RED) |	PASS
2 |	check if the Button is pressed |	program execution	| Wiper starts	| LED ON(BLUE)   | PASS
3 |	check if the Button is pressed	| program execution	| Wiper starts	| LED ON(GREEN)	 | PASS
4 |	check if the Button is pressed |	program execution | Wiper starts	| LED ON(ORANGE) | PASS
5	| check if the Button is pressed	| -	| Microcontroller/Engine stops	| LED TURNED OFF | PASS
## Low Level Test Cases 
Test ID |	Description |	Exp.i/p |	Exp.o/p |	Actual o/p |	STATUS
-- | -- | -- | -- | -- | --
1	| check if the Button is pressed |	program execution |	Microcontroller/Engine starts  |	LED ON(RED) |	PASS
2 |	check if the Button is pressed again |	program execution	| Wiper starts and speed of wiper is low	| LED ON(BLUE)   | PASS
3 |	check if the Button is pressed	again | program execution	| Wiper starts and speed of wiper is medium	| LED ON(GREEN)	 | PASS
4 |	check if the Button is pressed again |	program execution | program execution Wiper starts and speed of wiper is good	| LED ON(ORANGE) | PASS
5	| check if the Button is pressed	again | -	| Microcontroller/Engine stops	| LED TURNED OFF | PASS
# Images
## OFF State
![image](https://user-images.githubusercontent.com/101519714/168459632-817562d1-1f53-4530-aa82-5c42aab027eb.png)
## ON State
## 1.Press Button and Hold for 2 Seconds
![image](https://user-images.githubusercontent.com/101519714/168273912-2ee9f058-4e27-46b6-be87-c71e53cc8db7.png)
## 2.Wiper Speed is Low
![image](https://user-images.githubusercontent.com/101519714/168459522-852345c2-6d58-497a-a073-ffac58465b2c.png)
## 3.Wiper Speed is Medium
![image](https://user-images.githubusercontent.com/101519714/168274417-b0699cfb-aa55-4544-80c9-5a14c9c1ab7b.png)
## 4.Wiper Speed is High
![image](https://user-images.githubusercontent.com/101519714/168274568-f1098d57-7804-43a3-b54e-762a1bdbb5b1.png)
## 5.Press Button and Hold for 2 Seconds(OFF State)
![image](https://user-images.githubusercontent.com/101519714/168275143-250917bd-5111-4363-8d8e-38aa0830bd8b.png)
## Wiper_Control_System
![wiper_control_system](https://user-images.githubusercontent.com/101519714/168275703-7066dbf6-32c3-4e1c-a99a-a8840f259d37.png)
# Video
## Wiper Control System
https://user-images.githubusercontent.com/101519714/168473384-0f0fec80-8bcd-41b4-ac8e-948fbeed768c.mp4

