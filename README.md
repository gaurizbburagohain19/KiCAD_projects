# Constant Current Source (~10mA)

## Project Overview
This project is a hardware simulation of a constant current source built in KiCad. It uses a 2N3906 PNP transistor and a 1N4148 diode biasing network to deliver a stable, load-independent current of approximately 10.5mA.

## Schematic
<img width="817" height="702" alt="Screenshot 2026-08-04 202937" src="https://github.com/user-attachments/assets/6a2c1f1a-0fe3-4f3e-951b-5e2ee50e8355" />


## Simulation Results
A DC Sweep analysis was performed using SPICE models across a 10-ohm to 1k-ohm load range. The results prove stable current regulation despite massive load fluctuations.
<img width="760" height="515" alt="Screenshot 2026-08-03 185908" src="https://github.com/user-attachments/assets/29ee0f9d-533b-4cfe-8e51-7f9efd4d72f9" />



## How to Run the Simulation
1. Clone or download this repository.
2. Open the project file in KiCad.
3. Open the schematic and launch the integrated SPICE simulator.
4. Run the pre-configured DC sweep to view the current plot.
