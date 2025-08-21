# Nodal-Analysis

## Project Overview
This project demonstrates nodal analysis, a fundamental technique in petroleum engineering used to optimize oil and gas production systems. The analysis integrates Inflow Performance Relationship (IPR) and Tubing Performance Relationship (TPR) curves to determine the optimal operating point for a well under different tubing sizes.
## Key Features
- IPR curve generation using field data from PetroWiki
- TPR analysis for three different tubing sizes (1.90 in, 2.375 in, 2.875 in)
- Visualization of IPR and TPR curves using matplotlib

## Dataset
- **IPR Data**: Source - PetroWiki
  - Flow rates (Q) range: 0-5519 bpd
  - Flowing bottomhole pressures (Pwf) range: 14.7-4000 psi

- **TPR Data**: Includes performance curves for three tubing sizes at various flow rates. Source - PetroWiki

## Requirements
- Python 3
- Jupyter Notebook
- Libraries:
  - numpy
  - matplotlib
  - pandas

## Usage
1. Run the Jupyter notebook `nodal_analysis.ipynb`
2. The code will:
   - Import and display IPR data
   - Plot the IPR curve
   - Import and display TPR data for three tubing sizes
   - Generate a composite plot showing IPR and TPR curves

## Interpretation
The intersection points between IPR and TPR curves indicate the optimal flow rate and pressure conditions for different tubing configurations. This analysis helps  select the most efficient tubing size for maximum production.

## Application
This type of analysis is crucial for:
- Well productivity optimization
- Equipment selection (tubing size)
- Production system design
- Reservoir management decisions
