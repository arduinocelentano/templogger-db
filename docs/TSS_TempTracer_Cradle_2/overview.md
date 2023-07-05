# TSS TempTracer Cradle 2

# Official Specifications

First I addressed it as [GSK](https://www.gsk.com), which is a British pharmaceutical company. But after some research I found out that it was manufactured by [TSS](http://www.tss.se), a Swedish company that delivers
temperature logger solutions. I also found some evidence that [other companies](https://www.healthcarepackaging.com/logistics-distribution/cold-chain-temperature-control/article/13291777/clinical-trial-experts-save-over-1-million-with-new-temperature-tracing-and-the-cloud) use
TSS loggers for their clinical shipments. The exact model of this one is TSS TempTracer Cradle 2. It is currently not available at their website, but I found some [specs](https://tss.se/wp-content/uploads/2018/12/TSS-TempTracer-Cradle-2_PRD_TDS_005-Ver-A.pdf).
My PCB has two button pads, but the buttons are not soldered. They are apparently used in other version of this logger.

# Is it officially re-usable?
Well, it contains a note on the sticker that tells &#x201C;Re-usable, do not dispose.&#x201D; But I have not figured out how to reset it (does **ERA** pad mean erase?) I found a [leaflet ](https://help.astrazeneca.tss.se/wp-content/uploads/2021/07/TSS-AstraZeneca_TT_leaflet.pdf)
by AstraZeneca regarding their reuse policy. So I assume this is a sort of marketing trick. What you get is a single use device that you may send to the manufacturer. They apparently reprogram it and resell the very same device again. It
is also possible that this procedure is crucial to ensure proper calibration. Anyway, since there is no point for a courier company to bother about reuse, these completely operational
boards often turn into e-waste.

## Is it possible to use it as a devboard?
Probably yes. Because the manufacturer supposedly reprograms them somehow. There are pads on the PCB for serial interface that probably might be used for this purpose. Apart from it and USB interface, most GPIO pins are not available. But what really restricts its usage in your
hobby project is [ATSAM4S16B](https://www.microchip.com/en-us/product/atsam4s16b) microcontroller unless you already have an [expensive programmer](https://www.microchip.com/en-us/development-tool/ATATMEL-ICE) to deal with it. If you know a cheap way to program them, please
share your ideas. It is also possible that there is some sort of USB bootloader, but I found no signs of it.

## MCU
[ATSAM 4S16](https://www.microchip.com/en-us/product/atsam4s16b) Cortex&#xAE;-M4 120MHz/1MB flash/128KB SRAM

## LCD
None

## External flash/EEPROM
None

## Plastic Case
It is secured with one screw beneath the sticker and could be easily opened and closed without breaking.
