# Denoising Score Matching and Annealed Langevin Dynamics

This repository contains the implementation and empirical evaluation of **Noise-Conditional Score Networks (NCSNs)** trained via **Denoising Score Matching (DSM)** on a 2D Swiss Roll manifold. The project systematically explores how the number of training noise scales ($L$) and inference sampling budget ($T$) impact generative sample quality, quantified using the Nearest Neighbor Distance (NND) metric.

---

## Getting Started

The core experimentation is contained entirely within a single, sequentially structured Jupyter Notebook. Follow the steps below to set up your environment and run the pipeline.

### 1. Prerequisites & Environment Setup

Ensure you have a Unix-based environment (macOS/Linux) with Python installed. Clone the repository and navigate into the project directory:

```bash
git clone https://github.com/sj-rai/annealed-langevin-dsm.git
cd annealed-langevin-dsm
```
# Install required dependencies
pip install torch numpy scipy matplotlib jupyter ipykernel

open the experiment.ipynb notebook file

To run the project, open the Jupyter notebook and execute the cells sequentially from start to finish.