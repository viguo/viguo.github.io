# chapter1 Overview
-  training object
-  chip design flow
-  synthesis in chip design
- Q&A
# chapter2 data prepare
- **library prepare**
	- standard cell library
	-  memory library
	-  macro library
	-  IO library
- **design prepare**
	-  file list
	-  include file
- **constraint**
	-  timing constraint
	- donot touch
	- dont use
- **Lab**
	- Convert .lib to .db
	- familiar .lib file
# chapter3 tcl introduction
  - tcl overview
  - tcl  syntax
  - common commands in dc_shell
  - lab
    write tcl script
# chapter5 run dc
- **library setting**
	- target library
	- link library
	- search path
- **option setting**
	- read RTL
	- optimization
- **read_design**
	- verilog/system verilog
	- define
	- link
- **lab**
	- write a dc script and load the design

# chapter6 synthesis
- **running synthesis**
	- elaborate design
	- link design
	- compile_ultra options
	- report
- **introduce synthesis process**
	- RTL to GTECH
	- GTECH to mapped cell
	- design rule fix
	- critical timing path optimization
- **check netlist quality**
	-	floating inputs
- **check constraint quality**
	- unconstrained path
	- not clocked registers
- **check timing reports**
	- report_qor
	- report_timing
- **lab**
	- run synthesis and understand the reports
# chapter7 debug and improve result
- what's PPA
- analyze and improve timing
- analyze and improve power
- analyze and improve the area
- lab
	- analyze the result and give feedback about improvement
# chapter6 Design Compiler GUI
- introduce DC compiler GUI
- lab
	- operate in the GUI

# chapter8 program in dc_shell
- data structure
- class attribution
- lab
# chapter8 physical aware synthesis
- why synthesis need to aware physical information
- wire load model
- read physical information
- lab
	- run  physical aware synthesis
# chapter10 run MCU synthesis
- run lab
# chapter10 advance synthesis
- optimize the dynamic power with toggle information
- write svf file for formality
- clock gating insertion
# chapter 11 backup
- introduce the advanced synthesis class
