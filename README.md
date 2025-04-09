# Deep-reinforcement-learning-for-PMUT-inverse-design

This repository contains the code, models, and documentation for the paper:

"Inverse Design of PMUT Using Deep Reinforcement Learning with a View to Customized Operating Frequency and Broadened Bandwidth"
Jiapeng Xu, Zhou Da, Gabriele Schrag, Jeremy Streque, Tingzhong Xu

📌 Overview
This project presents a deep reinforcement learning (DRL) framework for the inverse design of Piezoelectric Micromachined Ultrasonic Transducers (PMUTs). Unlike traditional circular or rectangular designs, our method autonomously generates non-standard diaphragm geometries that optimize:

🎯 Target resonance frequency (±0.1 MHz accuracy)

📡 Enhanced -3dB fractional bandwidth (up to 113.7%)

🛠️ Fabrication feasibility

🚀 Key Contributions
DRL-based optimization cycle for PMUT geometry

Surrogate model for predicting frequency and bandwidth

Experimental validation with a fabricated 40-channel array

Strategy to mitigate crosstalk via dual-frequency integration

🧱 Technologies Used
Deep Reinforcement Learning (Actor-Critic model)

Parametric geometry generation

Surrogate modeling (based on FEM data)

Experimental characterization (LDV, FFT, hydrophone)

🧪 Results
113.7% bandwidth (6.6× over circular cells)

Validated eigenmodes and acoustic performance

Robust design-to-fabrication pipeline

📄 Paper
A full version of the paper is included in this repository: INVERSE DESIGN.pdf

👥 Authors & Contact
For questions or collaboration opportunities, contact:
📧 jiapeng.xu@silicon-austria.com
📧 tingzhong.xu@silicon-austria.com


© 2025 IEEE. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses, in any current or future media, including reprinting/republishing this material for advertising or promotional purposes, creating new collective works, for resale or redistribution to servers or lists, or reuse of any copyrighted component.

This is the accepted version of the paper: "INVERSE DESIGN OF PMUT USING DEEP REINFORCEMENT LEARNING WITH A VIEW TO CUSTOMIZED OPERATING FREQUENCY AND BROADENED BANDWIDTH." To appear in 2025 IEEE Transducers. The final version will be available at: https://ieeexplore.ieee.org/
