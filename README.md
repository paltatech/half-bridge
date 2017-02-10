# TO247 Inverter power stage
This is the hardware repository of a 3 phase inverter, UNTESTED but designed with the following specs in mind:

* 70kw nominal, 150kw peak
* TO247 IGBT to allow for easy silicon upgrades and power capabilities. Its also cheaper.
* Watercooled
* Embedded security features (desaturation, soft turn off, reinforced isolation)

![Alt text](http://cdn.rawgit.com/paltatech/VESC-controller/master/doc/images/schematic_toplevel.svg)
![Alt text](doc/images/assembly1.png)
![Alt text](doc/images/3d board2.png)

You can also check the layout [here](https://eyrie.io/board?id=7261e811b9074e0fb00fe3fcbbaa14d9) 

Will need some cnc milling, components, a pcb, and some spot welding

Made open source with open source tools (kicad, freecad)

## Bill of materials
BOM, pcb gerbers, and custom parts can be found in [fabrication files](https://bitbucket.org/paltatech/half-bridge) directory

## License
This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2

