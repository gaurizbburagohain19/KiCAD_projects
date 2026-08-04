# Constant Current Source (~10mA)

## Project Overview
This project is a hardware simulation of a constant current source built in KiCad. It uses a 2N3906 PNP transistor and a 1N4148 diode biasing network to deliver a stable, load-independent current of approximately 10.5mA.

## Schematic
*(Drag and drop your schematic screenshot image right here to embed it)*

## Simulation Results
A DC Sweep analysis was performed using SPICE models across a 10-ohm to 1k-ohm load range. The results prove stable current regulation despite massive load fluctuations.

*(Drag and drop your simulation graph screenshot image right here to embed it)*

## How to Run the Simulation
1. Clone or download this repository.
2. Open the project file in KiCad.
3. Open the schematic and launch the integrated SPICE simulator.
4. Run the pre-configured DC sweep to view the current plot.
