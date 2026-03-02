# Uber vs. Lyft: Operational Efficiency Analysis

## 📌 Problem Statement
A comparative analysis of Uber and Lyft’s operational efficiency in Boston. The project utilizes real ride data to identify pricing behaviors, surge sensitivities, and demand patterns through cost metrics and K-Means clustering.

## 📂 Dataset
*   **Source:** [Kaggle - Uber and Lyft Dataset (Boston, MA)](https://www.kaggle.com)
*   **Attributes:** Price, distance, timestamp, ride type, surge multiplier, and coordinates.

## 🛠 Tech Stack
*   **Language:** [Python](https://www.python.org)
*   **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
*   **Environment:** [Jupyter Notebook](https://jupyter.org)

## 🚀 Project Workflow
1.  **Data Preprocessing:** 
    *   Cleaned missing/inconsistent values.
    *   Feature Engineering: Extracted `hour_of_day` and calculated `price_per_mile`.
2.  **Cost Analysis:** 
    *   Compared average ride prices and surge multipliers.
    *   Analyzed pricing fluctuations by time of day.
3.  **Demand Clustering:** 
    *   Implemented **K-Means Clustering** using `Hour`, `Price`, and `Distance`.
    *   Features standardized via [StandardScaler](https://scikit-learn.org).

## 📈 Key Findings
*   **Uber** generally offers a lower price-per-mile, indicating higher cost efficiency.
*   **Lyft** shows higher surge sensitivity during peak hours.
*   **Clustering** successfully separated high-demand commuter peaks from low-cost off-peak periods.

## 📁 Project Structure
```text
Internal_Project_Business/
├── main.ipynb             # Analysis & Visualizations
├── data/
│   └── uber_lyft_boston.csv
├── results/               # Saved plots and figures
├── README.md              # Project Documentation
└── requirements.txt       # Python dependencies
```

## Run the analysis:
Execute the cells in main.ipynb sequentially.
* How to Run the Project
``` text

Clone or download the project

Install required dependencies

pip install -r requirements.txt

Open main.ipynb in Jupyter Notebook

Run cells sequentially

```
