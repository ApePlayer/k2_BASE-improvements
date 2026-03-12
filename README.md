# K2 Pro Improvements Script

This is a fork of JaminCollins' K2 improvements project, adapted for the **K2 Pro**.

This repository includes install scripts for various improvements and features for the K2 Pro.

In the `features` folder you will find install scripts for each of the features being installed, if desired to run separately.
If you're curious what each of these scripts do, i encourage all to open the install.sh files and dive into the code.
You'd be surprised what you'll learn. 


## DISCLAIMER

Use at your own risk, I'm not responsible for fires or broken dreams.  But you do get to keep both halves if something breaks.

## Warning


## SCREWS TILT ADJUST 

I added a cfg for the BASE K2 printer so you can use it with it as well :)







## Features

* [axis_twist_compensation](./features/axis_twist_compensation/README.md)
* [better init](./features/better-init/README.md)
* [better root](./features/better-root/README.md) home directory
* [Cartographer](./features/cartographer/README.md) support
* installs [Entware](https://github.com/Entware/Entware)
* updated [Fluidd](./features/fluidd/README.md)
* updated [Moonraker](./features/moonraker/README.md)
* [Obico](./features/obico/README.md) - _WIP_
* implements [SCREWS_TILT_CALCULATE](https://www.klipper3d.org/Manual_Level.html#adjusting-bed-leveling-screws-using-the-bed-probe)

And a few quality of life improvement macros

* [MESH_IF_NEEDED](./features/macros/bed_mesh/README.md)
* [START_PRINT](./features/macros/start_print/README.md)
* [M191](./features/macros/m191/README.md)

### Bed Leveling

Sadly, many of the K2 beds resemble a taco or valley.  In the [bed_leveling](bed_leveling) folder you will find a python based script and short writeup on how to apply aluminium tape to shim the bed.

## K2 Pro Specifications

| Parameter | Value |
|-----------|-------|
| **Build Volume** | 300×300 mm |
| **Max Nozzle Temp** | 300°C |
| **Heater Power** | 70W |
| **Cooling Fan** | Single auxiliary |
| **Chamber Exhaust** | 1 fan |

## Credits

* [@jamincollins](https://github.com/jamincollins) - The Guy who made this project to begin with
* [@Guilouz](https://github.com/Guilouz) - standing on the shoulders of giants
* [@stranula](https://github.com/stranula)
* [@juliosueiras](https://github.com/juliosueiras)

* Moonraker - [https://github.com/Arksine/moonraker](https://github.com/Arksine/moonraker)
* Klipper - [https://github.com/Klipper3d/klipper](https://github.com/Klipper3d/klipper)
* Fluidd - [https://github.com/fluidd-core/fluidd](https://github.com/fluidd-core/fluidd)
* Entware - [https://github.com/Entware/Entware](https://github.com/Entware/Entware)
* Obico - [https://www.obico.io/](https://www.obico.io/)
* SimplyPrint - [https://simplyprint.io/](https://simplyprint.io/)

## FAQ

See the [FAQ](./FAQ.md)
