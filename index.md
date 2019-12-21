@[TOC](自动布局布线大纲)
# 芯片设计基础

## 视频

链接: [1.1](https://1001v.cn/chronus/url/v1/getVideoUrl/42642a333946464cb8de1d2c8b5980f5)
链接: [1.2](https://1001v.cn/chronus/url/v1/getVideoUrl/436adfa56a3b490ca1d753e4db5f90cb)
链接: [1.3](https://1001v.cn/chronus/url/v1/getVideoUrl/7f0adffa6ec24af983f8e6887e7e78c1)
链接: [1.4](https://1001v.cn/chronus/url/v1/getVideoUrl/67607121e7de4ed98e5a8feb41c0101b)
链接: [1.5](https://1001v.cn/chronus/url/v1/getVideoUrl/5ed6ef53c1fb4980ab6bf1ee4977525f)
链接: [1.6](https://1001v.cn/chronus/url/v1/getVideoUrl/a37a8f9ac59f4e03abc4575f7b231d67)
链接: [1.7](https://1001v.cn/chronus/url/v1/getVideoUrl/79a78dc543d54d7fb5b49dd75f9f22fe)
链接: [1.8](https://1001v.cn/chronus/url/v1/getVideoUrl/203ff0a90f1c4ea9b579afa3f6158113)
链接: [1.9](https://1001v.cn/chronus/url/v1/getVideoUrl/b1fe623070394522be1fd5a1ce95e9d4)
链接: [1.10](https://1001v.cn/chronus/url/v1/getVideoUrl/fbe5ec70884c4f348586fe0ab74a7aaf)

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

# chapter7 program in dc_shell
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
