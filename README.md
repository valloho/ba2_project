# Interpretable machine learning prediction of multiple sclerosis conversion from clinically isolated syndrome

This repository contains a bachelor thesis project on predicting conversion from clinically isolated syndrome (CIS) to multiple sclerosis (MS) using Python and Jupyter Notebook.

**Author:** Veronika Schramadei Haber  
**Institution:** Hochschule Campus Wien

## Project structure

```text
ba2_project/
├── data/
│   ├── raw/
│   └── processed/
├── results/
│   ├── figures/
│   └── tables/
├──cis_ms_conversion.ipynb 
├──requirements.txt
├──.gitignore
└── README.md
```

## Setup

Follow these steps to set up and run the project locally.

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

### 2. Create virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Create project folders

Open `cis_ms_conversion.ipynb` and run the first code cell. This cell creates the required folders:

```text
data/raw/
data/processed/
results/figures/
results/tables/
```
### 5. Add the dataset

Download the dataset from Mendeley Data https://data.mendeley.com/datasets/8wk5hjx7x2/1 and place the Excel file in:

```text
data/raw/
```

### 6. Run the notebook

Run the remaining notebook cells from top to bottom.

## Dataset source
Pineda, Benjamin; Flores Rivera, Jose De Jesus (2023), “Conversion predictors of Clinically Isolated Syndrome to Multiple Sclerosis in Mexican patients: a prospective study.”, Mendeley Data, V1, doi: 10.17632/8wk5hjx7x2.1

## AI usage

AI tools were used as support during this project. All AI-generated suggestions were reviewed and adapted by the author. The final code and thesis content remain the author's responsibility.

