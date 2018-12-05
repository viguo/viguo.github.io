# chapter1 Overview
-  training object
-  chip design flow
-  synthesis in chip design
- Q&A
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
	1. read RTL
	2. optimization
- **read_design**
	1. verilog/system verilog
	2. define
	3. link
- **lab**
	1. write a dc script and load the design 

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
	4. critical timing path optimization
- **check netlist quality**
	1.	floating inputs
- **check constraint quality**
	1. unconstrained path
	2. not clocked registers
- **check timing reports**
	1. report_qor
	2. report_timing
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
