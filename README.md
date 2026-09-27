# PSpice Circuit Simulation

A PSpice-based circuit analysis project covering both **DC steady-state analysis** and **RLC transient response**. The work includes circuit construction, operating-point simulation, current and voltage measurements, power analysis, and interpretation of simulation waveforms.

## Project Overview

This project contains two circuit-analysis problems completed using PSpice.

### Problem 1 — DC Steady-State Circuit

The first circuit contains resistors, independent current sources, and a DC voltage source.

The simulation was used to determine:

- Voltage across the current-source branch
- Branch currents
- Output current through the 2 kΩ resistor
- Power associated with the DC voltage source
- Steady-state waveform behavior

### Simulation Results

| Quantity | Result |
| --- | ---: |
| V2 | 21.44 V |
| I0 | 777.78 µA |
| I1 | 3.154 mA |
| I2 | 1.222 mA |
| I3 | 4.846 mA |

Because the circuit uses DC sources and is analyzed at steady state, the measured voltages, currents, and source power remain constant with time.

### Problem 2 — RLC Transient Circuit

The second problem studies the transient response of a switched RLC circuit.

The switch is initially open and closes at:

```text
t = 0.3 s
```

The simulation examines:

- Inductor current `iL(t)`
- Output current `io(t)`
- Capacitor voltage `vC(t)`
- Energy transfer after switching
- Transition toward steady state

After the switch closes, the inductor and capacitor exchange energy. The current rises to a peak and then decays, while the capacitor voltage rises toward its steady-state value. Resistance dissipates stored energy, so the response does not exhibit sustained oscillation.

## Tools & Concepts

- PSpice
- DC operating-point analysis
- Transient analysis
- RLC circuits
- Resistors, capacitors, and inductors
- Current and voltage measurements
- Source power analysis
- Switching circuits
- Steady-state and transient response
- Circuit simulation and waveform interpretation

## Repository Contents

```text
pspice-circuit-simulation/
├── report/
│   └── ENEE2306_PSpice_Assignment.pdf
├── README.md
└── LICENSE
```

## Course

**ENEE2306 — Circuit Analysis / PSpice Assignment**  
Electrical & Computer Engineering Department  
Birzeit University

## What I Learned

This project strengthened my understanding of circuit simulation, DC steady-state behavior, transient RLC response, waveform interpretation, source power analysis, and the relationship between theoretical circuit behavior and simulation results.

## Author

**Ameer Daibes**  
Computer Engineering Student — Birzeit University

[LinkedIn](https://www.linkedin.com/in/ameer-daibes-1510aa207)
