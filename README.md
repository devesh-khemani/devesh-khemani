# Devesh Khemani

**Electrical and Electronic Engineering Undergraduate** | Imperial College London  
[Download Full CV (PDF)](./Devesh_Khemani_CV.pdf)

---

## Education

**Imperial College London** (2025 – 2028)  
*BEng Electrical and Electronic Engineering* | **Predicted: 2:1**  
*Relevant Modules:* Control Systems, Signal and Systems, Communications, Electromagnetism, Circuits and Systems  

**King Edward VI Camp Hill Grammar School for Boys** (2024)  
*A-Levels:* Mathematics ($A^*$), Physics ($A^*$), Computer Science ($A^*$)

---

## Technical & Research Projects

### Mixed-Signal Electro-Optical LoS Tracker & Inertially Stabilised Platform
*STM32F4, Embedded C++, Simulink, KiCad, LTspice, MPU-6050 IMU* (Jun 2026 – Sep 2026)
* Engineered an inertially stabilised platform using a 200 Hz C++ complementary filter fusing MPU-6050 gyroscope and accelerometer data.
* Modeled servomechanism dynamics in Simulink; tuned a discrete-time PID loop (1 ms sample period) to reduce settling time by 35% with <5% overshoot.
* Applied IMU angular-rate feed-forward in model-in-the-loop (MIL) simulation with kinematic disturbance rejection.
* Deployed a 1 kHz closed-loop PID controller in C++ on STM32F4, achieving <3.3° tracking accuracy in software-in-the-loop (SIL) evaluation.
* Designed a 4-channel optical front-end in LTspice, featuring a 38 kHz 4th-order Sallen-Key bandpass filter and LM393 Schmitt trigger (73 dB ambient rejection).
* Routed and bench-tested a custom mixed-signal PCB in KiCad isolating sensitive analog stages from PWM transients.

### Autonomous Systems & Sensing in Contested Electromagnetic Environments
*Independent Research & Simulation | Python, Bayesian Sensor Fusion, NumPy* (Oct 2022 – Sep 2023)
* Researched navigation and tracking resilience against GPS spoofing, RF jamming, and degraded sensor telemetry.
* Developed a multi-sensor Bayesian fusion simulation across thermal and optical channels in Python, modeling quadrature noise to reduce target state uncertainty by ~30%.
* Formulated confidence-threshold fail-safe criteria and human-in-the-loop authorization gates for autonomous actuation.

### Teleoperated Lunar Exploration Rover
*Embedded C++, ARM Cortex-M0+, LTspice, Sensor Interfacing* (May 2026 – Jun 2026)
* Co-developed a teleoperated exploration rover for real-time rock classification using IR, magnetic, ultrasonic, and RF sensing in a 5-person team.
* Designed and simulated analog front-ends in LTspice for 950 nm IR and Hall-effect sensors, rejecting 100 Hz ambient lighting using active filtering and an MCP6022 gain stage.
* Implemented embedded C++ routines on an ARM Cortex-M0+ to acquire 10-bit ADC telemetry with zero false positives across 11 test trials.

---

## Technical Skills

* **Navigation & Control:** Sensor Fusion (Complementary / Kalman Filtering), PID Control, IMU Interfacing, Closed-Loop Stabilisation
* **Hardware & Embedded:** Embedded C/C++ (STM32F4, ARM Cortex-M0/M4), Transimpedance Amplifiers, Sallen-Key Filters, Mixed-Signal PCB Layout (KiCad 7), Hardware Timers, ADC Sampling, PWM
* **Simulation & Tools:** LTspice, Simulink, MATLAB, Fusion 360, Python (NumPy), Linux, Git
* **Lab & Testing:** Digital Storage Oscilloscopes (DSO), Function Generators, Logic Analysers, Multimeters, SMD Soldering & Rework
