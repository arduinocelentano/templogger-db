# TempTale Ultra

## Official Specifications

It was manufactured by [Sensitech](https://www.sensitech.com), a US supply chain visibility company. The exact model is TempTale Ultra. The official info could be found [here](https://www.sensitech.com/en/media/TTUItra_LS_060820_Web_tcm878-133104.pdf).

## Is it officially re-usable? 

No,they sell them as single-use devices. The [official FAQ](https://www.sensitech.com/en/support/faqs/) tells that 
>Can I reuse or reprogram a temperature indicator?
>No. Temperature indicators are simple, convenient, cost-effective, single-use electronic monitoring devices, programmed with a customer-specific profile during the manufacturing process. The devices are designed for limited operation life and are not reprogrammable.

I found out that in 2009 Sensitech launched the [recycling program](https://www.fleetowner.com/refrigerated-transporter/refrigerated-vehicles-equipment/article/21221909/sensitech-green-solutions-means-recycling-for-recorders): 

>To encourage participation at receiving locations, Sensitech will
provide display posters to those requesting them.

Apparently it was not encouraging enough since people constantly sell used items on eBay and other platforms. So this completely operational hardware considered to be e-waste.

## Is it possible to use it as a devboard? 

Definitely yes. There are pads on the PCB for standard SWD interfaceand some GPIO. Alternatively, you could salvage some useful items like Flash chip, battery and LCD. You might want to use LCD pads to
solder some external modules. After writing this post I found out that [[zvodd]](https://hackaday.io/zvodd) even made a PlatformIO file for this board. Check out their [post](https://hackaday.io/project/189442-temptale-ultra-teardown-repurpose) for further details.

## MCU 

Ultra-low-power [STM32L152RCT6](https://www.st.com/en/microcontrollers-microprocessors/stm32l152rc.html) Cortex&#xAE;-M3 32MHz/256KB flash/32KBSRAM. 

## LCD 

One line of 7-segment numbers and some additional segments. It has rubberconnector. [[muttonchopsjoe]](https://hackaday.io/muttonChopsJoe) carried out some research and shared LCD documentation. Many thanks! It was made for [TempTale Ultra Dry Ice](https://www.sensitech.com/en/media/TTUItra_Probeless_Dry_Ice_LS_1_2021_tcm878-133025.pdf), which is another modification of this logger. Have not tested yet, but it is very likely that all TempTale Ultras have similar LCDs.

## External flash/EEPROM 

[Winbond25x40](https://datasheetspdf.com/pdf-file/582944/Winbond/W25X40/1) 4Mbit serial flash memory chip.

## Plastic Case 

It is secured with two screws and the board is attached to the upper part with another two screws, so you could only take off the bottom part to access the pads and use buttons and LCD normally. Everything could be easily opened and closed without breaking.

## What else could be reused?

Battery. Probably it is rechargeable, but the battery in my item was dead.
