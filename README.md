# README.md

## Overview
This repository contains two core notebooks and an environment notebook:

1. **tasks.ipynb**  
   - Covers four statistical tasks:
     - Permutations & Combinations (Lady Tasting Tea)  
     - Checking Normal Distribution with `numpy`  
     - t-Test Calculation (Before vs. After)  
     - Estimating Type II Error with One-Way ANOVA  

2. **project.ipynb**  
   - Dedicated to analysing the **PlantGrowth** dataset, which includes:
     - T-tests comparing treatment groups  
     - ANOVA across three groups (`ctrl`, `trt1`, `trt2`)  
     - Justification for ANOVA vs. multiple t-tests  

3. **environment.ipynb**  
   - Documents environment setup, required libraries, and version checks.  

## Repository Structure
- `tasks.ipynb`  
  - Notebook demonstrating four distinct statistical tasks.  
- `project.ipynb`  
  - Notebook focused on the PlantGrowth dataset.  
- `environment.ipynb`  
  - Details and validates the Python environment, capturing library versions.  
- `data/` (optional)  
  - Stores CSV files such as `PlantGrowth.csv`.  
- `requirements.txt`  
  - Lists necessary Python packages for reproducibility.  
- `README.md`  
  - This file, describing how to use the repository.

## Usage
1. **Clone or Download**  
   ```bash
   git clone https://github.com/YourUsername/YourRepo.git
   cd YourRepo

2. **Jnstall Requirements:**
     ```bash
   pip install -r requirements.txt
     # or alternatively, if you use conda
     conda create -n stats-env python=3.9
conda activate stats-env
pip install -r requirements.txt
     ```
3. **Launch Jupyter:**
   ```bash
   jupyter notebook
   # or jupyter lab
   ```

## License
This project is licensed under the terms of the MIT license.
     ```

3. **Library Installation:**
   - Install the required libraries using pip:
     ```bash
     pip install pandas numpy matplotlib seaborn scipy statsmodels
     ```

### Running the Notebooks
1. **Clone the Repository:**
   - Clone this repository to your local machine or download the notebooks.

2. **Launch Jupyter Notebook/Lab:**
   - Open your terminal or command prompt.
   - Navigate to the directory containing the notebooks.
   - Run `jupyter notebook` or `jupyter lab`.

3. **Open the Notebooks:**
   - Your web browser will open with a Jupyter interface.
   - Click on `tasks.ipynb` to explore the four statistical tasks.
   - Click on `project.ipynb` to view and run the dedicated project analysis.
   - Click on `environment.ipynb` to check the Python environment.
## License
This project is open source and available under the [MIT License](LICENSE).
