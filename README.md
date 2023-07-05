# templogger-db

![cover image](https://raw.githubusercontent.com/arduinocelentano/templogger-db/main/intro.jpeg)

These small devices are used to track the temperature of sensitive materials (like medicine, food etc.) during a transportation. They are usually single-use devises and considered to be e-waste as soon as a cargo container is delivered. Yes, imagine thousands of trucks all around the world delivering thousands of boxes with implanted little pieces of hardware destined to become a heap of e-waste just after few days of operating. I disassembled several samples and found out that some of them might be reprogrammed and repurposed with a little bit of reverse engineering.

In average, what you get is a well-assembled power-optimized board with a genuine 32-bit Cortex M3 or M4 microcontroller, RTC, temperature sensor, a couple of buttons and LEDs, LCD screen and USB support. On some boards GPIO pins are accessible, so it might be possible to extend their capabilities. 

A brief database of temperature loggers repurposing capabilities
For further details check out [this](https://hackaday.io/project/191592-arm-devboard-from-a-used-up-temperature-logger) project.

| Model | Performance | Peripherals | Hackability|
| --- | --- | --- | --- |
| [TSS TempTracer Cradle 2](docs/TSS_TempTracer_Cradle_2/overview.md) | ★★★ [ATSAM4S16](https://www.microchip.com/en-us/product/atsam4s16b) | ★☆☆ None | ★☆☆ Maybe |
| [Q-tag CLm doc](docs/Q-tag_CLm_doc/overview.md) | ★☆☆ [STM32L152RCT6A](https://eu.mouser.com/datasheet/2/389/stm32l151qc-1851375.pdf) | ★★☆ LCD | ★★★ Yes |
| [ TempTale 4 USB](docs/TempTale4USB/overview.md) | ★★☆ [ATSAM4S4B](https://www.microchip.com/en-us/product/atsam4s4b) | ★★★ LCD, ATMLH414, Winbond25x40 | ★☆☆ Maybe |
| [TempTale Ultra](docs/TempTale_Ulrta/overview.md) | ★☆☆ [STM32L152RCT6A](https://eu.mouser.com/datasheet/2/389/stm32l151qc-1851375.pdf) | ★★☆ [LCD](https://cdn.hackaday.io/files/1915928197072128/temptale-ultra_LCD.pdf), Winbond25x40 | ★★☆ [Yes](https://hackaday.io/project/189442-temptale-ultra-teardown-repurpose) |
| Testo 184 T3 | ★★★ [MK40DN512VLK10](https://www.nxp.com/part/MK40DN512VLK10) | ★★☆  LCD, [adesto2106 25df321A](https://www.renesas.com/us/en/document/dst/at25df321a-datasheet) | ★☆☆ Maybe (but no point) |
