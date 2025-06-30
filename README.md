
# FET-system-design
This document is the design specification of FSAEJ EV Testbed (FET).

## Table of Contents
- [FET-system-design](#fet-system-design)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
    - [1. Purpose](#1-purpose)
  - [System Requirements](#system-requirements)
    - [1. Regulatory Requirements](#1-regulatory-requirements)
    - [2. Functional Requirements](#2-functional-requirements)
    - [3. Non-Functional Requirements](#3-non-functional-requirements)
    - [4. User Interface Requirements](#4-user-interface-requirements)
    - [5. Documentetion / Training Requirements](#5-documentetion--training-requirements)
  - [Architecture](#architecture)
    - [1. Overall](#1-overall)
    - [2. Tractive System](#2-tractive-system)
    - [3. Shutdown System](#3-shutdown-system)
    - [4. GLV Power Supply System](#4-glv-power-supply-system)
    - [5. GLV System](#5-glv-system)
  - [Interfaces](#interfaces)
  - [Testing and Validation](#testing-and-validation)
  - [Appendices](#appendices)
    - [1. Glossary](#1-glossary)
    - [2. References](#2-references)
    - [3. Revision History](#3-revision-history)


## Overview
The FSAEJ EV Testbed (FET) is a compact electrical system that replicates key elements of a FSAEJ Electric Vehicle.  
It is designed to support education, off-vehicle testing and system development with FSAEJ regulations.  
> [!NOTE]
> Some systems such as the accumulator are excluded from this platform.

### 1. Purpose
The FSAEJ EV Testbed (FET) is a FSAEJ regulation-compliant electrical system designed for:
- **Education**: To train new team members on EV electrical architecture and FSAEJ safety requirement.
- **Testing**: To validate vehicle control behavior and sensor integration in an off-vehicle environment.
- **Development Support**: To serve as a reference design for developing and implementing electrical systems.


## System Requirements
### 1. Regulatory Requirements
- 2025 Formula SAE Rules
- 2025 Formula SAE Japan Local Rules

### 2. Functional Requirements
- Simulate the startup/shutdown sequence as per FSAE regulations
- Allow observation and simulation of key sensor inputs and system flags
- Enable Electrical Technical Inspection sequence
- Provide clear indication of system state and fault conditions

### 3. Non-Functional Requirements
- **Safety**: Safe to operate in a classroom or lab environment; includes visible fault indicators
- **Portability**: Compact and lightweight; suitable for demonstrations and training
- **Maintainability**: Easy to debug, modify and repair
- **Expandability**: Modular interfaces for new sensor modules or ECU versions

### 4. User Interface Requirements
- Serial CLI or optional GUI interface for diagnostics and simulation
- LEDs and switches for visual/tactile status and input simulation
- Cockpit elements such as pedals and switches should be replicated to allow realistic vehicle-like operation

### 5. Documentetion / Training Requirements
- Clear schematics and system diagrams
- Step-by-step user manual and testing procedures
- Training materials for new members


## Architecture
### 1. Overall
![overall-bd](/overall/overall-block-diagram_v1.0_20250630.png)

### 2. Tractive System
![ts-bd](/ts/ts-block-diagram_v1.0_20250630.png)

### 3. Shutdown System
![sdn-sch](/sdn/sdn-sch_v1.0_20250630.png)

### 4. GLV Power Supply System
![glv-pwr-bd](/glv_pwr/glv-pwr-sch_v1.0_20250630.png)

### 5. GLV System


## Interfaces


## Testing and Validation


## Appendices
### 1. Glossary
### 2. References
### 3. Revision History
| Version | Date | Author    | Notes            |
| ------- | ---- | --------- | ---------------- |
| 1.0     |      | ST04-tkmr | Initial Revision |
