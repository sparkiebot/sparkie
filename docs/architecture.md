
# Architecture

Sparkie although being a really simple robot, is composed of many different components that work together to make it work.
Essentially, the making of Sparkie has these ingredients:
- 3D Printing
- Embedded Board
- Jetson Orin
- Software

## 3D Printing

All the parts are designed to be 3D printed. 
In my particular setup I used a stock Ender 3 KE with 220x220x250mm build volume, so any printer with similar or larger build volume should work.
It will require some time, depending on the printer and the settings you choose.

Sparkie is divided into 3 main parts:
- The bottom part, which contains the motors and the battery
- The middle part, which contains the Jetson Orin and the custom board, and the sensors
- The top part, which contains the camera and the lidar 

The middle and the bottom part are divided in 4 parts each, to make it easier to print and assemble.
The top part is divided in 2 parts instead.

For more information on how to print the parts, check the [3D Print Repository](https://github.com/sparkiebot/3d_print) file.

## Embedded Board

Every Sparkie's sensor and actuator is controlled by custom board based on Raspberry Pico. The board is designed to be easy to assemble and to be as compact as possible.
This board needs to be printed using a PCB manufacturer, and then assembled by soldering the components on it.
After that, you will need to flash the firmware on the board.

To learn more about the custom board, check the [Custom Board Repository](https://github.com/sparkiebot/board).
If you want to know how to flash the firmware on the board, check the [Sparkie Firmware Repository](https://www.github.com/sparkiebot/sparkie_fw).

## Software

The Jetson Orin Nano is the brain of Sparkie. It is responsible for processing the camera data, controlling the motors, and running  most of the algorithms.
Before being able to use board, you will need to flash Jetson Linux on it, and install all the necessary libraries and dependencies.
After that, you will need to install the Sparkie software on it.

For more information on how to setup the Jetson Orin, check the For more information on how to install the software, check the [Software docs](/docs/software.md).

