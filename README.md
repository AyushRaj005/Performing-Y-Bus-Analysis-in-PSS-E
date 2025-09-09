# Power System Analysis using PSS/E and MATLAB

## 📌 Project Overview

This project focuses on performing **Power System Analysis** of the IEEE 9-Bus System using **Siemens PSS/E** and **MATLAB**. It covers single line diagram creation, Y-Bus matrix construction, load flow studies (Gauss-Seidel, Newton-Raphson, and Decoupled methods), and dynamic analysis.

---

## 📖 Experiments

### **Experiment 01**

### 📝 Aim

To create the single line diagram of a given power system using Siemens PSS/E.

### Task

* Design the **single line diagram** of a 9-Bus Power System from given data.

### Given Data

**Table 1: Terminal Conditions of IEEE 9-Bus System**

| Bus | V (kV)  | δ (deg) | P (MW) | Q (MVAR) |
| --- | ------- | ------- | ------ | -------- |
| 1   | 17.1600 | 0.0000  | 71.63  | 27.91    |
| 2   | 12.4500 | 9.3507  | 163.00 | 4.90     |
| 3   | 14.1450 | 5.1420  | 85.00  | -11.45   |

**Table 2: Transmission Line Characteristics**

| From Bus | To Bus | R (pu/m) | X (pu/m) | B (pu/m) |
| -------- | ------ | -------- | -------- | -------- |
| 4        | 5      | 0.0100   | 0.0680   | 0.1760   |
| 4        | 6      | 0.0170   | 0.0920   | 0.1580   |
| 5        | 7      | 0.0320   | 0.1610   | 0.3060   |
| 6        | 9      | 0.0390   | 0.1738   | 0.3580   |
| 7        | 8      | 0.0085   | 0.0576   | 0.1490   |
| 8        | 9      | 0.0119   | 0.1008   | 0.2090   |

**Table 3: Load Characteristics**
*(Details as provided in project)*

**Table 4: Transformer Data**

| From Bus | To Bus | Transformer | Tapping | Reactance |
| -------- | ------ | ----------- | ------- | --------- |
| 1        | 4      | T1          | 33      | 0.0576    |
| 2        | 7      | T2          | 33      | 0.0625    |

---

### **Experiment 02**

### 📝 Aim

a) Construct **Y-Bus** of a 9-bus system using MATLAB.
b) Construct **Y-Bus** of a 9-bus system using PSS/E (Raw file from Experiment 01).
c) Calculate the **Sparsity** of Y-Bus.

### Software

* MATLAB
* PSS/E

### Theory

* Difference between MATLAB and PSS/E software for Y-Bus construction.

---

### **Experiment 03**

### 📝 Aim

To perform and solve the **Load Flow Studies** of the given 9-bus power system using **Gauss-Seidel Method** in MATLAB and PSS/E.

---

### **Experiment 04**

### 📝 Aim

To perform and solve the **Load Flow Studies** of the given 9-bus power system using **Newton-Raphson Method** in MATLAB and PSS/E.

### Software

* MATLAB
* PSS/E

### Theory

* Load flow studies using Newton-Raphson Method.

---

### **Experiment 05**

### 📝 Aim

a) To perform load flow studies using **Fixed Slope Decoupled Newton-Raphson Method** in MATLAB and PSS/E.
b) To compare the **convergence characteristics, voltage, angle, and power profiles** of:

* Gauss-Seidel
* Newton-Raphson
* Fixed Slope Decoupled NR

📊 Results are plotted in one graph for comparison.

---

### **Experiment 07**

### 📝 Aim

To perform **Dynamic Analysis** of a 9-bus power system by creating a **Trip Line between Bus 8 and Bus 7** in PSS/E software.

<p align="center">
  <img width="527" height="504" alt="Dynamic Analysis Result" src="https://github.com/user-attachments/assets/a26ea753-a4e2-4712-bf97-4a2306af6c81" />
</p>  

---

## ⚙️ Software Used

* Siemens **PSS/E**
* **MATLAB**
