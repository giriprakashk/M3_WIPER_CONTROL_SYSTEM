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
