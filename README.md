# traffic-light-controller
Overview

This project implements a Finite State Machine (FSM) for a traffic light control system using Verilog RTL. The design manages traffic flow between a highway and a small road, with a sensor input detecting vehicles on the small road to adjust light transitions.

Features

FSM-Based Traffic Light Control: Implements state transitions to manage traffic efficiently.

Configurable Timings: Green-to-Yellow and Yellow-to-Red delays are defined using macros (G2YDELAY, Y2RDELAY).

Sensor-Based Decision Making: The small road gets a green light only when a vehicle is detected.

Xilinx FPGA Compatibility: Can be synthesized and deployed on Xilinx FPGA platforms.
