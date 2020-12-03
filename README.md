# Fast Fourier transform using microphone in STM32f746g-DISCOVERY
## Introduction
  ![](https://i.imgur.com/D3iZ376.png)
## Functions
  - USER LED OFF after booting
  - After pressing the USER BUTTON, the USER LED flashes at a speed of 1 hz, and COM
Port and LCD screen send out the string "LED FLASH =1/r/n".
  - After pressing the USER BUTTON again, the USER LED is OFF and stops blinking.COM Port and LCD screen send the string "LED FLASH =0/r/n".
  - Press USER BUTTON to interactively control whether the USR LED flashes or not.
  - COM Port parameters: 9600 bps, 8 Bit data, None parity, 1 stop Bit
## Video
  [![Using button control LCD/LED in STM32f746g-DISCOVERY](https://i.imgur.com/3ptjGlu.jpg)](https://youtu.be/cr1C7mOcJQ0)
## Environment
  - EVB:  STM32f746g-DISCOVERY    
  - IDE:  keil5 with MXcube  
## How to use it?
  - download keil and compiler project
  - load into the STM32f746g-DISCOVERY 
## Other

## License
[MIT License](https://opensource.org/licenses/MIT)
