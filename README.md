# SRAM Performance Analysis using Cadence Virtuoso

## Overview

This project presents the design, simulation, and analysis of a 6T SRAM cell using Cadence Virtuoso. The SRAM cell was implemented and characterized in both 90nm (gpdk090) and 180nm (gpdk180) CMOS technology nodes.

The work includes:

* Voltage Transfer Characteristic (VTC) Analysis
* Static Noise Margin (SNM) Analysis
* Read and Write Transient Simulations
* Stacking Effect for Leakage Reduction
* Power Consumption Analysis
* Layout Design and Verification
* Read-Write Block Design using Tristate Inverter
* Latch-Type Sense Amplifier Design
* Comparative Analysis of 90nm and 180nm Technologies

---

## Design Methodology

Cadence Virtuoso and Spectre Simulator were used for schematic capture, simulation, and layout design.

Technology Nodes:

* gpdk090 (90nm)
* gpdk180 (180nm)

Analysis Performed:

* DC Analysis
* Transient Analysis
* Power Analysis
* SNM Analysis
* Layout Verification

---

## 6T SRAM Cell – 90nm

### Schematic

![90nm SRAM](images/01_90nm_schematic.png)

### Symbol

![90nm Symbol](images/02_90nm_symbol.png)

### Voltage Transfer Characteristic (VTC)

![90nm VTC](images/03_90nm_vtc.png)

### Butterfly Curve (SNM)

![90nm Butterfly Curve](images/04_90nm_butterfly_curve.png)

### Read Operation with Precharge

![90nm Read Waveform](images/05_90nm_read_waveform.png)

### Stacking Effect Analysis

![Stacking Schematic](images/06_90nm_stacking_schematic.png)

![Stacking Power](images/07_90nm_stacking_power.png)

### Power Analysis

![90nm Power](images/08_90nm_power_analysis.png)

---

## 6T SRAM Cell – 180nm

### Schematic

![180nm SRAM](images/09_180nm_schematic.png)

### Write Operation

![180nm Write](images/10_180nm_write_waveform.png)

### Voltage Transfer Characteristic

![180nm VTC](images/11_180nm_vtc.png)

### Butterfly Curve

![180nm Butterfly](images/12_180nm_butterfly_curve.png)

### Layout

![180nm Layout](images/13_180nm_layout.png)

### Transient Analysis

![180nm Transient](images/14_180nm_transient_analysis.png)

### Power Analysis

![180nm Power](images/15_180nm_power_analysis.png)

### Average Power Calculation

![Average Power](images/16_180nm_average_power.png)

---

## Read-Write Block using Tristate Inverter

### NOT CMOS Gate

![NOT CMOS](images/17_not_cmos_schematic.png)

### NOT CMOS Symbol

![NOT CMOS Symbol](images/18_not_cmos_symbol.png)

### Tristate Inverter

![Tristate](images/19_tristate_inverter.png)

### Tristate Symbol

![Tristate Symbol](images/20_tristate_symbol.png)

### Read Write Block

![Read Write Block](images/21_read_write_block.png)

### Read Write Symbol

![Read Write Symbol](images/22_read_write_symbol.png)

### Full Read Write Simulation

![Full Simulation](images/23_full_read_write_waveform.png)

---

## Latch-Type Sense Amplifier

### Symbol

![Sense Amplifier Symbol](images/24_sense_amp_symbol.png)

### Schematic

![Sense Amplifier Schematic](images/25_sense_amp_schematic.png)

---

## Comparative Analysis

| Parameter           | 90nm    | 180nm  |
| ------------------- | ------- | ------ |
| VDD                 | 1.2V    | 1.8V   |
| Switching Threshold | ~0.70V  | ~0.75V |
| Leakage             | Higher  | Lower  |
| Dynamic Power       | Lower   | Higher |
| SNM                 | Smaller | Larger |
| Density             | Higher  | Lower  |

---

## Key Findings

* Positive SNM was observed in both technology nodes.
* 180nm exhibited higher noise immunity and larger SNM.
* 90nm achieved higher density and lower dynamic power.
* Stacking significantly reduced leakage current.
* The SRAM cell successfully performed write, hold, precharge, and read operations.

---

## Tools Used

* Cadence Virtuoso
* Spectre Simulator
* gpdk090
* gpdk180

---

## Report

The complete project report is available in the `reports` folder.
