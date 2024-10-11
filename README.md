# **Patch Antenna Design (1-5 GHz Range) with Future Machine Learning Integration**
![Screenshot (396)](https://github.com/user-attachments/assets/af775c82-6bf4-4d9d-b321-0dcbf5072aed)

![Screenshot (418)](https://github.com/user-attachments/assets/7c85badc-96a7-4a59-a726-2ead52ac903a)


![Screenshot (412)](https://github.com/user-attachments/assets/3fb07a91-95b5-4023-8a16-536ba65ca43c)



# Project Overview

This project involves the design, simulation, and optimization of a rectangular patch antenna operating in the 1-5 GHz frequency range using CADFEKO 2022. The primary objective is to achieve efficient radiation and minimal return loss, particularly around 2.5 GHz. The project also explores patch antenna integration at different positions along the feedline, with the middle position yielding the best performance. Future work will focus on optimizing the design using machine learning techniques.

## Design Specifications
- **Frequency Range**: 1 GHz to 5 GHz
- **Software Used**: CADFEKO 2022
- **Design Type**: Rectangular patch antenna
- **Objective**: Achieve high performance with minimal return loss in the target frequency range.

### Key Components and Parameters

- **S-Parameter (S11)**: Measures reflected energy. A dip at 2.5 GHz with S11 = -25 dB indicates excellent performance, with minimal energy reflection.
- **Frequency Sweep**: Covers 1 GHz to 5 GHz to identify resonance frequencies.
- **Reference Impedance**: Set to 50 ohms to match the transmission line, ensuring maximum power transfer.
- **Voltage Source**: Matched to the antenna's impedance for optimal performance.
- **Mesh Model**: A refined mesh improves simulation accuracy.
- **Ground Plane**: Enhances radiation pattern and directivity.

## Simulation Results

- **Resonant Frequency**: ~2.5 GHz
- **Return Loss (S11)**: Strong resonance at -25 dB near 2.5 GHz, with minimal reflection.
- **Bandwidth**: Effective performance derived from the -10 dB points on the S11 curve.

## Antenna Placement Results
- Different antenna feed points (70%, 30%, start, end, middle) were simulated.
- The **middle placement** produced the best result, with the most efficient radiation and the lowest return loss, as shown in the performance graph.

## Future Work: Machine Learning Integration

- **Optimize Design**: ML will predict optimal patch size, feed point, and substrate material for improved performance.
- **Automate Parameter Tuning**: Algorithms will suggest the best design parameters based on previous simulations.
- **Reduce Simulation Time**: ML will decrease the number of required simulations, speeding up the design process.

## How to Use

1. Open the `.fek` file in CADFEKO.
2. Run simulations to view return loss, radiation patterns, and other metrics.
3. Future updates will integrate machine learning models to automate and optimize design further.
