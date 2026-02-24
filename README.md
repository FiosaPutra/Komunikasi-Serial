Kerjakan program ESP32_UART


kerjakan program ESP32_I2C: Master_I2c dan Slave_I2C

## KOnfigurasi STM32 di STM32 CubeIDE:

* ➡️ UART TX & RX (echo)
* ➡️ STM32CubeIDE + HAL
* ➡️ USART1 (PA9 / PA10)
* ➡️ Interrupt (recommended)

* MCU: STM32F103C8Tx;
* USART1 → Asynchronous;
* Baudrate: 115200;
* Mode: TX & RX;
* Clock: default (HSI OK)

Connectivity → USART1 → Asynchronous

### Di USART1 Configuration:
* Baudrate: 9600 / 115200
* Word length: 8 Bits
* Parity: None
* Stop bit: 1

Mode: TX & RX
