# Zest_Core_STM32L562VE

[Zest_Core_STM32L562VE](https://6tron.io/zest_core/zest_core_stm32l562ve_1_0_0) board support for Zephyr OS.

## Dependencies

This module depends on:
- [6TRON connector definition](https://github.com/catie-aq/zephyr_6tron-connector)

## Supported Features

The Zephyr Zest_Core_STM32L562VE board configuration supports the following hardware features:

| Interface | Controller                                                                  | Driver/Component                               |
| :-------- | :-------------------------------------------------------------------------- | :--------------------------------------------- |
| ADC       | on-chip                                                                     | adc                                            |
| AES       | on-chip                                                                     | crypto                                         |
| CLOCK     | on-chip                                                                     | clock_control                                  |
| DAC       | on-chip                                                                     | dac                                            |
| DIE_TEMP  | on-chip                                                                     | sensor                                         |
| DMA       | on-chip                                                                     | dma                                            |
| EXTI      | on-chip                                                                     | interrupt_controller                           |
| FLASH     | on-chip                                                                     | flash                                          |
| GPIO      | on-chip                                                                     | gpio                                           |
| I2C       | on-chip                                                                     | i2c                                            |
| LPTIM     | on-chip                                                                     | timer                                          |
| LPUART    | on-chip                                                                     | serial                                         |
| NVIC      | on-chip                                                                     | arch/arm                                       |
| PINCTRL   | on-chip                                                                     | pinctrl                                        |
| QSPI      | on-chip                                                                     | qspi, flash                                    |
| RNG       | on-chip                                                                     | entropy                                        |
| RTC       | git push -u origin mainon-chip                                                                     | rtc                                            |
| SDMMC     | on-chip                                                                     | disk                                           |
| SMBUS     | on-chip                                                                     | smbus                                          |
| SPI       | on-chip                                                                     | spi                                            |
| TIMER     | on-chip                                                                     | counter, pwm, timer                            |
| UART      | on-chip                                                                     | serial                                         |
| USART     | on-chip                                                                     | serial                                         |
| USB       | [FT232RQ](https://ftdichip.com/products/ft232rq/) | console                                        |
| USBOTG_FS | on-chip                                                                     | usb                                            |
| VBAT      | on-chip                                                                     | sensor                                         |
| VREF      | on-chip                                                                     | sensor                                         |
| IWDG      | on-chip                                                                     | watchdog                                       |
| WWDG      | on-chip                                                                     | watchdog                                       |

See [STMicroelectronics vendor bindings](https://docs.zephyrproject.org/latest/build/dts/api/bindings.html#dt-vendor-st) for additional information.

## Usage

1. Add the Zest_Core_STM32L562VE board to your workspace using the [6TRON module](https://github.com/catie-aq/zephyr_6tron-manifest.git).
2. Compile and flash application using `west` tool:
   - Board name: `zest_core_stm32l562ve`
