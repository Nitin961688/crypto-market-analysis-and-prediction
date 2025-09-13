# crypto-market-analysis-and-prediction
## Overview
- Merge **historical crypto trading data** with the **Fear & Greed Index**.  
- Clean, preprocess, and handle missing values.  
- Perform **EDA** with descriptive statistics and visualizations.  
- Build a **Logistic Regression** model for prediction.  
- Evaluate results using **accuracy, confusion matrix, and classification report**.


##  Repository Structure
```text
crypto-market-analysis-and-prediction/
│
├── data/
│ ├── historical_data.csv # Historical trading data
│ ├── fear_greed_index.csv # Fear & Greed Index dataset
│ └── README.md # Dataset info (optional)
│
├── notebooks/
│ └── crypto-market-analysis-and-prediction.ipynb # Main Jupyter Notebook
│
├── src/
│ ├── data_preprocessing.py # Data cleaning & merging
│ ├── eda.py # Exploratory Data Analysis
│ ├── modeling.py # Logistic Regression model
│ └── utils.py # Helper functions
│
├── reports/
│ └── figures/ # Plots and results
│
├── requirements.txt # Python dependencies
├── README.md # Project overview
└── .gitignore # Ignore unwanted files


---
# Datasets

- **Historical Market Data**  
     File: `data/historical_data.csv`  
     [Download Historical Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=drive_link)  

- **Fear & Greed Index**  
     File: `data/fear_greed_index.csv`  
     [Download Fear & Greed Index Data](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=drive_link)
If datasets are too large, provide external download links.

Load Datasets in Python
import pandas as pd

# Direct Google Drive links (converted to 'uc?id=' format)
hist_url = "https://drive.google.com/uc?id=1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs"
fear_url = "https://drive.google.com/uc?id=1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf"

# Load CSVs into pandas
historical_data = pd.read_csv(hist_url)
fear_greed = pd.read_csv(fear_url)

print("Historical Data Shape:", historical_data.shape)
print("Fear & Greed Data Shape:", fear_greed.shape)

##🚀 Installation
git clone https://github.com/your-username/crypto-market-analysis-and-prediction.git
cd crypto-market-analysis-and-prediction
pip install -r requirements.txt

##⚡ Usage

Run the Jupyter Notebook:

jupyter notebook notebooks/crypto-market-analysis-and-prediction.ipynb


Or execute individual Python scripts:
python src/data_preprocessing.py
python src/eda.py
python src/modeling.py

   
