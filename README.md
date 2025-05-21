# COVID-19 Global Data Tracker

## Project Overview

This project analyzes and visualizes global COVID-19 trends with a focus on Kenya, United States, and India. It explores case counts, deaths, and vaccination rollouts over time using real-world data from [Our World in Data](https://ourworldindata.org/covid-vaccinations). 

The analysis includes:
- Time series of total and new COVID-19 cases and deaths
- Vaccination coverage and progress for selected countries
- Global vaccination coverage visualization via a choropleth map
- Interactive plots and pie charts illustrating vaccine uptake

This notebook is designed for both learning and insightful reporting, combining data cleaning, exploratory data analysis, and modern visualization tools.

---

## 📂 Files Included
- `covid_tracker.ipynb` — Jupyter Notebook containing the full analysis and visualizations
- `README.md` — Project overview and instructions
- `owid-covid-data.zip` — Zipped data file containing COVID deaths and vaccinations, (kindly unzip and store in same directory as covid_tracker.ipynb)
- `vaccinations.csv` — Data file containing and vaccinations

---

## 🛠️ Technologies & Libraries Used

Make sure to install the following Python libraries:

- `pandas` — for data loading and manipulation
- `matplotlib` — for static plotting
- `seaborn` — for enhanced visualizations
- `plotly` — for interactive maps and charts

You can install these with:

```bash
pip install pandas matplotlib seaborn plotly
```

## 📥 Dataset
Download the vaccination dataset from Our World in Data:

COVID-19 Vaccinations dataset (CSV)

Place the file vaccinations.csv in the same directory as the notebook.
Place the file owid-covid-data.zip in the same directory as the notebook, once unzipped.

## 🚀 How to Run
Ensure you have Python 3.x installed with the libraries listed above.

Download the vaccinations.csv dataset and place it alongside covid_tracker.ipynb.

Open the notebook using Jupyter Notebook or JupyterLab:

```bash
jupyter notebook covid_tracker.ipynb
```
Run each cell sequentially to:

Load and clean the data

Generate visualizations (line charts, pie charts, choropleth map)

Explore key trends and insights

Customize and extend the notebook as desired!

## 🔍 Project Insights
The analysis reveals the dynamics of COVID-19 cases and vaccination trends in Kenya, the USA, and India.

Pie charts provide a clear picture of vaccination coverage percentages for each country.

The choropleth map offers an interactive global view of vaccination progress, highlighting disparities between countries.

The project demonstrates the power of combining data science tools and visualization libraries to tell compelling data-driven stories.


## 🤝 Contributions & Support
Feel free to fork this project, suggest improvements, or submit issues!

If you have any questions or need help running the notebook, reach out or open an issue.

Thank you for checking out this project! Stay safe and keep coding. 💻✨
