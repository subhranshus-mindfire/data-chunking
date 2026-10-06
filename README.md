# Machine Learning Assignment

This repository contains the codebase, notebooks, and models for the Machine Learning assignment.

---

## 📁 Project Structure

```text
├── data/
│   ├── raw/             # Raw, unprocessed data
│   └── processed/       # Cleaned, preprocessed datasets
├── models/              # Trained models, checkpoints, and serialization files
├── notebooks/           # Jupyter notebooks for exploratory data analysis (EDA) & experiments
├── src/                 # Reusable source code and modules
│   └── __init__.py
├── .gitignore           # Git ignore rules for ML files, datasets, and models
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 🚀 Getting Started

### 1. Environment Setup

Create and activate a virtual environment:

```bash
# Using venv
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 3. Running Notebooks

```bash
# Register kernel with Jupyter
python -m ipykernel install --user --name=ml-env --display-name="Python (ML Env)"

# Launch Jupyter Lab / Notebook
jupyter notebook
```

---

## 🔗 Connecting to Remote GitHub Repository

To link this repository to a remote repository on GitHub:

```bash
# Add your remote repository origin
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git

# Push the initial commit to main
git branch -M main
git push -u origin main
```
