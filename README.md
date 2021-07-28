# Over-Voltage-Protection-System-for-Industrial-Loads-using-STM32-microcontroller
This is repository of our EEE 416 course project. In this repository, we organized our project files including all the necessary codes, simulation and PCB files. 

In this project, the source voltage is stepped down and then rectified to feed into STM's analog pin. Single or multiple thresholds can be set using some calibration methods. If the converted source voltage somehow exceeds the threshold of overvoltage then the STM will send proper digital signal to the driving darlington pair transistor at the load side. Darlington pair forces the relay to trip and disconnects connection between load and overvolteged power supply. By this simple process, we can make it for multiple loads and printing a PCB of it may turn it into a compact circuit protection device.

# Demonstration video
https://www.youtube.com/watch?v=6UFyhoZj2CA

# Working principle
TODO (see presentation slide for details)

# Contents
1. Project presentation slide
2. Video link of presentation
3. Simulation files in proteus
4. PCB design file in proteus
5. STM codes in CubeIDE

# Getting Started (Simulation)
1. Firstly open the simulation [file](EEE416_J2021_P10/adc.pdsprj) from proteus.
2. Upload code [hex](EEE416_J2021_P10/ADCconversion4/Debug/ADCconversion4.hex) file generated from cubeIde to the STM32 in proteus.
3. Click the simulation button which will start immediately.
4. (PCB) To generate pcb files we need to open proteus [file](adc_final_pcb.pdsprj) and you will find developed pcb version of it.

# Used Software
1. Proteus 10.1
2. STM32CubeIDE 1.6.1

