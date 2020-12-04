# Fast Fourier transform using microphone in STM32f746g-DISCOVERY
## Introduction
  ![](https://i.imgur.com/O3oZoqj.png)
## Functions
1. Read the digital microphone signal and display the signal on the horizontal axis of the screen:Between 0~130.
2. Digital microphone sampling frequency setting 8kHz.
3. FFT the digital microphone signal and display it on the horizontal axis of the screen:Between 140~270.
4. The frequency display range is 0~4kHz.
5. When you touch the microphone signal axis screen, you can start or stop reading Microphone signal.
6. When the FFT frequency axis screen is touched by hand, the frequency number is displayed in the upper right corner Value and power.
## Video
  [![Fast Fourier transform using microphone in STM32f746g-DISCOVERY](https://i.imgur.com/eCPdes8.png)](https://www.youtube.com/watch?v=NJCQbo03_Y8)
## Environment
  - EVB:  STM32f746g-DISCOVERY    
  - IDE:  keil5 with MXcube  
## How to use it?
  - download keil and compiler project
  - load into the STM32f746g-DISCOVERY 
## Other
  The fft part is not accurate. If you want to use the suggested correction.
## License
[MIT License](https://opensource.org/licenses/MIT)
