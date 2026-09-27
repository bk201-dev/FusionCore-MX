<div align="center">

# FusionCore MX

### 4-Layer STM32 Mixed-Signal Control Platform

**Ethernet • Precision Acquisition • Motor Control • Audio • USB • Onboard Debugging**

</div>

---

## Overview

FusionCore MX is a custom 4-layer mixed-signal embedded platform built around the STM32F407.

The project explores the integration of multiple electrical domains on a single PCB, combining high-speed digital communication, precision analog acquisition, motor-control power electronics, audio circuitry, USB connectivity, and onboard debugging.

The board was designed in Altium Designer with particular attention to component placement, return-current paths, power distribution, signal integrity, mixed-signal partitioning, and manufacturability.

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
