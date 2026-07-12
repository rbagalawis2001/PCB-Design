# Overview

## Purpose
  This PCB aimed to introduce or reinforce microcontroller (MCU) skills in CSULB electrical engineering undergrads while reducing time and material consumption during workshops. 

## Design
  This is a four layer board that reroutes the Nucleo's peripherals and shows the order of MCU port bits on the silkscreen. For most underclassmen, the leap from Arduino to STM32 may be overwhelming since the number of breakout pins go from 20ish to 60ish. The morpho headers are originally not organized by port bit, which will also cause delay by trying to find certain pins. They layout of this PCB breaks out ports A, B, and C while ordering the respective bits from 0-15.
  Additionally, the board's connectors convert the male morpho pin headers into female pin sockets to make wiring more convenient- due to an abundance of male wires over female wires. An extra pair of female connectors act as a *breadboard* jumper area for closer connections to peripheral devices such as a 16 pin LCD screen. This aims to help isolate any output circuitry (LED Displays) from input circuitry (sensors)
