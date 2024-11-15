# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.<br>

#### Synthesis RTL Schematic :

![Screenshot (52)](https://github.com/user-attachments/assets/e2782a77-5390-4e88-a4d7-2fdad3a06db4)

#### Area report:
![Screenshot (54)](https://github.com/user-attachments/assets/88fab233-b64a-4fa8-a82e-0f9ff18dbfae)

<br>
<br>
<br>
<br>
<br>
<br>


#### Power Report:
![Screenshot (55)](https://github.com/user-attachments/assets/7a5c2461-e6c4-487d-b672-ced979e42e00)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
