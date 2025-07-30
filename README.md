# Dynamic Pricing Prediction

A Jupyter Notebook–based project exploring machine learning techniques to forecast optimal pricing using historical dynamic pricing data.

## Project Overview

This repository contains:

- `main.ipynb` — the primary analysis and modeling notebook  
- `dynamic_pricing.csv` — dataset with historical pricing and relevant features

This project investigates predictive models to forecast dynamic prices, support pricing strategy simulations, and evaluate revenue impact.

---

## Data

- **Source**: `dynamic_pricing.csv`  
- Likely includes: historical price entries, demand indicators, time or product features  
- Utilized within `main.ipynb` for feature engineering and modeling

---

## main.ipynb Workflow

The notebook is structured to:

1. **Explore & visualize** data trends (e.g. price over time, feature distributions)  
2. **Engineer features** relevant for modeling (e.g. lagged pricing, demand proxies)  
3. **Train models** (such as regression, tree-based methods, or others)  
4. **Evaluate performance** using metrics like MAE or RMSE  
5. **Optionally simulate pricing scenarios** to assess potential revenue or consumer response

---

## Technical Stack

- **Language**: Python (via Jupyter notebook)  
- **Libraries**: pandas, NumPy, scikit-learn, Matplotlib/Seaborn, possibly XGBoost or LightGBM  
- **Modeling Approach**: regression and tree-based methods, with emphasis on dynamic pricing contexts

---

## Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Imadjaha/dynamic-pricing-prediction.git
   cd dynamic-pricing-prediction
   ```
   
2. **Open the notebook**
3. **Install dependencies as needed**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
4. **Run code cells sequentially**

   Load and preprocess the dataset
   Engineer features and split data
   Train and validate models
   Analyze results and simulate pricing decisions
