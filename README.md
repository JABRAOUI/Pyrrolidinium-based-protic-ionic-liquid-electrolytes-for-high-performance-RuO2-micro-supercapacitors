# README for Pyrolidinium-based Protic Ionic Liquid Electrolytes Repository

## Project Description
This repository contains simulation data and parameters for pyrolidinium-based protic ionic liquid electrolytes studied for high-performance RuO₂ micro-supercapacitors. The materials include:

1. 1-propyl pyrrolidinium trifluoroacetate (Pyr3H-TFA)
2. 1-methyl pyrrolidinium tetrafluoroborate (Pyr1H-BF4)
3. 1-methyl pyrrolidinium trifluoroacetate (Pyr1H-TFA)

## Repository Contents

### Initial Structures
- `BF4_Pyr1h.xyz`: Initial structure file for Pyr1H-BF4 system
- `TFA_Pyr1h.xyz`: Initial structure file for Pyr1H-TFA system
- `TFA_Pyr3h.xyz`: Initial structure file for Pyr3H-TFA system

### Simulation Videos
- `BF4_interactions_event_WW.mp4`: Video of proton exchange events in Pyr1H-BF4 system
- `BF4_interactions_video.mp4`: Simulation trajectory of Pyr1H-BF4 system
- `TFA_Pyr3H_interactions_video.mp4`: Simulation trajectory of Pyr3H-TFA system

### Force Field Parameters
- `ReaxFF_parameters`: Directory containing ReaxFF force field parameters used in the simulations

## System Details

The three electrolyte systems were simulated with the following properties:

1. **Pyr3H-TFA**:
   - Composition: 78 ion pairs + 1 H₂O molecule
   - Density: 1.22 g/cm³
   - Box dimensions: Lx = Ly = Lz = 28.90 Å

2. **Pyr1H-TFA**:
   - Composition: 78 ion pairs + 1 H₂O molecule
   - Density: 1.26 g/cm³
   - Box dimensions: Lx = Ly = Lz = 27.41 Å

3. **Pyr1H-BF4**:
   - Composition: 90 ion pairs + 7 H₂O molecules
   - Density: 1.27 g/cm³
   - Box dimensions: Lx = Ly = Lz = 27.41 Å

## Usage

To use the files in this repository:
1. The `.xyz` files can be used as starting structures for molecular dynamics simulations
2. The ReaxFF parameters can be used with compatible molecular dynamics packages
3. The video files visualize key proton exchange events and system dynamics

## Citation

If you use this data in your research, please cite the original work:

```
[Citation information will be added here]
```

## Contact

For questions about this repository, please contact me in hicham.jabraoui@gmail.com
