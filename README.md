# Secure Communication Using UART

## 📌 Overview

This project implements a secure UART communication system using Verilog.
The UART transmitter and receiver are designed and verified through simulation.
An XOR-based encryption mechanism is added to provide basic data security
during communication.

## 🎯 Objectives

- Design UART transmitter and receiver using Verilog
- Understand UART communication protocol
- Verify the UART design using Verilog
- Add basic data encryption using XOR
- Analyze the design through simulation

## 🛠️ Technologies Used

- Verilog
- SystemVerilog
- UART Protocol
- XOR Encryption
- ModelSim
- Git & GitHub

## 📂 Project Structure

```text
Secure-Communication-Using-UART/
│
├── rtl/
│   ├── tx_controller.v
│   └── rx_controller.v
│
├── testbench/
│   └── tb_128.v
│
├── simulation/
│
└── README.md
