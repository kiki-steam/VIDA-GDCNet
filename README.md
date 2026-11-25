# VIDA-GDCNet

**VIDA: A Real-World Vehicle Damage Dataset and GDCNet for Instance Segmentation**

This repository provides the project information for our work on real-world vehicle damage understanding and instance segmentation.

## Overview

We introduce **VIDA**, a real-world vehicle damage dataset, and **GDCNet**, a Generative–Discriminative Coupling Network for vehicle damage instance segmentation.

### VIDA Dataset

VIDA is collected from real-world vehicle insurance claim scenarios.

- **Images:** 9,169
- **Damage instances:** 23,972 pixel-level instance annotations
- **Categories:** 8 typical vehicle damage categories

The eight damage categories are:

1. Deformation
2. Dislocation
3. Missing
4. Glass breakage
5. Glass crack
6. Scratch
7. Scratches
8. Tearing

### GDCNet

GDCNet integrates complementary visual representations from a pretrained diffusion model and a discriminative backbone.

It consists of three key components:

- **MDPE (Multi-level Diffusion Prior Encoding):** Extracts multi-timestep and multi-level visual features from a pretrained diffusion model.
- **RCRM (Reciprocal Cross-Representation Modulation):** Enables adaptive timestep aggregation, bidirectional feature interaction, and multi-granularity feature enhancement.
- **BAGC (Boundary-Aware Gradient Consistency):** Introduces local gradient consistency constraints to improve damage boundary representation.

## Repository Contents

This initial public release contains only the project README.

Source code, dataset files, annotations, and pretrained weights are not included in this repository.

## Citation

Bibliographic information will be added when the paper's publication details are finalized.
