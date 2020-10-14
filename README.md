# skywater-openfpga
FPGA tape-outs using the open-source Skywater 130nm PDK and OpenFPGA

## Quick Start

```bash
#Clone the repository and go inside it
git clone https://github.com/LNIS-Projects/skywater-openfpga.git
python3 SCRIPT/repo_setup.py
```


* Keep this folder clean and organized as follows
  - **DOC**: documentation of the project
  - **ARCH**: Architecture XML and other input files which OpenFPGA requires to generate Verilog netlists
  - **BENCHMARK**: Benchmarks to be tested on the FPGA fabric
  - **HDL**: Hardware description netlists for the FPGA fabrics
  - **SDC**: design constraints
  - **SCRIPT**: Scripts to setup, run OpenFPGA etc.
  - **TESTBENCH**: Verilog testbenches generated by OpenFPGA 
  - **PDK**: Technology files linked from skywater opensource pdk
  - **SNPS\_ICC2**: workspace of Synopsys IC Compiler 2
                    Keep a README inside the folder about the ICC2 version and how-to-use.
  - **MSIM**: workspace of verification using Mentor ModelSim

* Note: 
  - Please **ONLY** place folders under this directory.
    README should be the **ONLY** file under this directory
  - Each EDA tool should have **independent** workspace in separated directories
