# templogger-db

![cover image](https://raw.githubusercontent.com/arduinocelentano/templogger-db/main/intro.jpeg)

These small devices are used to track the temperature of sensitive materials (like medicine, food etc.) during a transportation. They are usually single-use devises and considered to be e-waste as soon as a cargo container is delivered. Yes, imagine thousands of trucks all around the world delivering thousands of boxes with implanted little pieces of hardware destined to become a heap of e-waste just after few days of operating. I disassembled several samples and found out that some of them might be reprogrammed and repurposed with a little bit of reverse engineering.

In average, what you get is a well-assembled power-optimized board with a genuine 32-bit Cortex M3 or M4 microcontroller, RTC, temperature sensor, a couple of buttons and LEDs, LCD screen and USB support. On some boards GPIO pins are accessible, so it might be possible to extend their capabilities. 

A brief database of temperature loggers repurposing capabilities
For further details check out [this](https://hackaday.io/project/191592-arm-devboard-from-a-used-up-temperature-logger) project.

| Model | Performance | Peripherals | Hackability | Officially reusable | Could be used as a devboard | MCU | LCD | External Flash | External EEPROM | Plastic Case | Battery | What else could be salvaged |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [TSS TempTracer Cradle 2](https://tss.se/wp-content/uploads/2018/12/TSS-TempTracer-Cradle-2_PRD_TDS_005-Ver-A.pdf) | ★★★ | ★☆☆ | ★☆☆ | ❌ | Probably | [ATSAM4S16](https://www.microchip.com/en-us/product/atsam4s16b) | ❌ | ❌ | ❌ | Reusable | Coin cell | ❌ |
| [Q-tag CLm doc](docs/Q-tag_CLm_doc/overview.md) | ★☆☆ | ★★☆ | ★★★ | ❌ | ✓ | [STM32L152RCT6A](https://eu.mouser.com/datasheet/2/389/stm32l151qc-1851375.pdf) | ✓ | ❌ | ❌ | Reusable | Coin cell | ❌ |
| [ TempTale 4 USB](docs/TempTale4USB/overview.md) | ★★☆ | ★★★ | ★☆☆ | ❌ | Probably | [ATSAM4S4B](https://www.microchip.com/en-us/product/atsam4s4b) | ✓ | ATMLH414 | Winbond25x40 | Reusable | Lithium ER14250 | ❌ |
| [TempTale Ultra](docs/TempTale_Ulrta/overview.md) | ★☆☆ | ★★☆ | ★★☆ | ❌ | ✓ | [STM32L152RCT6A](https://eu.mouser.com/datasheet/2/389/stm32l151qc-1851375.pdf) | ✓ | ❌ | Winbond25x40 | Reusable | Lithium coin cell | ❌ |
