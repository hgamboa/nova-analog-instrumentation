# Guide 1 - Intro to LTspice

## Pre requeirments 

1. Install [ltspice]( https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html )

1. Print shortcuts:
  - for MAC [link](https://www.analog.com/media/en/simulation-models/spice-models/LTspiceShortcutsForMacOSX.pdf)
  - for windows [link](https://www.analog.com/media/en/simulation-models/spice-models/LTspice_ShortcutFlyer.pdf)


## Goals

1. Learn how to design a simple circuit in LTSpice
2. Generate a DC simulation and validate with your assumptions


## Tasks

1. Draw the second stage of the Coolpits Oscilator 
  - Introduce each of the components (R, C, Voltage source)
  - Introduce the specific values to each component
  - Add NPN transistor and the select the type to be 2N2222
  - Add a ground 
  - Connect the circut with wires
  - Add a .op spice directive
2. Compute the expected value for Vb and Ve 
3. Execute a DC simulation and check the spice output

The diagram is the following:

![Circuit Diagram](LTopsimulation.jpg)


The simulation is made by introducing a spice directive 

.op

Then check spice error log and verify V(Vb) and V(Ve), compare with your  expected results.

