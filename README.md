# COAL Microprocessor Project  

## 📖 Introduction  
This project is developed as part of the **Computer Organization and Assembly Language (COAL)** course.  
The objective is to design and implement a **simple single-cycle RISC Microprocessor** using digital logic design concepts and simulation tools like **Logisim**.  

It covers the design of functional units such as **ALU, Program Counter, Register File, Instruction Memory, Data Memory, and Control Unit**. The project demonstrates how instructions are executed at the hardware level.  

---

## 🎯 Objectives  
- Understand the design of a **RISC-based microprocessor**.  
- Apply **digital logic concepts** to build functional units.  
- Implement instruction formats (R, I, and J).  
- Verify processor operations with **Logisim simulations**.  
- Apply theoretical knowledge of **COAL** into practical system design.  

---

## 📦 Deliverables  
- Complete project report (with design, specifications, and figures).  
- Logisim circuit files for microprocessor components.  
- Documentation of instruction execution.  

---

## 🛠️ Design of Microprocessor  
The processor is built using the following units:  

1. **Program Counter (PC)** – Keeps track of instruction addresses.  
2. **Instruction Memory (ROM)** – Stores instructions.  
3. **Data Memory (RAM)** – Stores data during execution.  
4. **Register File** – Temporary storage for registers.  
5. **Arithmetic and Logic Unit (ALU)** – Performs arithmetic and logical operations.  
6. **Control Unit** – Generates control signals for execution.  

---

## 🧩 Instruction Formats  
The processor supports:  

- **R-Format** → Register-to-register operations.  
- **I-Format** → Immediate, Memory reference, and Branch instructions.  
- **J-Format** → Jump instructions.  

---

## 📑 Types of Instructions  
- Arithmetic Instructions  
- Memory Reference Instructions (Load/Store)  
- Branch Instructions  
- Jump Instructions  

---

## 🔧 Digital Circuit Design  
- **ALU Design (4-bit)**  
- **Register File (24x4)**  
- **Instruction Memory (24x16)**  
- **Data Memory (24x4)**  
- **Program Counter (4-bit)**  
- **Control Unit**  

Each unit is implemented separately and then integrated into the final processor.  

---

## 🖥️ Tools Used  
- **Logisim** (for circuit design & simulation)  
- **MS Word** (for project documentation)  

---

## 📂 Project Structure  
/COAL-Microprocessor-Project

│── Report.docx # Detailed project report

│── Logisim/ # Logisim circuit files

│ ├── ALU.circ

│ ├── ProgramCounter.circ

│ ├── InstructionMemory.circ

│ ├── DataMemory.circ

│ ├── RegisterFile.circ

│ └── ControlUnit.circ

│── README.md # Project documentation


---

## ✅ Conclusion  
This project demonstrates the **complete design flow of a simple RISC microprocessor** from functional unit design to execution. It successfully integrates COAL concepts with hands-on implementation using Logisim.  

---

## 👨‍💻 Contributors  
- **Ahmed Raza**  
