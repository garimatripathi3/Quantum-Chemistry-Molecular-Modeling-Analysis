# 🧪 Computational Chemistry Analysis: Molecular Modeling with Gaussian

This repository contains the results and analysis of various computational chemistry studies performed using Gaussian software with Hartree-Fock (HF) method and STO-3G basis set.

## 📋 Project Overview

This project explores fundamental concepts in computational chemistry through several key analyses:

1. **🔄 Reaction Energy Calculations**: Computed energetics for five organic reactions
2. **🔄 Conformational Analysis**: Dihedral angle rotation energy profile for butane
3. **💍 Ring Conformer Comparison**: Energy difference between cyclohexane conformers
4. **📊 Vibrational Spectroscopy**: Calculated IR spectrum of acetaldehyde with experimental comparison
5. **🔗 Hydrogen Bonding Analysis**: Comparison of H-bonding strength between H₂O and H₂S

## ⚙️ Technical Details

### Methods
- **🧮 Computational Method**: Restricted Hartree-Fock (RHF)
- **🔬 Basis Set**: STO-3G
- **💻 Software**: Gaussian
- **📏 Energy Units**: Hartree (au) converted to kcal/mol using 1 Hartree = 627.5095 kcal/mol

### Computational Resources
- **🖥️ High-Performance Computing**: All calculations were performed on ABACUS, the high-end computing server at IIIT Hyderabad
- **⚡ Server Specifications**:
  - Multi-node cluster with high-performance CPU cores
  - Advanced memory configuration for quantum chemistry calculations
  - Optimized for parallel computation of molecular modeling tasks

## 📈 Key Results

### 1. 🔥 Reaction Energy Calculations

| Reaction | ΔE (kcal/mol) | Type |
|----------|---------------|------|
| Hydrogenation of Ethene | -71.98 | Exothermic |
| Combustion of Methane | -106.84 | Exothermic |
| Acid-Base Neutralization | -90.92 | Exothermic |
| Formation of Water | -91.13 | Exothermic |
| Decomposition of H₂O₂ | +29.11 | Endothermic |

### 2. 🔄 Butane Conformational Analysis
- **Anti conformation (180°)**: Global energy minimum
- **Gauche conformations (±60°)**: Local energy minima
- **Eclipsed conformations (0°, 120°, 240°)**: Energy maxima
- **Rotational barrier**: ~6 kcal/mol

### 3. 💍 Cyclohexane Conformer Comparison
- **Chair conformation**: -231.4826716 Hartree
- **Boat conformation**: -231.4729725 Hartree
- **Energy difference**: 6.086 kcal/mol (chair more stable)

### 4. 📊 Acetaldehyde Vibrational Analysis
Key vibrational modes comparison:

| Vibrational Mode | Calculated (cm⁻¹) | Experimental (cm⁻¹) | Difference (%) |
|------------------|-------------------|----------------------|----------------|
| C=O stretching | 1700 | 1730 | 1.7 |
| CH₃ asymm. str. | 3050 | 3005 | 1.5 |
| CH₃ symm. str. | 2950 | 2917 | 1.1 |
| CH aldehyde str. | 2750 | 2720 | 1.1 |
| CH₃ deformation | 1400 | 1427 | 1.9 |
| C-C stretching | 1000 | 1113 | 10.2 |
| CHO bending | 600 | 509 | 17.9 |

### 5. 🔗 Hydrogen Bonding Comparison
- **Water (H₂O)**:
  - Monomer energy: -74.96590117 a.u.
  - Dimer energy: -149.94124427 a.u.
  - Binding energy: -5.925 kcal/mol
  - Dipole moment (monomer): 1.7094 Debye
  - Dipole moment (dimer): 2.8260 Debye

- **Hydrogen Sulfide (H₂S)**:
  - Monomer energy: -394.306248 a.u.
  - Dimer energy: -788.62430206 a.u.
  - Binding energy: -7.406 kcal/mol
  - Dipole moment (monomer): 0.974 Debye
  - Dipole moment (dimer): 1.3188 Debye

Analysis shows that despite the calculated binding energy values, water forms stronger hydrogen bonds due to oxygen's higher electronegativity, smaller atomic radius, and stronger dipole-dipole interactions compared to sulfur in H₂S.

## 📁 Repository Structure
```
├── 📂 data/
│   ├── reaction_energies.csv
│   ├── butane_conformational.csv
│   └── vibrational_data.csv
├── 📊 figures/
│   ├── butane_energy_profile.png
│   ├── acetaldehyde_ir_spectrum.png
│   └── h-bond_comparison.png
├── 📜 scripts/
│   ├── energy_calculations.py
│   ├── conformational_analysis.py
│   └── spectrum_comparison.py
├── ⚙️ gaussian_input/
│   ├── ethene_hydrogenation.gjf
│   ├── methane_combustion.gjf
│   └── water_dimer.gjf
└── 📖 README.md
```

## 🔮 Future Work
- Improve accuracy with higher-level theory (DFT/B3LYP)
- Expand basis set to 6-31G(d) or better
- Include anharmonic corrections for vibrational analysis
- Incorporate solvent effects for solution-phase simulations

## 💻 Computational Environment
All calculations in this project were executed on the ABACUS high-performance computing cluster at IIIT Hyderabad. This advanced computing infrastructure provided:

- Parallel processing capabilities for complex quantum mechanical calculations
- Sufficient memory allocation for handling large molecular systems
- Optimized numerical libraries for quantum chemistry applications
- Dedicated nodes for computationally intensive tasks like vibrational analysis

Access to ABACUS was instrumental in achieving high-quality results within reasonable timeframes, particularly for the frequency calculations and conformational analyses that require significant computational resources.

## 📚 References
- Gaussian Software: https://gaussian.com/
- Computational Chemistry Textbook (recommended): "Molecular Modeling: Principles and Applications" by Andrew Leach



## 👤 Author
Created by Garima Tripathi


Email : garimatripathi0778@gmail.com

