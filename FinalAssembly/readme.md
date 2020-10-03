## Planetary Gearbox (Group 5)
##### Audrey Chan, Keshav Raj

#### Summary
This gearbox consists of a simple planetary gear drive system consisting of three planets, a ring gear and a sun gear. It also features central input and output shafts and the ability to shift between rotational directions on the output shaft.

The exterior box is made of laser cut 6mm acrylic while the gears themselves are to be 3D printed using ABS filament with at least 60% infill to provide the strength needed (as the input rotary motion specifications are unknown). For further details, please refer to the readme found within the fabrication outputs folder for 3D printing.


The gears all follow a standard which consists of a module of 2.5 and pressure angle of 20o. As mentioned previously there are two drive gears to the output shaft which provide two different directions and rate of rotations. The two gears are the sun and ring gears.
The gear ratio between the output and input shafts when the sun gear is engaged is 2:1 (input : output). The gear ratio from when the ring gear is engaged is 4:1 in the opposite direction. As such this gearbox is a reduction gearbox.


In order to mount a bearing onto the shafts, the bearing must be heated in heated oil to expand it. Then it can be mounted onto a shaft and after it cools it will form a tight grip with the shaft and shouldn’t move around.

As the gear system is expected to be slow in rotational speed (it is plastic and ABS melts at 230o and will erode quickly), epoxy can be used to mount the gears onto the bearings.


For additional assembly details regarding the gearbox, please refer to the file “instructions.pdf” which consists of a step by step set of instructions on assembling the gearbox and getting it ready for operation.

#### Video in Motion
Link: https://youtu.be/1ZXuh8vvWhE

Full disclosure for this we used the “animation” modelling and manually spun every gear instead of the “basic motion” technique. After playing with this for hours I think there’s just too much stuff for the system to calculate the physics in a coherent way. Parts would move that weren’t even “contact” tooled with anything and the teeth would just get stuck on themselves. You can see though in the video and by running the sim yourself that all the teeth mesh right and the movement makes sense.


Missing from this video is the action of the shifter which was too complex to make work in the vid. Basically the stick on the top pushes dog teeth gears into the sun or moon gear which connects the output splined shaft to that gear. Thus the output can be switched between gears.

#### BOM

| Item                                   | Qty               | Extra Details                                                                                  | Cost?              | External Links:                                                                                     |
|----------------------------------------|-------------------|------------------------------------------------------------------------------------------------|--------------------|-----------------------------------------------------------------------------------------------------|
| ABS Filament                           | 177g (66.65m)     | 1.75mm filament                                                                                | $34.99 USD/1KG     | https://www.amazon.com/Dremel-Nylon-Printer-Filament-Diameter/dp/B076MBTJBR/                        |
| Acrylic (clear)                        | 2x 600x400 Sheets | 6mm thickness                                                                                  | $25.81 NZD Exc GST | https://cambrianplastics.co.nz/product/acrylic-clear-cut-to-size-2/                                 |
| 6 mm ID x 12mm OD Flanged Ball Bearing | 11                | Servocity Part: 535220                                                                         | $18.65 USD         | https://www.servocity.com/6mm-id-x-12mm-od-flanged-ball-bearing-2-pack/                             |
| 12mm Bore Side Tapped Pillow Block     | 1                 | Servocity Part: 535096                                                                         | $8.49 USD          | https://www.servocity.com/12mm-bore-side-tapped-pillow-block/                                       |
| 720 mm of silver steel rod             | 1                 |                                                                                                | ~$13 NZD           | https://tradetools.co.nz/products/silver-steel-6mmx36-length                                        |
| M3x12 screws                           | 48                | From Tim                                                                                       | You have plenty    |                                                                                                     |
| M3x16 screws                           | 5                 | From Tim                                                                                       | You have plenty    |                                                                                                     |
| UNC 6-32 30mm screws                   | 2                 |                                                                                                | $1.25 USD          | https://www.amazon.com/Phobya-UNC-6-32-30mm-Screws/dp/B004CLJLKI                                    |
| M3 Nuts                                | 48                | From Tim                                                                                       | You have plenty    |                                                                                                     |
| Decorative Sticker Sheet               | 1                 | I demand you put stickers on it (don’t have to be these stickers, just anything with a rocket) | $8.95 USD          | https://www.amazon.com/SPACE-Self-adhesive-Reflective-Decorative-Scrapbook/dp/B076CWYRM2/ref=sr_1_3 |

#### Contributions

###### Keshav:

* Created the gears in Solidworks
* Created the gear system assembly.
* Generated fabrication outputs
* Explanation of how to optimally 3D print the ABS components.

###### Audrey:

* Created Box
* Created Motion Study
* Created Assembly Instructions
* Filmography and Sound Design
