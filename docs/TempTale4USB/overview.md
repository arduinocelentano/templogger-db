# TempTale 4 USB

![](temptale4_pinout.jpg)

## Official Specifications

It was manufactured by [Sensitech](https://www.sensitech.com), a US supply chain visibility company. The exact model is TempTale 4 USB. The official info could be found [here](https://www.sensitech.com/en/media/T83001870_TT4_USB_MA_RevD_tcm878-133706.pdf).

## Is it officially re-usable?
No, they sell them as single-use devices. [It is said](https://forum.xda-developers.com/t/help-to-reprogramming-of-temperature-data-loggers-temptale-4-usb.4156735/) to exist some specific software to reset them, but it is not
officially available for customers. I found out that in 2009 Sensitech launched the [recycling program](https://www.fleetowner.com/refrigerated-transporter/refrigerated-vehicles-equipment/article/21221909/sensitech-green-solutions-means-recycling-for-recorders): 

>To encourage participation at receiving locations, Sensitech will provide display posters to those requesting them.

Apparently it was not encouraging enough since people constantly sell used items on eBay and other platforms. So this completely operational hardware turns into electronic waste.

## Is it possible to use it as a devboard?
Probably yes. But... what really restricts its usage in your hobby project is SAM 4S4 microcontroller unless you already have an [expensive programmer](https://www.microchip.com/en-us/development-tool/ATATMEL-ICE)&#xA0; to deal with it. If you know a cheap way to program these MCUs,
please share your ideas. It is also possible that there is some sort of USB bootloader, but I found no signs of it. If you short JP1 jumper, the screen begins to blink and an anonymous user [suggested](https://www.grant-trebbin.com/2014/12/sensitech-temptale-4-usb-teardown.html?showComment=1473432183380#c683124818955315144) that
it activates RESET mode. However no idea where to go next. Anyway, you could salvage some useful items like EEPROM and Flash chips, battery and LCD.

## MCU
[ATSAM4S4B](https://www.microchip.com/en-us/product/atsam4s4b)&#xA0; Cortex&#xAE;-M4 120MHz/256KB flash/64KB SRAM

## LCD
It gives you one line of 7-segment numbers and some additional segments. It has rubber connector.


## External flash/EEPROM
You receive both ATMLH414 EEPROM chip and [Winbond25x40](https://datasheetspdf.com/pdf-file/582944/Winbond/W25X40/1) 4Mbit serial flash memory chip.


## Plastic Case
It is secured with six screws and could be easily opened and closed without breaking. The board itself is connected to the upper part with another two screws.


## What else could be reused?
Lithium battery (it might be rechargeable, but you do it at your own risk), maybe a 5cm long USB Type-A tail if you badly need it :)
