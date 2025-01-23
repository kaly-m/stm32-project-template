To use this Template (with STM32CubeIDE):

- Create a copy of this folder and rename it 'The_Name_Of_Your_Project'.
- replace all occurrences of 'my_project' to 'The_Name_of_Your_Project' in the following files:
.cproject and .project

The project is ready to use according to STM32CubeIDE_1.14.1 standards.

*************************************************************************
$ SPECS $

PROJECT STRUCTURE TYPE (** are source folders !!)

** /app folder will be used to put application-level source files:
    - /inc for headers (.h)
    - /src for functions implementation (.c)
    
** /bsp (board support package) folder will used to put driver-level source files used for peripherals initialization and board-related low-level functions:
    - /inc for headers (.h)
    - /src for functions implementation (.c)

** /cmsis folder will be used to put STM32 device drivers(Cortex Microcontroller Software Interface Standard):
    - /core for CMSIS headers
    - /device/inc for device headers
    - /device/src for device startup source code
