# Exercise 3.a
**Investigate project board**

Look at the documents for the board you are considering for your final project (or any ST Discovery Board), draw the hardware block diagram for the board. For peripherals, note the communication paths (SPI, I2C, etc).

Look at the datasheet for the processor and other documents. Answer these questions: 
- What kind of processor is it?
- How much Flash and RAM does it have? Any other memory types? 
- Does it have any special peripherals? (List 3-5 that you noted as being interesting.) 
- Does it have a floating point unit?
- If it has an ADC, what are the features?
- Look at one application note for this processor.

**Board: B-L475E-IOT01A**

![image](https://user-images.githubusercontent.com/18359133/144717758-8b5c2ce2-af08-495f-a844-82fdac82869e.png)

1. Processor: STM32L475VG based on ARM® Cortex®-M4 core in LQFP100 package
2. Memory: 1 Mbyte of Flash memory and 128 Kbytes of SRAM, 64-Mbit Quad-SPI (Macronix) Flash memory
3. Peripherals: 
   1. 2× 12-bit ADC 5 Msps, up to 16-bit with hardware oversampling, 200 μA/Msps
   2. 2x 12-bit DAC, low-power sample and hold
   3. 2x operational amplifiers with built-in PGA
   4. 2x ultra-low-power comparators
4. single precision Floating point unit
5. 12-bit ADC 5 Msps, up to 16-bit with hardware oversampling, 200 μA/Msps
6. Application Note: capture an audio signal from an analog microphone and convert it into the numeric domain using the STM32L4 OPAMP and ADC peripherals
![image](https://user-images.githubusercontent.com/18359133/144717879-cb212a4d-93ea-4308-a4c7-7d97c83411ae.png)


