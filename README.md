# 📊 Using FFT in an Oscilloscope – Practical DSP Application

## 📌 Project Overview

This project explains how the **Fast Fourier Transform (FFT)** is practically used in a **digital oscilloscope** to analyze real-world electrical systems. The study bridges the gap between **Signals & Systems / DSP theory** and **hands-on engineering diagnostics**, using a **refrigerator compressor current signal** as a real application example.

The work demonstrates why the theoretical **Fourier Transform (FT/DTFT)** cannot be directly implemented in hardware and how the **FFT algorithm (efficient DFT computation)** is used instead in modern oscilloscopes and embedded systems.

---

## 🎯 Objectives

- Understand why FFT is used instead of FT / DTFT in real instruments  
- Connect DSP theory to practical signal measurement  
- Analyze real signals in the **frequency domain**  
- Identify harmonics, noise, and non-linear effects using FFT  
- Learn how oscilloscopes internally process sampled data using FFT  
- Apply FFT for **fault diagnosis of electric motors/compressors**

---

## 🧠 Key Concepts Covered

- Fourier Transform vs DTFT vs DFT  
- Fast Fourier Transform (FFT) algorithm  
- Sampling theory and ADC  
- Time-domain vs Frequency-domain analysis  
- Harmonics caused by nonlinearity  
- High-frequency noise from switching circuits  
- Mechanical vibration analysis using FFT  
- Fault diagnosis using frequency signatures  

---

## ⚙️ Tools & Technologies

- Digital Oscilloscope (FFT mode)  
- ADC & Sampling Theory  
- Signal Processing Concepts (DSP)  
- Frequency Spectrum Analysis  

---

## 🧪 Methodology

1. Considered the **compressor current signal** as a real-world analog signal  
2. Sampled the signal using ADC (as done in oscilloscopes)  
3. Observed the **time-domain waveform**  
4. Applied **FFT** to convert the signal to the frequency domain  
5. Identified:
   - Fundamental frequency  
   - Harmonics (2nd, 3rd, 4th, etc.)  
   - High-frequency noise components  
6. Related observed frequency components to:
   - Electrical nonlinearity  
   - Mechanical vibration  
   - Switching noise  
7. Used frequency signatures for **fault diagnosis**

---

## 📊 Key Observations

- Time-domain waveforms can hide faults and distortions  
- FFT reveals:
  - Harmonics caused by non-linear loads  
  - Noise from SMPS and switching devices  
  - Mechanical vibration frequencies  
- FFT enables early detection of:
  - Capacitor faults  
  - Relay issues  
  - Rotor imbalance  
  - Inverter/switching failures  
- FFT is computationally efficient and suitable for **real-time analysis**

---

## 🚀 Why This Project Matters

This project demonstrates how **pure mathematical DSP concepts** are implemented in real instruments used by engineers. It directly connects university theory with:

- Power quality analysis  
- Motor and compressor diagnostics  
- EMI/EMC investigations  
- Predictive maintenance  
- Embedded DSP applications  

This makes FFT one of the **most important practical tools in electrical, electronics, and telecommunication engineering**.

---

## 🔮 Future Improvements

- Perform FFT analysis using MATLAB / Python on real oscilloscope data  
- Implement FFT on a microcontroller (ARM / ESP32)  
- Compare windowing functions and spectral leakage  
- Build a small vibration monitoring system using FFT  
- Automate fault detection using ML on FFT features  

---

## 📄 Reference Document

This repository is based on the technical report:

**“Using FFT in an Oscilloscope – Practical DSP Application”**  
Author: Tharindu Navodya  
Date: December 27, 2025  

---

## 🧑‍💻 Author

**Tharindu Navodya**  
Electronics & Telecommunication Engineering Undergraduate  
Interests: DSP, RF, Embedded Systems, Control Systems, Robotics  
