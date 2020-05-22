![Alt text](imgs/ratatech_echo_pcb_top_view.png?raw=true "RATAT-ECHO pcb top view")

# RATAT-ECHO

This repository contains mainly the PCB design files for a small echo effect unit. The circuit it's mainly composed by two major blocks, the echo and the spring reverb drive/recovery circuits. 

The echo module is basically an adaptation of the echo circuit included in PT2399 echo processor [datasheet](./datasheets/PT2399_1.pdf). The changes were mostly a few components values to a more standarized ones and the resistor/potentiometer to reduce a bit the minimum delay time. A great analysis of this circuit is done by [Electrosmash](https://www.electrosmash.com/pt2399-analysis). 

The core of the reverb unit is the [ Accutronics, AMC2BF, 2-Spring reverb tank](https://www.amplifiedparts.com/products/reverb-tank-accutronics-amc2bf-2-spring). This is a small and very affordable($9) spring reverb tank. I liked, not only for the budget but also because of the size and the ability to fit the whole tank within the unit box. The drive and recovery circuit was taken from Rod Eliott's design ["Spring Reverb Unit for Guitar"](https://sound-au.com/project34.htm). I added an additional potentiometer a the drive input in order to have some extra input gain. Also a clipping detector was included to have some feedback when pushing too much the input gain. 

## Files

* [datasheets](./datasheets) 	Datasheets of some of the components and schematics used in this project.
* [freecad](./freecad) 			Front panel 3d model design.
* [imgs](./imgs) 				Images used in the design and captures or the 3d models/final pcb.
* [kicad](./kicad) 				Main Kicad project directory. Including schematics and pcb.
* [others](./others) 			Random stuff.

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
