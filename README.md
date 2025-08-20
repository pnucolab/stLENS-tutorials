# stLENS Tutorials

Welcome to the stLENS tutorials repository! This collection provides comprehensive guides and reproducible examples for using stLENS with spatial transcriptomics data.

## Tutorial Overview

### Getting Started
- **[Basic Tutorial](tutorial.ipynb)** - Introduction to stLENS fundamentals
  - Installation and setup
  - Basic usage with VisiumHD and STOmics data
  - Step-by-step workflow examples

### Paper Reproduction
These tutorials reproduce the key analyses and figures from the stLENS paper:

- **[Spatial Analysis Tutorial](spatial_notebook.ipynb)** - Reproduce spatial transcriptomics results
  - VisiumHD and STOmics data analysis
  - Spatial principal component optimization
  - Performance benchmarking
  - Figure generation for paper results

- **[Time Series Analysis](time_notebook.ipynb)** - Reproduce temporal analysis benchmarks
  - Performance evaluation with different dataset sizes (10k, 30k, 50k, 100k, 500k, 1m cells)
  - Runtime comparison and scalability analysis

## Prerequisites

Before running the tutorials, ensure you have:

- Python 3.9, 3.10, or 3.11
- CuPy for GPU acceleration (`conda install cupy`)
- stLENS installed (`pip install stLENS`)
- Jupyter Notebook or JupyterLab

## Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pnucolab/stLENS-tutorials.git
   cd stLENS-tutorials
   ```

2. **Install dependencies**:
   ```bash
   conda install cupy
   pip install stLENS 
   ```

3. **Start with the basic tutorial**:
   ```bash
   jupyter notebook tutorial.ipynb
   ```

## Related Documentation

- **Main Documentation**: https://stlens.readthedocs.io/
- **API Reference**: https://stlens.readthedocs.io/en/latest/api/index.html
