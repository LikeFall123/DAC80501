# DAC80501
Interfacing a DAC80501 digital-analog converter with an STM32F407 MCU

This is a simple project for a STM32F407 MCU to interface with the DAC80501 digital-analog converter.
The MCU is programmed to use SPI with DMA to send data to the DAC. For using this DAC, it should follow the required design recommendations on your PCB.

The required pins are configured for the CLK, MOSI, CS lines (see the .ioc STMCubeMX file).\
The repository contains the project for STMCudeIDE and the EWART project for IAR Embedded Workbench IDE.
