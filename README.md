# FPGA数据流位宽转换模块

初始目录仅准备仿真环境依赖，尚未包含业务RTL或业务测试。

本机工具：SystemVerilog2012语言模式、Icarus Verilog11.0、GNU Make4.3、Python3.10.12。
项目依赖：cocotb1.9.2、find-libpython0.5.1，已安装在本目录.venv。

直接使用iverilog、vvp、make；项目Python使用.venv/bin/python，无需激活环境。
cocotb.runner可通过项目Python导入并调用Icarus；cocotb配置查询入口是.venv/bin/cocotb-config。
具体模块、测试和示例运行命令由实现补充。

依赖恢复：创建Python3.10虚拟环境后，使用.venv/bin/python -m pip install -r requirements.txt。
