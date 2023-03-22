# frequency response analysis prj 
## introduction
This is a demo script for testing frequency response on STM32/ARM M7 cortex.
This is to replace spectrometry device with low-cost MCU/dev. board during pruction test. 
## feature
* adjustable nyquist frequency to max. 2000Hz (per max. ctrl freqency)
* adjustable sampling rate frequency range and test cycle in eqch freq. 
* precise sampling period with high priority IT
* high throughput and little data trasmissin, by simplified FFT/DFT cal. inside MCU  
* one-to-two is applicable for bare metal version (one-to-three by RTOS is under dev.)

## test flow design
![alt text](https://github.com/Wowowdog/demo-frequency-response-prj/blob/master/png/ctl1.png?raw=true)

## output snippet
![alt text](https://github.com/Wowowdog/demo-frequency-response-prj/blob/master/png/mag1.png?raw=true)

