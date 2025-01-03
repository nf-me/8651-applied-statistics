# README.md

## Repository Overview
This repository contains three core notebooks, each focused on different aspects of applied statistics:

1. **tasks.ipynb**  
   - Demonstrates four statistical tasks:  
     - Permutations & Combinations (Lady Tasting Tea)  
     - Checking Normal Distribution with `numpy`  
     - t-Test Calculation (Before vs. After)  
     - Estimating Type II Error with One-Way ANOVA  

2. **project.ipynb**  
   - Focuses on analyzing the **PlantGrowth** dataset, including:  
     - T-tests comparing treatment groups  
     - ANOVA across three groups (`ctrl`, `trt1`, `trt2`)  
     - Justification for ANOVA versus multiple t-tests  

3. **environment.ipynb**  
   - Details the environment setup, required libraries, and version checks.

## Repository Structure
- `tasks.ipynb`: Notebook demonstrating four distinct statistical tasks.
- `project.ipynb`: Notebook focused on the PlantGrowth dataset.
- `environment.ipynb`: Documents the Python environment setup and library versions.
- `data/` (optional): Directory to store CSV files such as `PlantGrowth.csv`.
- `requirements.txt`: Lists necessary Python packages for reproducibility.
- `README.md`: This file, describing how to use the repository.

## Key Features
- **Comprehensive Statistical Methods**: Includes t-tests, ANOVA, and type II error estimation.
- **Detailed Environment Documentation**: Provides a reproducible Python environment setup.
- **Flexible Analysis**: Enables exploration of the PlantGrowth dataset with robust statistical methods.

## Expected Results
- Visualization of distributions using `matplotlib` and `seaborn`.
- Insights from statistical tests with detailed explanations.

## Setup and Usage Instructions

### Installation
1. **Clone or Download the Repository**:
   ```bash
   git clone https://github.com/nf-me/8651-applied-statistics.git
   cd 8651-applied-statistics
   ```
2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```
   **Or**, if using Conda:
   ```bash
   conda create -n stats-env python=3.9
   conda activate stats-env
   pip install -r requirements.txt
   ```

3. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```

### Running the Notebooks
1. **Open Jupyter Notebook/Lab**:
   - Run `jupyter notebook` or `jupyter lab`.

2. **Open the Notebooks**:
   - Click on `tasks.ipynb` to explore the four statistical tasks.
   - Click on `project.ipynb` to view and run the dedicated project analysis.
   - Click on `environment.ipynb` to check the Python environment.

## License
This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The formatting, wording, and some variable names were refined with the assistance of GitHub Copilot. This tool was utilised exclusively for crafting explanations, enhancing readability, and improving clarity; all code development, statistical analyses, and interpretations are entirely my own.