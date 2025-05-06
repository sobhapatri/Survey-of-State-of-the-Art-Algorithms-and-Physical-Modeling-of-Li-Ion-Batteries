# Survey-of-State-of-the-Art-Algorithms-and-Physical-Modeling-of-Li-Ion-Batteries

This project presents a comprehensive analysis of Battery Management Systems (BMS) using MATLAB/Simulink. The focus lies on state-of-the-art algorithms for estimating State of Charge (SOC), State of Health (SOH), State of Power (SOP), cell balancing, fault diagnosis, and thermal management. A physics-based modeling approach is used, further integrated with machine learning methods to improve robustness, accuracy, and adaptability.

## 📌 Project Overview

- Developed detailed lithium-ion battery models using Simscape Battery and Simscape Electrical.
- Simulated real-world behavior across thermal, electrical, and electrochemical domains.
- Implemented and evaluated SOC and SOH estimation algorithms.
- Explored cell balancing, fault detection, and predictive thermal control.
- Integrated Kalman filtering, Model Predictive Control (MPC), and Hybrid BMS strategies with ML support.

## 🔬 Objectives

- Survey and evaluate advanced BMS algorithms.
- Design and simulate a lithium-ion battery model on MATLAB/Simulink and Simscape.
- Accurately estimate key battery parameters like SOC, SOH, SOP.
- Explore hybrid modeling approaches using machine learning for adaptive optimization.

## 🧪 Methodology

- **Modeling Platform:** MATLAB/Simulink (Simscape Battery, Simscape Electrical)
- **Battery Chemistry:** Lithium-ion
- **Design Type:** Equivalent Circuit Model (ECM) with 3-cell x 10-parallel configuration
- **Key Features:**
  - Electrochemical + Thermal Modeling
  - SOC Estimation (Coulomb Counting + EKF)
  - Real-time Fault Detection via Kalman Filtering
  - MPC for Predictive Thermal Regulation

## 📈 Results

- **Thermal Management:** Achieved stable thermal behavior under varying load using predictive control.
- **SOC Estimation:** Improved accuracy by integrating correction algorithms with Coulomb Counting.
- **SOH Degradation:** Captured realistic degradation profiles over repeated charge/discharge cycles.
- **Fault Diagnosis:** Incorporated intelligent fault detection using simulated failure scenarios.
- **Simulation Plots:** Voltage, temperature, SOC trends demonstrate robust model behavior.

## 🧠 Insights

- Hybrid models combining physics-based frameworks and ML lead to more scalable and intelligent BMS systems.
- Thermal safety and fault-tolerance are essential in high-performance battery applications like EVs.
- Tools like Simscape Battery enable flexible, high-fidelity modeling from cell-level to pack-level.


