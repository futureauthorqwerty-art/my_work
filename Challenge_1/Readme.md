# Molecular-and-Materials-Modeling-2026-November Solutions

## Challenge Overview
The objective of this assignment is to verify the installation, environment setup, and computational readiness of three molecular and materials modeling packages (**MACE**, **MOPAC**, and **NWChem**) using an isolated water molecule ($\text{H}_2\text{O}$) as a standard test system.

## Solution Summary

### 1. MACE
* **Setup:** Executed on CPU using a Python smoke-test script.
* **Models:** Loaded `MACE-OFF23 (medium)` and `MACE-MP-0 (med+D3)`.
* **Outcome:** Successfully calculated single-point potential energies and atomic forces for water molecules.

### 2. MOPAC
* **Setup:** Created a standard MOPAC input file for $\text{H}_2\text{O}$ and executed the job via the terminal.
* **Outcome:** Completed without errors, generating standard output and archive files with molecular properties.

### 3. NWChem
* **Setup:** Verified through two independent execution workflows:
  1. **Python / ASE Interface:** Executed the calculation using the provided Python script.
  2. **Standalone Execution:** Ran NWChem directly from the terminal using a standalone input file.
* **Outcome:** Both methods completed successfully and produced consistent energy results.

### Note: 
Actually I don't understend what is solution in this particular case due to I did exactly what you have done and obtain the same results, except the MACE executed on CPU. If solution is my terminal script, then I attach it in corresponding file. 

