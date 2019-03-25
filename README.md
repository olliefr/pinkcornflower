# Project Pink Cornflower

A self-watering tray for wildflowers. [Fusion 360 CAD files](https://a360.co/2TBmJan)

Original work by Oliver Frolovs, 2019

![Image of 3D Printed Flower Tray](tray.png)

Files:

* `.stl` files are stereolithography files for 3D printing. They are a direct export from the `Fusion 360` model.
* `.3mf` files are `Cura Ultimaker` project files
* `.gcode` files are `Cura Ultimaker` output to be printed
* `.dxf` files are direct export of MDF box surfaces from `Fusion 360` model

The 3D printing workflow for *each* of the parts is the following:

* A solid body is exported as `stl` file from the `Fusion 360` model
* An `stl` file is imported into `Ultimaker Cura`, the printing parameters are set
* The `gcode` numerical control instructions file is saved from `Ultimaker Cura`
* The `3mf` project file is saved from `Ultimaker Cura` to have a record of parameters used

General Wisdom:

* MDF must be primed with solvent-based primer to prevent surface damage. [How to Paint MDF](https://www.bidvine.com/blog/how-to-paint-mdf/) and [Learn the art of priming MDF before you paint](https://www.thesprucecrafts.com/avoid-extra-sanding-prime-mdf-2365111) and [Tips for Painting MDF](https://www.finewoodworking.com/2006/06/06/tips-for-painting-mdf)
* [Dr Dulux: Paint Finishes Explained](https://www.dulux.co.uk/en/decorating-tips-and-advice/dr-dulux-paint-finishes-explained)

Useful links:

* [Dulux Pick Your Colour Palette](https://www.dulux.co.uk/en/colour-details/)
* [Self-Watering Planter (Small)](https://www.thingiverse.com/thing:903411) This is where I got the idea of self-watering planter from...

Some Estimates:

* [Dulux Primer for Wood](https://www.dulux.co.uk/en/products/primer-undercoat-wood) covers 16 m^2 per litre. So, a 250 ml can covers 4 m^2.



## 3D printed parts

Defined in the `Fusion 360` model, referenced above.

All parts:
* Ultimaker Cura 2+
* PLA 0.4 mm nozzle

### Plant Pot.stl v36
* Layer Height 0.15
* Infill 20%
* Quantity x6
* Build plate adhesion
* 12 hours estimated
* 11.34 m, 90 g material
* *Result*: printed well on the first attempt

### Top.stl v36
* Layer Height 0.1
* Infill 20%
* Quantity x1
* Build plate adhesion
* Generate support
* 14 hours estimated
* 9 m, 70 g material
* *Result*: TBA

### Tray.stl v36
* Layer Height 0.1
* Infill 20%
* Quantity x1
* Build plate adhesion [REQUIRED]
* 23 hours estimated
* 13 m, 100 g material
* *Result*: failed on first attempt as no adhesion plate was generated.

## Obsolete: MDF box parts

*NB* Kerf is likely to be incorrect... this is not relevant anymore, since 3D-printed container looks good enough.

Defined in the `Fusion 360` model, referenced above.

All parts:
* To be laser cut on [Trotec SP1500](https://www.troteclaser.com/en-gb/trotec-laser-machines/laser-cutters-sp-series/)
* v36 MDF thickness 9 mm
* v36 kerf 0.13 mm

Quantities:
* Side x2
* Front x2
* Bottom x1
