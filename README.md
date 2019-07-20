# STM32F0 Discovery C++

I basically followed this great Tutorial https://www.instructables.com/id/Build-a-Program-for-STM32-MCU-Under-Linux/
and setup a Project which is only compiled by running "make" in the root folder. In the process I used STM32CubeMX and Makefile4CubeMX.
As I love Visual Studio Code, I did not setup CodeBlocks IDE.

I changed main.c to main.cpp to call a sample class and had to change the Makefile to support C++.

# Tested on
Ubuntu 18.04, ARM GCC 6.3.1

# Licenses
Please note that STM32CubeMX generated files are licensed as BSD-3-Clause, more information here opensource.org/licenses/BSD-3-Clause.
    
    COPYRIGHT STMicroelectronics 2019
    
The files related to Makefile4CubeMX are licensed under Apache License, Version 2.0, more information here http://www.apache.org/licenses/LICENSE-2.0
