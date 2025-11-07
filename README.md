# 🏁 FPGA Race Timer — Real-Time Stopwatch on Hardware  

**Developed using Verilog and AMD Vivado | NMAM Institute of Technology (ECE Lab Project)**  

This project implements a **real-time race timer** on the **Real Digital Boolean Board (Spartan-7 XC7S50 FPGA)** using **Verilog HDL**. It measures and displays elapsed race timings with millisecond precision using hardware counters, clock dividers, and 7-segment multiplexing.

---

## ⚙️ Features
- Hardware-based timer coded in Verilog HDL  
- Real-time counting up to milliseconds  
- Display output via 7-segment displays  
- Designed and simulated in Vivado  
- Implemented on AMD Spartan-7 Boolean Board  

---

## 🧩 Modules Overview
### 🔸 `RACE_TIMER.v`
Implements counting logic for minutes, seconds, and milliseconds, and drives the 7-segment display using multiplexing.

### 🔸 `Mhz100_1000hz.v`
Divides 100 MHz input clock to 1 kHz for timing accuracy.

### 🔸 `RACE_COUNTER.xdc`
Contains pin mappings for switches, buttons, and display segments.

---

## 📷 Code Snapshots
Here are some Verilog code snapshots 👇  

| Main Timer Logic | Clock Divider | Constraints |
|:----------------:|:--------------:|:-------------:|
| ![Race Timer Code 1](./rt1.jpg) | ![Clock Divider](./rt8.jpeg) | ![Pin Constraints](./rt9.jpeg) |

*(See all other images in this repository for the complete code.)*

---

## 🎥 Demo Video
🎬 [Watch on LinkedIn] https://www.linkedin.com/feed/update/urn:li:ugcPost:7392545040939778048/
Or download & watch locally 👉 [racetimer.mp4](./racetimer.mp4)

---

## 🧠 Learnings
- RTL design & simulation in Vivado  
- Clock management and timing constraints  
- Debugging real-time logic on FPGA  
- Understanding counter design and synchronization  

---

## 🧰 Tools & Technologies
- AMD Vivado Design Suite  
- Verilog HDL  
- Real Digital Boolean Board (Spartan-7 XC7S50 FPGA)  
- 7-segment display interfacing  

---

## 👨‍💻 Developer
**Arya Dinesh**  
B.Tech in Electronics & Communication Engineering  
NMAM Institute of Technology, Nitte  

---

⭐ *If you found this project interesting, feel free to star this repo!*


