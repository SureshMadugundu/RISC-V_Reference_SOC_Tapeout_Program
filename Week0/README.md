# Week0 - VLSI System Design (VSD) Program Foundation & Tools Installation Instructions


<p align="center">
  <img src="https://img.shields.io/badge/VirtualBox-2A5DB0?style=for-the-badge&logo=virtualbox&logoColor=white" alt="VirtualBox"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Yosys-000000?style=for-the-badge&logo=git&logoColor=white" alt="Yosys"/>
  <img src="https://img.shields.io/badge/Iverilog-FF6600?style=for-the-badge&logoColor=white" alt="Iverilog"/>
  <img src="https://img.shields.io/badge/GTKWave-007ACC?style=for-the-badge&logoColor=white" alt="GTKWave"/>
  <img src="https://img.shields.io/badge/OpenSTA-32CD32?style=for-the-badge&logoColor=white" alt="OpenSTA"/>
</p>

---

This repository contains all the setup and installation instructions for Week0 tasks.

---

## System Requirements

Before starting, ensure your system meets the following requirements:

- **RAM:** 6 GB  
- **HDD:** 50 GB  
- **Operating System:** Ubuntu 20.04+  
- **CPU:** 4 vCPU  

---

## Oracle Virtual Machine

Download and install the Oracle VirtualBox from the official link:  
[VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads)

---

## Tool Installation Instructions

### **1. Yosys**

Yosys is a framework for Verilog synthesis. Follow the steps below to install:

```bash
sudo apt-get update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make          # If make is not installed, install it
sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make
sudo make install

```
### **2. iverilog**

```bash
sudo apt-get update
sudo apt-get install iverilog

```

### **3. GTKWave**
```bash
sudo apt-get update
sudo apt install gtkwave

```
