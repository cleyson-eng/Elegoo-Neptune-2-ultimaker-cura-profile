![](https://github.com/MrJ0se/Elegoo-Neptune-2-ultimaker-cura-profile/blob/main/sample.png?raw=true)

### Install definitions (obsolet for Cura 5.X+ users, see last topic)

- copy folders "definitions", "extruders", "meshes" and "quality" to the resouce folder of your cura (cura folder/resources).

### Configure to create preview images for printer

- install "MKS Wifi Plugin" (marketplace -> extensions).
- restart your cura and add the printer.
- go to manage printers -> your neptune 2 printer -> MKS Wifi Plugin, mark active, go to tab "Preview Settings", mark screenshot support, and set "Printer model" as "default".

### Cura 5.X+ Notes

Now cura has a profile for elegoo neptune 2 by default, but if you want preview images, the previous topic still valid, and if your printer is colliding with a custom tensioner, change de size X,Y dimension from 260 to 235 (real size of bed) to solve.
