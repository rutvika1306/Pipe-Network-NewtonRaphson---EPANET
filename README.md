# Pipe-Network-NewtonRaphson---EPANET
Hydraulic analysis of a four-loop pipe network using Newton-Raphson method and EPANET
# Pipe Network Analysis using Newton-Raphson Method & EPANET

This project involves solving a four-loop pipe network problem with given inflows and outflows. The goal is to determine the steady-state flow in each pipe using the **Newton-Raphson method** for nonlinear equations and to validate results with **EPANET** simulations.

## Problem Statement
- **Network:** 4 loops, steady inflow of 5.0 units, and outflows of 2.0 and 3.0 units.
- **Flow Resistance:** `R = (Base value) + p` for each pipe, where:  
  `p = 10x + y` (x and y are the last two digits of the roll number).
- **Base resistance values:**
  - R₁ = 120 + p units  
  - R₂ = 300 + p units  
  - R₃–R₆ = 400 + p units  
  - R₇ = 200 + p units  
  - R₈ = 150 + p units  

## Objectives
1. Write a computer program to:
   - Formulate the system of nonlinear equations for loop flows.
   - Solve using the **Newton-Raphson method**.
   - Output the flow in each pipe.
2. Model and solve the same network in **EPANET** and compare results.

## Methods Used
- **Newton-Raphson Iterative Solver** for nonlinear hydraulic equations.
- Loop head loss equations derived from **Darcy-Weisbach / Hazen-Williams** form.
- **EPANET** for network simulation and verification.

## Project Workflow
1. Define pipe resistances based on roll number.
2. Set up loop equations from energy conservation.
3. Implement Newton-Raphson method in Python
4. Simulate the same network in EPANET.
5. Compare computed and simulated flows.


