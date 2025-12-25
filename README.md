# DIY Optical Power Meter (ESP32 + Photodiode + MATLAB)

A low-cost optical power meter built using a silicon photodiode and a low-noise transimpedance amplifier, with data acquisition via ESP32 and calibration/analysis performed in MATLAB.  
This project focuses on **optical measurement accuracy**, **analog front-end design**, and **hardware–software integration**.

---

## Motivation

Commercial optical power meters are expensive and often opaque in how measurements are performed.  
This project explores how accurately optical power can be measured using off-the-shelf components while maintaining good engineering practice in analog design, calibration, and data analysis.

Key goals:
- Understand photodiode-based optical power measurement
- Design and debug a low-noise transimpedance amplifier (TIA)
- Calibrate raw voltage measurements to optical power
- Document the full system clearly and reproducibly

---

## System Overview

**Signal Chain**
