# One simple project for porting purpose

This project is to port an ESD3 example project , which is originally exported for FT90X platform by default, to STM32L4 Discovery board. 

Users can reference this project to see how to adapte an exported project by ESD3 to STM32 ARM platform. 

The main changes is in FT_Eve_Hal\FT_Gpu_Hal.c, which re-implement the transportation layer and system initialization API. 

Check Wiki for more details. 
