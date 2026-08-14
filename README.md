# SQUID-CPW Bolometer

Design and simulation of a cryogenic bolometer with SQUID-based readout,
developed as part of the KIT practical course
*Design und Entwurf von Quantenschaltkreisen*.

The project combines microwave resonator design, superconducting circuit
simulation and layout integration for the detection of electromagnetic
radiation at cryogenic temperatures.

## Project Overview

The bolometer consists of a frequency-selective CPW resonator coupled to
a thermally isolated sensing element and a dc-SQUID readout circuit.

**6 GHz λ/2 CPW resonator**

<img width="700" height="300" alt="Resonator with coupled capacitors and termination resistor" src="https://github.com/user-attachments/assets/d7da730b-077e-4b14-a25a-3ef0b7c54086" />

**dc-SQUID and input coil**

<img width="700" height="350" alt="dc-SQUID circuit with thermal coupling to the waveguide" src="https://github.com/user-attachments/assets/0f3aab9e-b3ca-471c-9a76-f3dc2de4054f" />

**Integrated bolometer layout**

<img width="700" height="200" alt="Integrated bolometer" src="https://github.com/user-attachments/assets/51eca074-cc97-46ce-b4f7-90017797f73a" />

The main design tasks included:

- Design and EM simulation of a **6 GHz λ/2 CPW resonator** using **Sonnet**
- Analysis of **characteristic impedance and S-parameters**
- Design of the **dc-SQUID and inductively coupled input coil** using **KLayout**
- Calculation of self- and mutual inductances using **InductEx**
- Simulation of the Josephson-junction circuit using **JSIM**
- Integration of the individual components into the complete bolometer layout
- Evaluation of simulation results using **MATLAB and Python**

## Tools

| Task | Software |
|---|---|
| Microwave / EM simulation | Sonnet |
| SQUID layout | KLayout |
| Inductance extraction | InductEx |
| Josephson circuit simulation | JSIM |
| Data analysis | MATLAB, Python |

## Technical Report

A detailed description of the design process, simulations and results
is available in the [technical report](./SQUID_CPW_Bolometer_Report.pdf).

## Authors

Erinç Gökgöz and Pujan Karehroudi
