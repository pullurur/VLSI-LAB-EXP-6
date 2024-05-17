AIM:
To create,simulate the design of CMOS inverter,NAND,NOR from schematic using cadence.

APPARATUS REQUIRED:
cadence

PROCEDURE:
Commands to get into Cadence

Right Click and open the terminal window Type the following commands as follows and press enter. i) tcsh ii) source /home/install/cshrc iii) virtuoso

Procedure for Schematic simulation using Cadence

Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…” Close the 2nd window Use 1st window i.e virtuoso window(CIW) for further processing. i) Create a New Library ii) Create Schematic Cell view. iii) Create the Symbol for schematic Cell view. iv) Create the test Cell view. v) Analog simulation by spectre

Procedure for Creating New Library.

a) File –New – Library b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK c) Attach the library to the technology library gpdk045.Click OK

Create Schematic Cell view. a) Go to 1st window i.e virtuoso(CIW) b) File-New-Cell view c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic d) Type: Schematic press OK e) Add the required components from the libraries and make the connections. f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin h) Make the connections by using fixed narrow wire key i) Click Check and Save button

Creating the Symbol for schematic Cell view

a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok b. Now Symbol generation form appears. Click Ok If No changes required c. A new window with with default symbol is created. d. Edit the symbol if you want to give actual symbol shape else continue. i. Execute Create-Cell view-from cell view ii. Library Name and Cell Name must be same which you have used for schematic. Press OK iii. Check for the position of pin side.Prss OK iv. Edit for the shape by Create-Shape-Choose required options to edit.

Creating the new test cell view

a) Go to CIW window, Execute File-New-Cell view b) Setup the new file form Library: Select the one you a created. Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test View: Schematic Type: Schematic press OK

Analog simulation by SPECTRE.

a. In test cell view window i. Launch – ADE L(Analog Design Environment) b. Execute Setup—Simulation/directory/Host A new window opens c. Set the simulation window to spectre and click ok d. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK. e. Execute Analysis – Choose. A window opens. f. Select the type and set the specifications and press OK g. Execute Output s—to be plotted – Select on Schematic h. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse i. Execute Simulation -- Net list and Run

INVERTER SCHEMATIC:

![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/d2ce1347-570e-461a-a995-49cc4b6a9c74)
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/5c05bb5e-f90e-4bae-9200-89d80751a4f6)

Specifications: Vpulse

V1 = 0

V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Vdc = 1

Simulation Settings

Setup for transient analysis:

Stop time =400n

Setup for D.C analysis

Component to be selected in schematic is for d.c analysis

Start = -1 Stop = 1 resp.

Expected Waveform:

Transient Analysis:

![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/2998f1d6-f153-4059-ba10-9e4687575696)

DC Analysis:
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/8f38c25e-279e-4c79-8131-d8f8b181d688)

NAND SCHEMATIC :
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/7756e5e8-640a-400f-a499-83502865bb71)
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/31ae619c-dbfc-4d4c-bf1d-0d5fcf6e30d0)

Expected Waveform:

Transient Analysis:
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/ca9ff8dd-04fa-46e1-829d-c5d210115f7a)

NOR SCHEMATIC:
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/f8bed960-e0da-4313-8713-a84f627cca22)
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/05e64298-0825-4dca-b89e-d1ca374a1264)

Specifications:

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

Expected Waveform:

Transient Analysis:
![image](https://github.com/pullurur/VLSI-LAB-EXP-6/assets/161436550/55b813b0-d83e-4ab1-82ff-7ba106837eea)


RESULT:
Thus, the design,simulation and verification of the CMOS inverter,NAND,NOR from schematic using cadence was successfully completed.







