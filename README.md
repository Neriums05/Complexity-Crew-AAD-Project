# Complexity-Crew-AAD-Project

Files : 
-> All folders contain .ipynb files for their respective algorithm
-> README.md : This file
-> AAD_Final_Report : The final report pdf
-> Comparative-testing : The .ipynb file with the code used to compare the algorithms against each other on various metrics.

This repo contains 5 different algorithm implementations for delaunay triangulation and dataset/benchmark code for the same.

Prerequisites
- Python 3.8+ (3.10 recommended)
- pip
- Jupyter or VS Code with Jupyter support

Quick install (recommended: use virtual environment)
```bash
# Create & activate venv (Linux / macOS)
python3 -m venv .venv
source .venv/bin/activate

# Windows (PowerShell)
python -m venv .venv
.venv\Scripts\Activate.ps1

# Install core dependencies
pip install --upgrade pip
pip install numpy matplotlib scipy jupyter notebook

Then, run each code block in the .ipnyb files in order to run the implementation as well as comparison against various datasets for each algorithm.