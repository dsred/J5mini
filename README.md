# J5mini
Just for fun construction of a 3d printer


Spezifications of the J5mini:
- Build space approx. 250mm x 250 mm x 200 mm
- Dimensions of the 3030-frame: 440mm x 580 mm x 525mm (width x height x depth)
- Independent triple Z-axis on MGN12H driven by SFU1204
- CoreXY on MGN12H
- Fast head, based on the Eva-System (https://main.eva-3d.page/)
- E3D-Volcano Hotend with a 0.6 mm Microswiss-Nozzle, 50W/24V heating
- Controlling Units: Rasperry Pi4 at a Bigtreetech Octopus with TMC2209
- 200W / 24 V Meanwell power supply
- 500W heat bed on a SSR with thermo fuse
- Software: Klipper via FluiddPi (Control via Web-Interface)


<b> 1. Printer head and X-carrier</b>

Is a remix of the well known and excellent EVA-system (https://main.eva-3d.page/) to fit a volcano hotend and to save some weight. Including an accelerometer of input shaper measurements and a Z-probe device.

