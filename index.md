# chapter1 Overview
-  **target of this training**
-  **chip design flow**
-  **synthesis in chip design**
- **Q&A**
# chapter2 data prepare 
- **library prepare**
	1. standard cell library
	2. memory library
	3. macro library
	4. IO library
- **design prepare**
	1. file list
	2. include file
- **constraint**
	1. timing constraint
	2. donot touch
	3. dont use
- **Lab**
	1. Convert .lib to .db
	2. familiar .lib file
# chapter3 run dc
- **library setting**
	1. target library
	2. link library
	3. search path
- **option setting**
	1. HDL
	2. optimization
- **read_design**
	1. verilog/system verilog
	2. define
	3. link
- **lab**
	1. write a script to read verilog

# chapter4 synthesis 
- **running synthesis**
	1. elaborate design
	2. link design
	3. compile_ultra options
	4. report
- **introduce synthesis process**
	1. RTL to GTECH
	2. GTECH to mapped cell
	3. design rule fix
	4. critial timing path optimization
- **check netlist quality**
	1.	floating inputs
- **check constraint quality**
	1. unconstrained path
	2. unclocked registers
- **check timing reports**
	1. report_qor
	2. report_timing
- **lab**
	1. run synthesis and understand the reports
# chapter5 debug and improve timing
- analyze timing result
- resolve real case
# chapter6 DC compiler GUI
- introduce DC compiler GUI	

# chapter7 frequent command
- tcl system
- class
- lab :
	1. write a simple scripts
