# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-19 at 21 04 59_c2fe8f1f](https://github.com/user-attachments/assets/d77a7ef9-5765-4fb9-a920-50d156b3aff9)


Area report:
![WhatsApp Image 2024-11-19 at 21 04 59_aca8a52a](https://github.com/user-attachments/assets/c96b939c-5d85-419c-ab05-4d1546233e41)


Power Report:
![WhatsApp Image 2024-11-19 at 21 05 00_6fe66e70](https://github.com/user-attachments/assets/3de2310d-8f68-4501-b75d-38a54b7a4312)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
