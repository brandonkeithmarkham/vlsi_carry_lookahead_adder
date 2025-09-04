# ⚡ VLSI Carry Look-Ahead Adder Project

This repository contains the design files and documentation for my **8-bit Carry Look-Ahead (CLA) Adder**, implemented with NAND-only logic gates. The project focuses on logic design, transistor-level simulation, and VLSI layout using LTspice and Microwind.

## 📄 Project Overview
The goal of this project was to design and simulate an 8-bit CLA adder that outperforms ripple-carry designs by computing carries in parallel. The implementation was constrained to **NAND-only gates**, demonstrating their universality in digital design. The adder was verified through logic-level, transistor-level, and post-layout simulations.

## 🛠 Tools & Methods
- **Logic & Circuit Simulation**: LTspice  
- **Layout & Post-Layout Analysis**: Microwind  
- **Design Approach**:
  - Two 4-bit CLA blocks combined for an 8-bit adder  
  - XOR, AND, OR expressed using only NAND gates  
  - DRC and timing verification performed in Microwind  

## 📊 Key Outcomes
- Successfully implemented an **8-bit CLA adder** using only NAND gates  
- Verified functionality through **gate-level and transistor-level LTspice simulations**  
- Completed **Microwind layout with DRC checks** and post-layout timing analysis  
- Demonstrated improved carry computation speed compared to ripple-carry adders  

## 📄 Documentation
The full project documentation, including schematics, simulation plots, and layout screenshots, can be found here:  
👉 [**Final Report**](./docs/EE4352_VLSI_Final_Project.pdf)  
👉 [**Presentation Slides**](./docs/VLSI_Presentation.pdf)  

Example simulation files and layout sources are included in this repository for reference and reproducibility.

## 🔖 Notes
- NAND-only mapping highlights the universality of NAND gates in digital logic.  
- Timing results were compared across gate-level, transistor-level, and post-layout implementations.  
- Modular 4-bit CLA blocks make the design scalable to larger adders.  

## 📝 Authors
Brandon Markham, John Gellerup, Cassidy Miskovitz  

## 📫 Contact
[LinkedIn](https://www.linkedin.com/) | [Email](mailto:youremail@example.com)
