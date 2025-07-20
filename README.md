# Fraud Detection Project

## Overview
This project implements a machine learning model to detect fraudulent transactions. It includes data analysis, model training, and evaluation using Python and Jupyter notebooks.

## Project Structure
- `analysis_model.ipynb` — Jupyter notebook containing data exploration, preprocessing, model building, and evaluation  
- `AIML Dataset.csv` — Dataset for training the model (**not included in the repo due to size limits**)  
- `README.md` — Project documentation

## Prerequisites
- Python 3.13 or later  
- Virtual environment (recommended)  
- Required Python libraries (e.g., pandas, scikit-learn, numpy, matplotlib, etc.)

## Installation

```bash
git clone https://github.com/dyumna11/fraud-detection-rf.git
cd fraud-detection-rf
python -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
pip install -r requirements.txt
Usage
Place your dataset file (AIML Dataset.csv) in the project root or adjust the path inside analysis_model.ipynb.

Open the notebook:

bash
Copy
Edit
jupyter notebook analysis_model.ipynb
Follow the notebook cells to preprocess data, train the model, and evaluate results.

You can modify the notebook or add scripts as needed for your use case.

Dataset
Due to GitHub size restrictions, the dataset is not included in this repository.
Please download the dataset separately and place it in the project folder to run the notebook successfully.

Contributing
Contributions are welcome! Feel free to:

Open issues to report bugs or suggest features

Fork the repository and submit pull requests
