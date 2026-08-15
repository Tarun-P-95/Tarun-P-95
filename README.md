<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:2c5364,100:00d9ff&height=220&section=header&text=Tarun%20Parashuramappanavara&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Digital%20Design%20%7C%20RTL%20%7C%20VLSI%20%7C%20FPGA&descAlignY=58&descSize=18" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2500&pause=800&color=00D9FF&center=true&vCenter=true&width=650&lines=Building+Hardware+that+Thinks+%F0%9F%A7%A0;RTL+Designer+%7C+VLSI+Enthusiast+%E2%9A%A1;18-State+FSMs+%26+Fixed-Point+MACs;NIT+Warangal+%7C+ECE+%2728+Batch;From+Gates+to+GDSII+%F0%9F%94%A9" alt="Typing SVG" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tarun--p-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tarun-parashuramappanavara/)
[![Gmail](https://img.shields.io/badge/Email-p386tarun%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:p386tarun@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Tarun--P--95-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Tarun-P-95)
[![Phone](https://img.shields.io/badge/Call-%2B91%207022851412-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+917022851412)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d9ff,100:2c5364&height=3&width=100%" width="100%"/>

## `$` whoami

```verilog
module tarun_p (
    input  wire        clk,          // always learning, always ticking
    input  wire         rst,          // resets between semesters, never gives up
    output reg  [7:0]  focus         // currently pointed at VLSI + RTL Design
);

    parameter INSTITUTE = "NIT Warangal";
    parameter BRANCH     = "Electronics & Communication Engineering";
    parameter YEAR       = "3rd Year (Batch of 2028)";
    parameter MISSION    = "Gates -> RTL -> Silicon";

    initial focus = 8'hFF;            // fully committed
endmodule
```

- 🔭 Currently architecting **RTL-based neural network inference engines** on FPGA — no CPU required.
- ⚡ Deep in the world of **finite-state machines, fixed-point arithmetic, and memory-mapped protocols**.
- 🎯 Long-term target: become a strong **Digital / VLSI / Hardware Engineer** — GATE/postgrad or direct core placements, whichever door opens first.
- 💬 Ask me about: **FSM design, fixed-point MAC pipelines, UART interfacing, AMBA AXI4-Lite, or TTL logic builds.**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d9ff,100:2c5364&height=3&width=100%" width="100%"/>

## 🧩 Signal Chain — Skills & Toolchain

<div align="center">

### Hardware Description & Verification
<img src="https://img.shields.io/badge/Verilog-000000?style=for-the-badge&logo=v&logoColor=00D9FF"/>
<img src="https://img.shields.io/badge/Xilinx%20Vivado-D2232A?style=for-the-badge&logo=xilinx&logoColor=white"/>
<img src="https://img.shields.io/badge/Intel%20Quartus-0071C5?style=for-the-badge&logo=intel&logoColor=white"/>
<img src="https://img.shields.io/badge/ModelSim-4B0082?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LTSpice-FF6600?style=for-the-badge"/>

### Languages
<img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white"/>

### Embedded & Prototyping
<img src="https://img.shields.io/badge/Arduino%20IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
<img src="https://img.shields.io/badge/Tinkercad-1DA1F2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Simulink-EF7D00?style=for-the-badge"/>

</div>

<table align="center">
<tr>
<td valign="top" width="50%">

**🔬 Coursework Foundations**
- Digital Electronics
- Signals & Systems
- Electronic Devices & Circuits
- Electromagnetic Theory
- Network Theory
- Linear IC Applications

</td>
<td valign="top" width="50%">

**🎯 Areas of Interest**
- FPGA Design & Prototyping
- VLSI & Chip Design
- Computer Architecture
- CPU/GPU Microarchitecture
- Low-Level Systems Programming
- Embedded Systems

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d9ff,100:2c5364&height=3&width=100%" width="100%"/>

## 🚀 Flagship Builds

<table>
<tr>
<td width="50%" valign="top">

### 🔢 [FPGA-Based MNIST Digit Recognizer](https://github.com/Tarun-P-95/fpga-mlp-mnist-accelerator)
**RTL & FPGA Implementation** &nbsp;•&nbsp; `Jan 2026 – Apr 2026`

A CPU-free neural network accelerator, entirely in RTL.

- 🧠 18-state FSM controller orchestrating a full MLP inference pipeline — data flow, MAC accumulation, and argmax decoding, zero CPU involved.
- ⚙️ 8-bit fixed-point MAC unit with **Q1.7 saturation arithmetic**, inferring BRAM for **23,000+ weights** and ROM LUTs for single-cycle activation.
- 🔌 UART receiver with a **double-flop metastability synchronizer** for reliable async PC→FPGA pixel streaming, plus live 7-segment display output.

`Verilog HDL` `Vivado` `Artix-7 (Nexys A7)` `UART` `BRAM` `FSM Design`

</td>
<td width="50%" valign="top">

### 🔗 AMBA AXI4-Lite Slave Peripheral
**RTL Design** &nbsp;•&nbsp; `Jul 2026 – Aug 2026`

A fully compliant memory-mapped peripheral built from first principles.

- 🏗️ Architected all five independent AXI channels (**AW, W, B, AR, R**) for decoupled, deadlock-free transactions.
- 🤝 Implemented rigorous **VALID/READY** handshakes across every channel.
- 🧮 Engineered memory-mapped logic with **4-bit write strobes (wstrb)** to synchronize 32-bit control/status registers.

`Verilog HDL` `ARM AMBA Protocols` `Vivado` `Logic Design`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎲 3-Bit Timed Binary Guessing Game
**Digital IC Implementation** &nbsp;•&nbsp; `Mar 2026 – Apr 2026`

A microcontroller-free hardware game built entirely from discrete logic.

- ⏱️ Unlimited guessing attempts within a fixed **10–15 second** countdown, no MCU in sight.
- 🔍 Verification system using **XOR/OR comparators** and edge-triggered **D-Flip-Flops (7474)** to latch inputs and prevent tampering.
- ⏲️ Game-over timing enforced by an **NE555 timer** in monostable mode; gate count minimized using **De Morgan's laws**.

`74-Series TTL Logic` `D-Flip-Flops` `NE555 Timer` `Tinkercad` `Breadboard`

</td>
<td width="50%" valign="top">

### 🌐 [Digital Twin — Campus Power](https://github.com/sk24ecb0a56-coder/innothon_digital_twin)

Using ML-driven data to model power requirements and build a live digital-twin dashboard of campus power consumption.

`Python`

<br/>

### 💰 [Personal Finance Management System](https://github.com/Tarun-P-95/Personal-Finance-Management-System)

A desktop app (Tkinter + Matplotlib) for tracking income, expenses, savings, and future bills — with login/profile management and categorized transactions.

`Python` `Tkinter` `Matplotlib`

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d9ff,100:2c5364&height=3&width=100%" width="100%"/>


## 🛰️ Positions of Responsibility

> **Executive Member — Satellite and Electronics Amateur Club**, NIT Warangal &nbsp;•&nbsp; `2025 – Present`
> - Co-hosted an Arduino workshop for junior students covering hardware interfacing and embedded programming basics.
> - Helped organize and manage technical events during **Technozion**, the college's annual tech fest.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d9ff,100:2c5364&height=3&width=100%" width="100%"/>

<div align="center">

### ⚡ "First, solve the problem. Then, write the RTL."

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:0f2027,100:00d9ff&height=120&section=footer" width="100%"/>

</div>
