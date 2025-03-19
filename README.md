# 🦠 COVID-19 India Analysis

This project presents an **exploratory analysis** of COVID-19 cases and vaccination data in India. It includes detailed insights on case trends, state-wise impacts, and vaccination demographics using both **static** and **interactive visualizations**.

## 📊 Visualizations Included

| Visualization                                  | Description                                                    |
|-----------------------------------------------|----------------------------------------------------------------|
| **Top States with Most Active Cases**         | Bar plot highlighting the top 10 states with active cases.     |
| **Top States with Most Deaths**               | Bar plot showing states with the highest death toll.           |
| **Growth Trend in Top 5 States**              | Line plot of active cases over time in heavily affected states.|
| **Male vs Female Vaccination Distribution**   | Interactive pie chart showing gender-wise vaccine uptake.      |
| *Top and Bottom 5 Vaccinated States in India*                   | Barplots showing top 5 and Bottom 5 states with highest and lowest number of vaccinated people respectively|

## 🗂️ Dataset Sources

- **COVID-19 Case Data**: `covid_19_india.csv`
- **Vaccination Data**: `covid_vaccine_statewise.csv`
- **Testing Details**: `StatewiseTestingDetails.csv`

## 🛠️ Requirements

Install the following libraries to run the analysis:

```bash
pandas
numpy
matplotlib
seaborn
plotly
```

Install via pip:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/covid19-india-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd covid19-india-analysis
   ```
3. Open the notebook:
   - Jupyter:
     ```bash
     jupyter notebook "Covid 19 Analysis.ipynb"
     ```
   - Google Colab: Upload the notebook and dataset files to Colab, then run all cells.

## 📌 Key Insights

- Identified the most affected Indian states based on active cases and deaths.
- Visualized COVID-19 growth trends over time in top states.
- Analyzed vaccination distribution by gender.
- Presented interactive visuals for better data exploration.

---
