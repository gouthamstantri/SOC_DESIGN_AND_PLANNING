**<p align="center">DIGITAL VLSI SOC DESIGN AND PLANNING WORKSHOP**</p>

<p>Hello, everyone! I'll be sharing what I have learned during a 2 weeks of workshop on Digital VLSI SOC design and planning using openLANE tool and sky-130nm PDK offered by VSD Pvt ltd.</p>

**<p align="center">Day 1 -Inception of open-source EDA, OpenLANE and sky130 PDK**</p>

Introduction to QFN-48 Package, chip, pads, core, die and IPs

![335806110-a5d5897c-74a0-4c4b-b0e1-cb4186923e32](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/8aeebd01-6710-41f9-88b0-ed75559323ce)
![335806774-66f28906-d9da-4952-a27a-f39f96136841](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/fccb2d3e-15c2-46bd-9ab5-e765b5de05b6)
**<p align="center">Introduction to RISC-V**</p>

RISC architecture that were developed at the University of California, Berkeley. RISC is an open standard instruction set architecture (ISA) based on established RISC principles. Unlike most other ISA designs, RISC-V is provided under open source licenses that do not require fees to use. A number of companies are offering or have announced RISC-V hardware, open source operating systems with RISC-V support are available, and the instruction set is supported in several popular software toolchains. 
![335808593-fdda8d67-121b-4195-9c81-3e3ea5755f87](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/c6b4509a-650f-4952-8018-a3d68c044168)

**<p align="center">Introduction to all components of open-source digital asic design**</p>
![image](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/51e3e3e4-5f1b-4275-abfd-2571361a9531)
To design ASIC chips, few tools or things required. Those are

**RTL Design**: register-transfer level (RTL) is a design abstraction which models a synchronous digital circuit. for this designs many open sorces are available. like, librecores.org, opencores.org, github.com, etc...

**EDA tools**: The term Electronic Design Automation (EDA) refers to the tools that are used to design and verify integrated circuits (ICs). open sorces tools are available like Qflow, OpenROAD, OpenLANE, etc.

**PDK data**: PDK is process design kit. It is interface between FAB and design.
Theopensource foundry PDK used in this workshop is **SKYWATER 130nm** which is made open source by Google and Skywater foundry (efabless) under apache license

![image](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/f1038ff3-1163-4797-89aa-9ad00a606c12)

**<p align="center">Simplified RTL2GDS flow**</p>
![image](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/93118465-e295-4bd8-be0b-4c07f47b918d)

**<p align="center">Introduction to OpenLANE and Strive chipsets**</p>

In This workshop we will be using the opensource flow called **OPENLANE** its components are as shown in below figure
it is combination of many opensource tools such as
**<p align="center">YOSYS**</p>
**<p align="center">FAULT**</p>
**<p align="center">OPENROAD**</p>
**<p align="center">OPENSTA**</p>
etc..
![image](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/087c298a-4780-4073-8504-9f32ad675499)
**<p align="center">open-source EDA tools Handson**</p>
We have to enter in to the openlane path, type docker after Here we use flow.tcl file to open the tool in interactive mode
![335865271-1924f29c-a16f-4854-8794-c52f8000c7d1](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/cde744d7-711d-4bab-9f5d-8e64662f99fb)

<p>Now its ready for the commands

here we are opening the picorv32a.v design</p>

![335866282-8f6a0388-12ea-4996-95eb-9d2a06d739f2](https://github.com/gouthamstantri/SOC_DESIGN_AND_PLANNING/assets/51639089/e795c16b-5021-483d-987d-2bcc01105306)
