# Overview
This folder contains documentation of additional tools for liquid handling using the incubator perfusion system. Primarily, the system was adapted to use with P6 well plates (tested using [Falcon](https://ecatalog.corning.com/life-sciences/b2c/US/en/Cell-Culture/Cell-Culture-Vessels/Multiwell-Plates/Falcon%C2%AE-Plates/p/353046) and [Greiner](https://shop.gbo.com/en/row/products/bioscience/cell-culture-products/cellstar-cell-culture-multiwell-plates/657160.html), which are compatible with the 6-channel flow manifolds. Two design variations are available (see below). Furthermore, two single-unit chips with support for parallel perfusion were developed, one for flat samples and one for cubic samples with graded flow-rates achieved by varying channel diameters. 

In addition to the flow manifolds, a hydrocyclone filter design was developed, to remove particles (e.g. formed by tubing abrasion) from the liquid during perfusion without clogging or significantly altering the internal system pressure.

## Flow manifold designs
Several designs and materials were tested in the scope of development. Primarily, flow manifolds were developed to allow up to 6 parallel experiments (or repetitions of a single experiment) within a 6-well plate. In addition, single well units and other designs were tested as well, which are described in more detail [here](https://github.com/IRNAS/newharvest-perfusion-components).
### 6-well flow manifold variation 1
![image|200](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/liquid-handling/flow-manifold-6well/Manifold_v1.png)
Design variation 1 can be used as an intermediary unit that fits between the well plate base and cover. The flow manifold can be manufactured using CNC machining from PEEK blocks, which makes it chemically stable and suitable for autoclave sterilization. The design was also sucessfully manufactured using DLP resin 3D printing. To connect the manifold to tubing, the input and output channels were modified with M5 threading and sucessfully tested using M5 connectors, that either extend to [tube fittings](https://www.nordsonmedical.com/Shop/Fluid-Management/Products/M6210-6005) or [luer-lock](https://www.droh.de/produkt/2835-luer-lock-adapter-mit-m5-gewinde-weiblich). Other options would also be possible, depending on which threading the channel is adapted to. To improve sealing, o-rings with 3x1mm dimensions (or similar) can be used.

### 6-well flow manifold variation 2
![image|200](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/liquid-handling/flow-manifold-6well/Manifold_v2.png)
Design variation 2 is not compatible with a multi well-plate cover. Instead the manifold can be covered with an [adhesive, breathable membrane](https://www.sigmaaldrich.com/SI/en/product/sigma/z380059) to protect the samples while allowing sufficient gas exchange. Similarly to manifold variation 1, connecting the wells to perfusion can be done using threaded fittings, depending on the modification of the channels.

### Single-well chips - flat
![image](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/liquid-handling/P6-single-well-chip/P6-well-chip-single.png)
In addition to the 6-well flow manifold that allows simultaneous perfusion of up to 6 wells within a P6 well plate, single-well chips were designed that are compatible with P6 well plates and can be used for double perfusion experiments within a single well, but could be adapted to individual petri dishes. The [design files](https://github.com/IRNAS/newharvest-incubator-perfusion/tree/main/liquid-handling/P6-single-well-chip) are available in the complementary folder and are suitable for manufacturing using DLP resin printing. The design was adapted to allow direct connection with laboratory tubing with an inner diameter of 1.5 - 2mm.

### Single-well chips - graded channels
![image](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/liquid-handling/perfusion-chamber/v1/explode-diagram.png)

The intention behind this design was to establish a gradient of shear forces within the perfusion channels of the scaffold, while maintaining even flow-rates throughout. This is achieved by varying the number and diameter of the channels on respective levels of the scaffold in such a way that the combined volume per level remains the same,however, the channel surface is gradually increased.

## Hydro-cyclone filter
![image](https://github.com/IRNAS/newharvest-incubator-perfusion/blob/main/liquid-handling/15ml-falcon-filter/15ml-falcon-hydrocyclone-filter.png)
Cyclone filters function by particle separation from a fluid by centrifugal forces and gravity, which is beneficial for continuous filtration where filter components are difficult to exchange and potential clogging could reduce flow rates. This filter design is adapted for laboratory applications using peristaltic pumps and connects to 15ml falcon tubes that act as particle collectors.
