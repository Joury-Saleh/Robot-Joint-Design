# Joint Design Analysis

## Overview
This repository contains the analysis of three different joint designs created in Onshape and evaluated using Finite Element Analysis (FEA) simulation. The goal is to determine the optimal design based on structural performance under load.

## Design Specifications

### Common Parameters
- **Material**: Aluminum
- **Applied Force**: 9.8 N (equivalent to 1 kg mass under gravity)
- **Analysis Type**: Von Mises Stress Analysis
- **Design Software**: Onshape
- **Simulation Software**: FEA Module

## Design Variants

### Design 1: Standard Joint Configuration
![Design 1](joint-1/joint-1)
![Design 1](joint-1/joint-1-FEA)

**Key Features:**
- Two separate joint components
- Circular holes for connection points
- Maximum Von Mises Stress: **87,630 Pa** (8.763e+4 Pa)

**Stress Distribution:**
- High stress concentration around the circular holes (yellow/orange regions)
- Moderate stress in the connecting areas
- Low stress in the base regions (blue areas)

### Design 2: Reinforced Joint with Central Connection
![Design 2](Image_2_reference)

**Key Features:**
- Integrated design with central connecting element
- Reinforced joint structure
- Maximum Von Mises Stress: **71,040 Pa** (7.104e+4 Pa)

**Stress Distribution:**
- More distributed stress pattern
- Reduced peak stress concentrations
- Better load distribution through the central connection

### Design 3: Compact U-Shaped Joint
![Design 3](Image_3_reference)

**Key Features:**
- U-shaped configuration
- Compact design with integrated structure
- Maximum Von Mises Stress: **50,430 Pa** (5.043e+4 Pa)

**Stress Distribution:**
- Lowest overall stress levels
- Well-distributed stress pattern
- Minimal stress concentrations

## Comparative Analysis

| Design | Max Stress (Pa) | Stress Reduction vs Design 1 | Advantages | Disadvantages |
|--------|----------------|-------------------------------|------------|---------------|
| Design 1 | 87,630 | Baseline (0%) | Simple manufacturing, Easy assembly | Highest stress concentrations, Potential failure points |
| Design 2 | 71,040 | 18.9% reduction | Better load distribution, Reinforced structure | More complex geometry, Additional material |
| Design 3 | 50,430 | 42.5% reduction | Lowest stress levels, Compact design, Best structural integrity | Most complex manufacturing, Limited accessibility |

## Results & Recommendations

### **Recommended Design: Design 3 (U-Shaped Joint)**

**Justification:**
1. **Superior Stress Performance**: 42.5% lower maximum stress compared to Design 1
2. **Better Safety Factor**: Lower stress levels provide higher safety margins
3. **Structural Efficiency**: Compact design with optimal load distribution
4. **Failure Resistance**: Reduced stress concentrations minimize crack initiation points

### Performance Ranking:
1. **Design 3** - Best overall performance (Lowest stress: 50,430 Pa)
2. **Design 2** - Good performance with moderate improvement (71,040 Pa)
3. **Design 1** - Baseline design requiring optimization (87,630 Pa)

## Material Properties (Aluminum)
- **Yield Strength**: ~276 MPa (276,000,000 Pa)
- **Ultimate Tensile Strength**: ~310 MPa
- **Young's Modulus**: ~69 GPa
- **Density**: 2,700 kg/m³

## Safety Analysis
All designs show stress levels well below the yield strength of aluminum:
- Design 1: Safety Factor = 3,150
- Design 2: Safety Factor = 3,885
- Design 3: Safety Factor = 5,475

## Simulation Setup
- **Mesh Type**: Automatic mesh generation
- **Load Application**: Point load of 9.8 N
- **Boundary Conditions**: Fixed supports as shown in models & Force & Hinge constraint
- **Analysis Type**: Linear static analysis

## Conclusions
The FEA analysis clearly demonstrates that Design 3 offers the best mechanical performance with significantly reduced stress concentrations. While all designs are structurally safe under the applied load, Design 3 provides the highest safety margin and most robust solution for the intended application.


---
*Analysis completed using Onshape FEA simulation tools*
