# Quadrature Down Converter Design and Implementation

> Analog Electronic Circuits (EC2.103) Course Project  
> Spring 2025, IIIT Hyderabad

## Team Name - Non-Operational Amplifiers
1. **Nagamalla Sai Abhinav**
   - Roll No: 2024102037
   - Email : saiabhinav.nagamalla@students.iiit.ac.in
2. **Nikhil Venkat Atkuru**
   - Roll No: 2024102039
   - Email : nikhil.atkuru@students.iiit.ac.in
3. **Abhinav Venkata Kota**
   - Roll No: 2024102059
   - Email : abhinav.kota@students.iiit.ac.in

## Overview

This project focuses on designing a Quadrature Down Converter for RF signal processing. It converts highfrequency RF signals to low-frequency baseband signals using I/Q demodulation.

## Main Theme
The system employs mixers, local oscillators, and low-pass filters to extract in-phase and quadrature components.

1. **Quadrature Oscillator** - Generates orthogonal local oscillator (LO) signals using Op-Amp topology and Automated Gain Control (AGC).
2. **Mixer** - Perform the multiplication of high-frequency radio signal (RF) and LO signals using an NMOS device operating in linear mode.
3. **Low Pass Filter** - Extracts the desired IF/baseband signals.

The paper named "Report.pdf" contains in-depth report of the design procedure of the circuit made and all the plots.

## Directory Structure

```
AEC_Project_Final/
├── README.md                           # Project documentation (This File)
├── Report.pdf                           # Complete LaTeX project report
├── TSMC_180nm.txt                     # MOSFET model file (required)
├── UA741.301                          # Op-amp model file (required)
├── LTSpice Schematics/                 # All LTSpice files
├── Resources/                         # List of all the resources used
├── Mid Eval PPT                         # PPT used for the project mid evaluations
└── Problem statement                # Project Problem statement
```
