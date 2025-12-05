# Interpretation of Band Gap Tuning for Silicon Nanowire (SiNW) Solar Cell  
**Author:** Maharathi Karan (122EE0151)  
**Guide:** Prof. Paresh G. Kale  
**Department of Electrical Engineering, NIT Rourkela**

---

## 📌 Project Overview
Silicon nanowire (SiNW) solar cells offer strong optical absorption, light trapping, and high carrier collection efficiency. However, their large surface-to-volume ratio introduces surface recombination losses.  
This project investigates **bandgap tuning of the SiNW emitter layer** and its effect on the electrical performance of heterojunction SiNW solar cells using **SCAPS-1D simulations**.

The bandgap is varied from **1.1 eV to 1.9 eV**, and its impact on:
- Open-circuit voltage (Voc)  
- Short-circuit current (Jsc)  
- Fill Factor (FF)  
- Efficiency (η)  
- EQE spectrum  
is analyzed.

---

## 📚 Abstract
This study examines how tuning the bandgap of the n-type SiNW emitter improves the photovoltaic performance of heterojunction solar cells. Using experimentally reported recombination parameters, SCAPS-1D simulations reveal that increasing the bandgap significantly enhances **Voc** and **FF**, while **Jsc remains nearly constant** due to efficient optical absorption in the nanowire structure.  
An optimum bandgap of **~1.5 eV** is identified, yielding the best device performance with minimum recombination losses.

---

## 🧪 Simulation Setup  
Simulation performed using **SCAPS-1D v3.3.11**.  
The device includes:  
- **n-layer (SiNW)** – Bandgap varied from 1.1–1.9 eV  
- **p-layer (Si)**  
- **p+ Back Surface Field (BSF)**  

A full parameter table is available in the project report (see `/docs/report.pdf`).  
SCAPS solves Poisson and continuity equations to extract **I–V**, **Jsc**, **Voc**, **FF**, **η**, and **EQE**.

### 📘 Structure Diagram  
*(Refer to Fig. 2 in the report)*

---

## 📊 Results & Discussion  

### **1️⃣ Voc & Jsc vs Bandgap**  
- Voc increases sharply with bandgap and saturates near **1.5 eV**.  
- Jsc remains nearly constant (~26.6 mA/cm²).  
- Wider bandgaps (>1.5 eV) do not provide additional benefit due to increased recombination.

### **2️⃣ FF & Efficiency vs Bandgap**  
- Both FF and η increase rapidly with bandgap up to **1.5 eV**.  
- Maximum performance:  
  - **Voc = 0.93 V**  
  - **FF = 87.6%**  
  - **η = 21.7%**

### **3️⃣ J–V Characteristics**  
Comparison between bandgaps:  
- **1.1 eV:** Voc = 0.68 V, η = 15.2%  
- **1.5 eV:** Voc = 0.93 V, η = 21.7%  

### **4️⃣ EQE Spectrum (for Eg = 1.5 eV)**  
- Low response below 450 nm (surface recombination).  
- EQE > 80% in 600–900 nm indicating strong carrier collection.

---

## 🧾 Conclusion  
Bandgap engineering significantly strengthens the electronic quality of SiNW solar cells.  
The optimal emitter bandgap is **1.5 eV**, producing higher Voc, FF, and overall efficiency while maintaining stable Jsc.  

This demonstrates that **SiNW bandgap tuning is a powerful method to overcome recombination limitations and enhance next-generation photovoltaic devices**.

---

## 📂 Repository Structure (Recommended)

