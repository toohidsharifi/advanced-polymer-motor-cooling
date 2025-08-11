# Advanced Polymer Motor Cooling Simulations

This repository contains the simulation files for the paper: **"Improving the Water Jacket Cooling for Flywheel Energy Storage Systems: An Investigation on the Potting and Polyamide-imide/Boron Insulators"**.

**DOI:** [https://doi.org/10.1109/ICEMD64575.2024.10963552](https://doi.org/10.1109/ICEMD64575.2024.10963552)

### Repository Language: English

The study investigates using advanced potting and polymer materials to mitigate hotspots and improve 3-D temperature uniformity in an IPM motor for a Flywheel Energy Storage System (FESS). The goal is to enhance thermal performance without increasing the energy consumption of the water jacket cooling unit.

***

## 📊 Visual Results

The images below compare the thermal performance with and without the use of advanced materials.

### Case 1: Without Advanced Materials

The baseline configuration shows significant hotspots ($124^{\circ}C$) in the end windings and a large temperature difference ($35^{\circ}C$) between the middle and end parts of the windings.

| Axial View | Slot View |
| :---: | :---: |
| ![Axial temperature distribution without advanced materials](Images/Axial%20without%20advanced%20materials.png) | ![Slot temperature distribution without advanced materials](Images/Slot%20without%20advanced%20materials.png) |

### Case 2: With Advanced Materials

By using advanced materials like **CoolTherm TC-426** in the end spaces and **CoolTherm SC-320** in the slots, the hotspot temperature is reduced by over 30% to $83^{\circ}C$. This approach achieves superior thermal uniformity across the motor.

| Axial View | Slot View |
| :---: | :---: |
| ![Axial temperature distribution with advanced materials](Images/Axial%20with%20advanced%20materials.png) | ![Slot temperature distribution with advanced materials](Images/Slot%20with%20advanced%20materials.png) |

***

## ⚙️ System Specifications & Cost Analysis

The improved thermal performance allows for a significantly downsized cooling system, leading to lower energy consumption and weight, though at a higher initial capital cost.

| Specification | Without Advanced Materials | With Advanced Materials |
| :--- | :---: | :---: |
| **Inlet Flow Rate** (`l/min`) | 4.8 | 2.5 |
| **Pressure Drop** (`kPa`) | 14.09 | 4.69 |
| **Energy Consumption** (`kW.h`) | 2.46 | 0.82 |
| **Pump's Power Rate** (`kW`) | 2.46 | 0.82 |
| **Pump's Weight** (`kg`) | 80 | 65 |
| **Pump's Price** (`€`) | 1530 | 1180 |
| **Material's Weight** (`kg`) | 0 | 12.1 |
| **Material's Cost** (`$`) | 0 | 860 |
| **Total Weight** (`kg`) | **80** | **77.1** |
| **Total Capital Cost** (`$`) | **1530** | **2040** |

As the data shows, the cooling strategy with advanced materials is **3.6% lighter** and significantly more energy-efficient due to the lower required flow rate. However, the initial capital cost is **about 25% higher** because of the high price of the advanced materials themselves. This higher initial cost is offset by improved long-term reliability and reduced thermal stress on motor components.

***

## ⚙️ Accessing the Simulation Files

The thermal-fluidic simulation files for both cooling strategies are available in a password-protected ZIP archive.

To purchase access to the complete dataset and simulation models, please contact me at **hamidsharifi32@gmail.com**.
