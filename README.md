# PCB_PROJECT_3_CUSTOM_ATMEGA328P_BOARD

Hello there! Welcome to my third PCB design project, where I have created a custom ATMEGA328p board optimized for IoT applications that require extensive data logging. 
Unlike standard boards like the Arduino Uno, this board is designed to handle large datasets, making it ideal for applications like monitoring systems that collect continuous data over time. 
Equipped with a Real-Time Clock (RTC) module, this board enables precise time-stamped data collection.

Project Overview:  Board Layers:   The board can be designed with either 2 layers or 4 layers. Although the board can be designed using 2-layer, I experimented with a 4-layer design due to the complexity and number of connections in this project. Memory and Interfaces: The board features 2MB of memory and supports both I2C and UART interfaces, with dedicated pins for each. It also includes 7 GPIO (digital) pins for additional functionality. Programming: The board can be programmed using the onboard ICSP pins. Power Supply: The board can be powered using an external power supply through the pins marked "Battery" (please refer to the ATMEGA328p datasheet for maximum input voltage specifications).

Features:  IoT Benefits: Designed specifically for IoT projects, this board allows for more data logging compared to standard boards like the Arduino Uno. It provides extensive functionalities ideal for IoT applications, except for ADC (Analog to Digital Conversion). Real-Time Clock (RTC): The onboard RTC module enables precise time-stamped data collection, which is crucial for continuous monitoring and data analysis.
  
  
Note: The board does not support any analog pins and the internal ADC of the ATMEGA328p is disabled.


**Repository Structure** Branches:main: General overview. 2Layer:Files and details specific to the 2-layer design. 4Layer: Files and details specific to the 4-layer design.
Feel free to explore the files in each branch to see the different design styles.

Note: You are currently viewing the main branch of this repository.
