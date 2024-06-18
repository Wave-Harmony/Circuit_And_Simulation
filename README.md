# Real Time Audio Spectrum Analyzer

## Discussion - Filter

---

### File
This repo contains many files related to the experiments that we have done.
The simulation file related to following resluts are given at tha path

WaveHarmoney/Circuit_And_Simulation/Simulations/Filters.asc

---

### Filter Type
We constructed 10 Band Pass Filters (BPFs) for this project. Each filter has the following specifications:
- **Filter Response**: Butterworth
- **Circuit Topology**: Multiple Feedback (MFB)
- **Gain (a)**: 2
- **Q factor (Q)**: 4
- **Capacitor Value (C)**: 10nF

![Capture7](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/fc1f038a-f2d3-45eb-b379-b43aec21d33e)

---

### Calculations
Using software, we determined the values for the remaining circuit components (R1, R2, R3). The software-generated values are presented below.

![Capture](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/328bdd59-d260-4407-832f-706940fab105)
![Capture2_2](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/54cb94eb-e26c-47f1-861e-b77927ae5a9c)

However, we couldn't find resistors with the exact values given by the software, so we selected the closest available resistor values.

![Capture2_1](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/f7b2c0c7-9856-41eb-b7b0-38569618ba83)

---

### Simulation Results
We performed simulations using LTSpice circuit simulation tool. The simulation results for the 10 filters, using the selected resistor values, are included in the following figures.

![Capture5](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/ac3122b6-5987-4566-8477-98a3c84aab75)

![Capture3](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/789557cd-6775-45cc-b17b-6fb1714a0ffb)
![Capture4](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/41a5b51e-c46f-4c25-a34c-5724f56e262a)




---

### Note
The figures mentioned are intended to provide visual aids for the discussion and results.

---

This README provides a comprehensive overview of the filter design and simulation process for the Real Time Audio Spectrum Analyzer project. For more details, please refer to the full documentation and figures.
