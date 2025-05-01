# MOBO_SOIL_CALIBRATION
FLIPROSE is a Finite Element Method (FEM) program that utilizes the Strain Space Multiple Mechanism Soil Constitutive Model to analyze the liquefaction behavior of sandy soil. It incorporates Multi-Objective Bayesian Optimization (using AX and BoTorch) to identify an optimal set of liquefaction parameters calibrated against experiment cyclic loading test data.

# Title of the Journal Paper
Multi-Objective Bayesian Optimization incorporating an FEM Framework for Calibrating Sandy Soil using Cyclic Loading Tests<br>SOILDYN-D-25-00762<br>Date of Submission (Rough Draft) : 11th April 2025 (On peer review)

# Program Version Inforamtion
FLIPROSE : 7.2.3 (Commercial Software)<br>
Python : 3.11.5<br>
Jupyter notebook : 7.0.6 (Didn't mention on the paper)
Botorch : 0.9.2<br>
AX platform : 0.3.4<br>

# Key features
1. A methodology integrating the FEM framework with the Multi-Objective Bayesian Optimization algorithm to automatically calibrate soil constitutive model parameters, aiming to simultaneously satisfy multiple liquefaction criteria.
2. A method of quantifying the discrepancy between simulation results and experimental measurements across various Cyclic Stress Ratio (CSR) values using specific metrics, and then averaging these discrepancies over all CSRs to formulate a single objective function value. The "single objective function value" does not mean that the MOBO is being processed as a single optimization manner.

# Drawback of this code
1. d
2. 

# Please Check the code file
This code was intentionally developed using hardcoding.<br> 
The next version will be automatically generated, will include new functions aiming to obtain a good quality of simulation data when blind prediction stage.<br>
It is expected to be released around Q1 2026 (hopefully).

