# SRAM Performance Analysis using Cadence Virtuoso

## Overview

This project presents the design and performance analysis of a 6T SRAM cell using Cadence Virtuoso. The SRAM cell was implemented and analyzed in both 90nm and 180nm CMOS technologies.

### Objectives

* Analyze Static Noise Margin (SNM)
* Study Read and Write Operations
* Evaluate Power Consumption
* Investigate Leakage Reduction using Stacking
* Compare 90nm and 180nm Technologies
* Design Read-Write Block and Sense Amplifier

---

## Tools Used

* Cadence Virtuoso
* Spectre Simulator
* gpdk090 Technology
* gpdk180 Technology

---

# 90nm SRAM Analysis

## SRAM Schematic

![90nm SRAM](images/90nm_Analysis/01_90nm_schematic.png)

## SRAM Symbol

![90nm Symbol](images/90nm_Analysis/02_90nm_symbol.png)

## Voltage Transfer Characteristic (VTC)

![90nm VTC](images/90nm_Analysis/03_90nm_vtc.png)

## Butterfly Curve (SNM)

![90nm Butterfly Curve](images/90nm_Analysis/04_90nm_butterfly_curve.png)

## Read Operation with Precharge

![90nm Read Operation](images/90nm_Analysis/05_90nm_read_waveform.png)

## Stacking Effect Circuit

![Stacking Schematic](images/90nm_Analysis/06_90nm_stacking_schematic.png)

## Stacking Effect Analysis

![Stacking Power](images/90nm_Analysis/07_90nm_stacking_power.png)

## Power Analysis

![90nm Power Analysis](images/90nm_Analysis/08_90nm_power_analysis.png)

---

# 180nm SRAM Analysis

## SRAM Schematic

![180nm SRAM](images/180nm_Analysis/09_180nm_schematic.png)

## Write Operation

![180nm Write Operation](images/180nm_Analysis/10_180nm_write_waveform.png)

## Voltage Transfer Characteristic

![180nm VTC](images/180nm_Analysis/11_180nm_vtc.png)

## Butterfly Curve

![180nm Butterfly Curve](images/180nm_Analysis/12_180nm_butterfly_curve.png)

## Layout Design

![180nm Layout](images/180nm_Analysis/13_180nm_layout.png)

## Transient Analysis

![180nm Transient Analysis](images/180nm_Analysis/14_180nm_transient_analysis.png)

## Power Analysis

![180nm Power Analysis](images/180nm_Analysis/15_180nm_power_analysis.png)

## Average Power Calculation

![180nm Average Power](images/180nm_Analysis/16_180nm_average_power.png)

---

# Read-Write Block Design

## CMOS NOT Gate

![NOT CMOS](images/Read-Write_Block/17_not_cmos_schematic.png)

## CMOS NOT Symbol

![NOT CMOS Symbol](images/Read-Write_Block/18_not_cmos_symbol.png)

## Tristate Inverter

![Tristate Inverter](images/Read-Write_Block/19_tristate_inverter.png)

## Tristate Inverter Symbol

![Tristate Symbol](images/Read-Write_Block/20_tristate_symbol.png)

## Read-Write Block

![Read Write Block](images/Read-Write_Block/21_read_write_block.png)

## Read-Write Block Symbol

![Read Write Symbol](images/Read-Write_Block/22_read_write_symbol.png)

## Read-Write Operation Simulation

![Read Write Simulation](images/Read-Write_Block/23_full_read_write_waveform.png)

---

# Sense Amplifier Design

## Sense Amplifier Symbol

![Sense Amplifier Symbol](images/Sense_Amplifier/24_sense_amp_symbol.png)

## Sense Amplifier Schematic

![Sense Amplifier Schematic](images/Sense_Amplifier/25_sense_amp_schematic.png)

---

# Comparative Analysis

| Parameter       | 90nm Technology | 180nm Technology |
| --------------- | --------------- | ---------------- |
| Supply Voltage  | 1.2V            | 1.8V             |
| Device Density  | Higher          | Lower            |
| Leakage Current | Higher          | Lower            |
| Dynamic Power   | Lower           | Higher           |
| Noise Margin    | Lower           | Higher           |
| Area            | Smaller         | Larger           |

---

# Key Findings

* The 6T SRAM cell successfully performs read, write, and hold operations.
* Static Noise Margin was verified using butterfly curve analysis.
* Stacking effect reduces leakage current significantly.
* 180nm technology provides better stability and larger SNM.
* 90nm technology provides higher density and reduced area.
* Trade-offs exist between stability, power, and scalability.

---

# Report

The complete project report is available in:

`reports/SRAM_Final_Report.pdf`
