## Overview
Here the mechanical part of the hardware components and their assembly are described. The mechanical unit of the in-incubator perfusion unit contains a peristaltic pump head, driven by a stepper motor, both mounted on a sample tray where up to 3 multi-well plates and medium reservoirs can be held in place. The tray also has attachable/detachable feet, that can be used to evelate the tray and fit a microscopy unit (e.g. Cytosmart Lux) under one of the samples. The individual design files of the components in the table below are assembled in the [design files](https://github.com/IRNAS/newharvest-incubator-perfusion/tree/main/hardware/design%20files) folder. The complete assembly file (image below) containing the mentioned files is available in the complementary [perfusion-system-assembly.STEP](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/hardware/perfusion-system-assembly.STEP) file.

![assembly](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/hardware/assembly-v1.jpg)

## Bill of materials

| Aluminum         | Quantity | Description                     |
|------------------|----------|---------------------------------|
| 1 - NH2022V1 -T  | 2        | Leg                             |
| 2 - NH2022V1 -T  | 2        | Leg 2                           |
| 3 - NH2022V1 -T  | 1        | Adapter                         |
| 4 - NH2022V1 -T  | 1        | Nema 34 mount 1                 |
| 5 - NH2022V1 -T  | 1        | Nema 34 mount 2                 |
| 6 - NH2022V1 -T  | 1        | Nema 34 mount 3                 |
| 7 - NH2022V1 -T  | 1        | Motor clutch                    |
| 8 - NH2022V1 -T  | 1        | Tray                            |
|                  |          |                                 |
| Plastic          |          |                                 |
| 9 - NH2022V1 -T  | 2        | Manifold V1                     |
|                  |          |                                 |
| Mechanics        |          |                                 |
| 10 - NH2022V1 -T | 1        | Nema 34 stepper motor           |
| 11 - NH2022V1 -T | 1        | Peristaltic pump                |
|                  |          |                                 |
| Screws           |          |                                 |
| 12 - NH2022V1 -T | 10       | screw TORX ISO7380 BN6404 M4x16 |
| 13 - NH2022V1 -T | 4        | screw DIN 912 M6x20             |
| 14 - NH2022V1 -T | 2        | screw DIN 7984 M6x10            |
|                  |          |                                 |
| Other            |          |                                 |
| 15 - NH2022V1 -T | 2        | Magnet                          |

## Assembly instructions
The [assembly instructions](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/hardware/assembly-instructions.pdf) for the mechanical part of the pump system are summarized in the complementary file.

## Alternative design
The described assembly uses a Nema 34 stepper motor to drive the pumping motion, however, we also developed and tested an alternative design that uses a spare DC motor used in Masterflex peristaltic pumps, described in the complementary [zip file](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/hardware/NewHarvest_perfusion-system_alt.zip).
