# TEMP non-blocking example overview 
## Overview

- Application initializes the nrfx_temp driver and starts operating in non-blocking mode (i.e. program waits until reading is taken).
- Application demonstrates the simple use of the die temperature sensor inside nRF SoCs.
- Temperature is measured until a number of measurements performed is equal to the value specified by the user
- Time to take specified amount of readings are measured and printed at the end.
- Built-in nRF HAL libs are used.
- Example or hal libs aren't created by me. Only some modification in the original sample is made for simplification and demonstration purposes.
- Original example path in Nordic NCS: modules\hal\nordic\nrfx\samples\src\nrfx_temp

## Requirements

The sample supports the following development kits:

| **Board**           | **Support** |
|---------------------|:-----------:|
| nrf52dk_nrf52832    |     Yes     |
| nrf52833dk_nrf52833 |     Yes     |
| nrf52840dk_nrf52840 |     Yes     |
| nrf5340dk_nrf5340   |     Yes     |
| nrf9160dk_nrf9160   |      No     |


> For more information, see the die temp sensor chapter in the product specification of supported SoC.


## Wiring
To run this sample, no special configuration is needed. You should monitor the output from the board to check if it is as expected.

## Building and running
To run this sample, use nRF Connect for SDK with VS Code, import this application, build and flash to your device.