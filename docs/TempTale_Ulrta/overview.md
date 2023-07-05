Official Specifications

It was manufactured by Sensitech, a US supply chain visibility company. The exact model is TempTale Ultra. The official info could be found here.

Is it officially re-usable? No, they sell them as single-use devices. The official FAQ tells that

    Can I reuse or reprogram a temperature indicator?
    No. Temperature indicators are simple, convenient, cost-effective, single-use electronic monitoring devices, programmed with a customer-specific profile during the manufacturing process. The devices are designed for limited operation life and are not reprogrammable.

I found out that in 2009 Sensitech launched the recycling program:

    To encourage participation at receiving locations, Sensitech will provide display posters to those requesting them.

Apparently it was not encouraging enough since people constantly sell used items on eBay and other platforms. So this completely operational hardware considered to be e-waste.

Is it possible to use it as a devboard? Definitely yes. There are pads on the PCB for standard SWD interface and some GPIO. Alternatively, you could salvage some useful items like Flash chip, battery and LCD. You might want to use LCD pads to solder some external modules. After writing this post I found out that [zvodd] even made a PlatformIO file for this board. Check out their post for further details.

MCU Ultra-low-power STM32L152RCT6 Cortex®-M3 32MHz/256KB flash/32KB SRAM.

LCD gives you one line of 7-segment numbers and some additional segments. It has rubber connector. [muttonchopsjoe] carried out some research and shared LCD documentation (1) (2). Many thanks! It was made for TempTale Ultra Dry Ice, which is another modification of this logger. Have not tested yet, but it is very likely that all TempTale Ultras have similar LCDs.

External flash/EEPROM Winbond25x40 4Mbit serial flash memory chip.

Plastic Case is secured with two screws and the board is attached to the upper part with another two screws, so you could only take off the bottom part to access the pads and use buttons and LCD normally. Everything could be easily opened and closed without breaking.

What else could be reused: battery. Probably it is rechargeable, but the battery in my item was dead.
