# Experiment: 4:1 Multiplexer Implementation in Spartan-7 FPGA

## Aim
To design, simulate, synthesize, and implement a 4:1 Multiplexer using Verilog HDL on a Spartan-7 FPGA using Xilinx Vivado Design Suite.

---

## Apparatus Required
| S.No | Apparatus / Software | Specification / Description |
|------|----------------------|-----------------------------|
| 1 | FPGA Board | Xilinx Spartan-7 development board (modify pin names for your board) |
| 2 | Software | Xilinx Vivado Design Suite 2023.1 or later |
| 3 | Cable | USB Programming Cable (JTAG/USB-JTAG) |
| 4 | Power Supply | As required by the development board |
| 5 | Accessories | Breadboard/wires (optional), LEDs and switches present on board used for I/O |

---

## Theory
A **4:1 multiplexer** selects one of four data inputs (D0..D3) and routes it to a single output Y, based on two select lines S[1:0].

**Truth table**

| S1 | S0 | Y   |
|----|----|-----|
| 0  | 0  | D0  |
| 0  | 1  | D1  |
| 1  | 0  | D2  |
| 1  | 1  | D3  |

**Logic (one implementation):**
