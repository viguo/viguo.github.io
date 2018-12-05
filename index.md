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
# chapter3 run dc
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

# chapter4 synthesis
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
# chapter5 debug and improve result
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

# chapter7 program in dc_shell
- tcl syntax
- attribute
- dc scripts
- lab :
	-	 write a simple scripts
# chapter8 physical aware synthesis
- why synthesis need to aware physical information
- wire load model
- read physical information
- lab
	- run  physical aware synthesis