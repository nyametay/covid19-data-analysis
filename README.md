# 🦠 COVID-19 Data Analysis (April 2020)

This repository contains a Jupyter Notebook that performs basic data analysis on a small COVID-19 dataset. The data includes global statistics for confirmed, death, and recovered cases as of **29-April-2020**.

---

## 📓 Notebook Overview

**`Covid 19 Analysis Notebook.ipynb`** includes:
- Loading and inspecting a COVID-19 dataset from Kaggle
- Handling missing values
- Grouping by region for aggregate statistics
- Filtering, sorting, and analyzing case trends
- Country-specific analysis (e.g., India)

---

## 🧾 Dataset Description

- Source: Kaggle COVID-19 dataset  
- Timeframe: Up to 29-April-2020  
- Features: `Region`, `Confirmed`, `Deaths`, `Recovered`, and more

> **Note:** The file `Covid_19_data.csv` should be placed inside the `../Datasets/` directory or the path updated in the notebook.

---

## 📊 Analysis Performed

1. **Aggregate Statistics by Region**  
   - Total confirmed, death, and recovered cases by region

2. **Filtering**  
   - Removed all rows where confirmed cases were fewer than 10

3. **Region-Based Queries**  
   - Region with the maximum number of confirmed cases  
   - Region with the minimum number of deaths

4. **Country-Specific Analysis**  
   - COVID-19 stats for **India** as of 29 April 2020

5. **Sorting**  
   - Sorted by number of confirmed cases (ascending)  
   - Sorted by number of recovered cases (descending)

---

## 🛠️ Requirements

You can install the required Python packages with:

```bash
pip install pandas
```

## Running the Notebook
1. Clone the repository:

```bash
git clone https://github.com/your-username/covid19-data-analysis.git
cd covid19-data-analysis
```
2. Launch the notebook:

```bash
jupyter notebook
```
3. Open Covid 19 Analysis Notebook.ipynb and run the cells to explore the dataset.

