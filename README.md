# Booth's Algorithm Multiplier - Verilog Implementation

This project implements a **signed 16-bit Booth's Multiplier** in Verilog. It multiplies two 16-bit signed integers and produces a 32-bit signed product. The design follows the classical Booth's algorithm and is verified using a testbench with simulation waveforms.

---

## 🧠 What is Booth's Algorithm?

Booth's algorithm is an efficient technique for multiplying binary numbers, especially signed values. It reduces the number of additions/subtractions by encoding consecutive bits of the multiplier.

---

## ⚙️ Features

- ✅ 16-bit signed input operands  
- ✅ 32-bit signed product  
- ✅ Implements Booth’s encoding logic  
- ✅ Simulated using ModelSim / Icarus Verilog  
- ✅ Testbench with multiple test cases  
- ✅ Waveform output for verification  

---

## 🗂️ Project Structure

```plaintext
booth-multiplier-verilog/
├── design.sv         # Booth multiplier RTL code
├── testbench.sv      # Testbench to simulate the design
├── waveform.png      # Simulation result waveform (optional)
└── README.md         # Project documentation
