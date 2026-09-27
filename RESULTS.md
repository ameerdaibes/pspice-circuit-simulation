# Simulation Results

## Problem 1 — DC Steady-State Circuit

The submitted PSpice simulation produced the following operating-point values:

| Quantity | Result |
| --- | ---: |
| V2 | 21.44 V |
| I0 | 777.78 µA |
| I1 | 3.154 mA |
| I2 | 1.222 mA |
| I3 | 4.846 mA |

The circuit operates in DC steady state, so its measured voltages, currents, and source power remain constant with time.

The largest reported branch current is **I3 = 4.846 mA**, while the smallest reported branch current is **I2 = 1.222 mA**. The output current through the 2 kΩ resistor is **I0 = 777.78 µA**.

## Problem 2 — Switched RLC Transient Circuit

Before **t = 0.3 s**, the switch is open, isolating the capacitor and right-hand branch.

When the switch closes:

- the inductor and capacitor begin exchanging energy;
- the inductor current and output current rise to a peak and then decay;
- the capacitor voltage increases toward its steady-state value;
- resistor losses dissipate the stored energy;
- the response settles without sustained oscillation.

The transient simulation therefore demonstrates the transition from an initially isolated reactive branch to a stable post-switch steady state.
