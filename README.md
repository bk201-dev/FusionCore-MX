<p align="center">
  <img src="assets/renders/fusioncore_3d_iso.png" width="900">
</p>

<h1 align="center">FusionCore MX</h1>

<p align="center">
  <b>4-Layer STM32 Mixed-Signal Control Platform</b>
</p>

<p align="center">
  Ethernet • Precision Acquisition • Motor Control • Audio • USB • Onboard Debugging
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MCU-STM32F407-blue">
  <img src="https://img.shields.io/badge/PCB-4--Layer-green">
  <img src="https://img.shields.io/badge/EDA-Altium%20Designer-orange">
  <img src="https://img.shields.io/badge/Ethernet-DP83826-purple">
</p>

---

## Overview

FusionCore MX is a custom 4-layer mixed-signal embedded control platform built around the STM32F407.

The board brings together high-speed digital communication, precision analog acquisition, motor-control power electronics, audio circuitry, USB connectivity and onboard debugging on a single PCB.

The project was developed as a practical exploration of mixed-signal PCB design, with particular focus on:

- component placement
- return-current paths
- power distribution
- signal integrity
- analog/digital partitioning
- differential routing
- switching-current loops
- manufacturability

---

## Key Hardware

| Function | Implementation |
|---|---|
| Main MCU | STM32F407 |
| PCB | 4-Layer |
| Ethernet | DP83826 PHY + RJ45 |
| Precision ADC | ADS122C04 |
| Motor Control | 2× DRV8701E + external N-MOSFET stages |
| USB-UART | CH340C |
| Debug Interface | STM32F103 onboard debugger |
| Analog Acquisition | Load-cell interface |
| Audio | DAC + microphone interface |

---

> Full technical documentation, PCB renders, architecture diagrams and design files are being added.
