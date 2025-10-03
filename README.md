# Sunrudh-Microgreens-Yield-Dataset
LLM-generated dataset on microgreens yields with cleanliness checks.
Microgreens Yield Dataset (LLM-Generated)

This repository contains a **synthetic dataset on microgreens yields** generated using a Large Language Model (LLM).  
Unlike typical messy real-world datasets, this one is surprisingly **clean, consistent, and realistic** — because the LLM respected agricultural constraints like **temperature, humidity, soil needs, and growth cycles**.

The repo also includes a Jupyter Notebook demonstrating just how clean the dataset is (no missing values, no duplicates, no outliers).

Contents
- `Sunrudh Agri Yield.xlsx` — The LLM-generated dataset
- ` MicrogreensYieldPart01.ipynb` — Notebook showing validation, range checks, and quick EDA

Dataset Features
The dataset includes structured information across **8 categories of microgreens**:
- Growth duration (days to harvest)
- Temperature and humidity requirements
- Water and soil needs
- Yield estimates per tray/gram
- Category (leafy greens, legumes, herbs, root-based, etc.)

Notebook Highlights
The included notebook demonstrates:
- Dataset overview (`.info()`, `.describe()`)
- Checks for missing values and duplicates
- Range validation for growth days, yields, and climate variables
- Distribution plots for numeric features
- Correlation matrix for quick insights

Result: ✅ The dataset is **near perfect** — clean, structured, and analysis-ready.


Why Share This?
Most analysts spend 70–80% of their time cleaning data.  
This dataset shows the opposite extreme: what happens when an **LLM generates a domain-specific dataset with constraints built-in**.  

It’s open-source so anyone can:
- Explore synthetic agricultural data
- Use it for predictive modeling, EDA, or dashboards
- Compare with messy datasets (coming soon in Part 2!)

Coming Next
Stay tuned for **Part 2: Messy Dataset** — where we’ll look at a noisy, inconsistent dataset and walk through the cleaning process.
