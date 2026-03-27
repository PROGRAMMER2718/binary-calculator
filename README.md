# 🔢 Binary Adder & Subtractor using 2’s Complement

## 📌 Project Overview
This project implements a **Binary Adder and Subtractor circuit** capable of performing both operations using a single unified design. The system is based on **2’s complement arithmetic**, which allows subtraction to be handled as addition internally.

The circuit is designed and simulated using **CircuitVerse**, demonstrating how digital logic circuits perform arithmetic operations inside an ALU (Arithmetic Logic Unit).

---

## 🚀 Live Simulation
👉 [View Circuit on CircuitVerse](https://circuitverse.org/users/413055/projects/binary-adder-and-subtractor-5d61a910-97bb-4d81-91e0-fb03354c6ab9)

---

## 🎯 Objectives
- Design a circuit capable of performing **binary addition and subtraction**
- Implement **2’s complement method** for subtraction
- Use **basic logic gates and full adders**
- Understand how arithmetic operations are handled in digital systems

---

## 🧠 Concept Used

### 🔹 1. Binary Addition
- Performed using **Full Adders**
- Handles carry propagation through stages

### 🔹 2. Binary Subtraction
- Implemented using **2’s Complement**
- Steps:
  1. Invert bits (1’s complement)
  2. Add 1
  3. Add to the other number

### 🔹 3. Control Signal (Mode)
- `M = 0` → Addition  
- `M = 1` → Subtraction  

---

## ⚙️ Components Used
- XOR Gates
- AND Gates
- OR Gates
- NOT Gates
- Full Adders
- Input switches
- Output displays

---

## 🏗️ Working Principle

1. Inputs: Two binary numbers (A and B)
2. A control signal (Mode) decides operation:
   - If Mode = 0 → Normal addition
   - If Mode = 1 → B is converted to 2’s complement
3. XOR gates modify input B based on Mode
4. Full adders perform the final computation
5. Output shows result along with carry/borrow

---

## 🔄 Block Diagram (Conceptual)
