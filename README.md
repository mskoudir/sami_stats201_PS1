# Hiring Bias Analysis

## Overview
This repository investigates racial bias in hiring decisions using machine learning models. It examines whether applicant names influence callback rates and evaluates fairness-aware algorithms.

## System Requirements

### Local Setup
Ensure you have the following installed:
- Python 3.9+
- Jupyter Notebook
- Required dependencies listed below.

Run the following commands:

```bash
# Clone the repository
git clone https://github.com/Rising-Stars-by-Sunshine/hiring-bias-analysis.git
cd hiring-bias-analysis

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

### Cloud Setup (Google Colab)
- Open [Google Colab](https://colab.research.google.com).
- Clone the repository using:
```python
!git clone https://github.com/Rising-Stars-by-Sunshine/hiring-bias-analysis.git
%cd hiring-bias-analysis
```
- Run the Jupyter notebook in `code/eda_notebook.ipynb`.

## Repository Structure
- `data/` - Contains datasets and metadata.
- `code/` - Contains Jupyter Notebooks and preprocessing scripts.

## Data Description
The dataset includes:
- **Applicant Names:** First and last names used in the job application.
- **Race/Ethnicity:** Perceived race based on applicant name.
- **Job Category:** Type of job applied for.
- **Callback:** Whether the applicant received a response.

For a complete list of variables, see `data/data_dictionary.md`.

## Running the Analysis
To perform exploratory data analysis (EDA), open and execute `code/eda_notebook.ipynb` in Jupyter Notebook. This notebook:
- Loads the dataset
- Summarizes key statistics
- Visualizes hiring biases using data distributions

For preprocessing, run `code/preprocess.py`:
```bash
python code/code.py
```
This script cleans and encodes categorical data, preparing it for model training.

## Dependencies (requirements.txt)
```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
shap
jupyter
```

## License
This project is released under the MIT License. See `LICENSE` for details.

## Contributors
- Mohamed Sami Koudir

