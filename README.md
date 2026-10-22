# JACE32

Well I tried to implement (or you can say studied) Point-Based architecture used in Building Management Systems, inspired by JACE controller.

## Overview

- I was fascinated by the point-based architecture when i got to know about its significance and how useful it might be in BMS.
- Instead of changing whole firmware for specific sensor or moduke, point-based structure provides flexibilty.
- So in this project I tried to replicate and impliment point-based architecture on STM32 blackpill (STM32F411CEU6).

## Objectives

- Develop a configurable point database.
- Support digital and analog inputs.
- Separate physical hardware from logical point definitions.
- Store point configurations on an SD card.
- Demonstrate sensor replacement without rewriting the main application logic.

## Development Phases

- Phase 1: Project initialization and documentation
- Phase 2: Basic STM32 input reading
- Phase 3: Point data structure
- Phase 4: SD card configuration storage
- Phase 5: Configurable point mapping
- Phase 6: Sensor swapping demonstration
- Phase 7: Testing and documentation

## Scope

This project is an educational prototype inspired by BMS controller architecture. It is not intended to reproduce the complete functionality of a commercial Niagara JACE controller.