
# 🌍 COVID-19 Global Data Tracker

This project is a global COVID-19 data analysis and visualization notebook created using real-world data. It allows users to explore how the pandemic evolved across different countries in terms of total cases, deaths, recoveries, and vaccinations. The notebook includes a choropleth map to visualize the global distribution of cases.

---

## Project Objectives

- Import and clean global COVID-19 data.
- Analyze trends over time (cases, deaths, vaccinations).
- Compare metrics across countries and regions.
- Visualize trends using interactive and static charts.
- Communicate insights through narrative markdown and visuals.

---

## Project Structure
```
covid19-data-tracker/
├── owid-covid-data.csv
├── COVID19_Global_Tracker.ipnyb
└── README.md
```

---
## Technologies Used
- **Python 3**
- **Pandas** – for data loading and manipulation
- **Matplotlib & Seaborn** – for static data visualizations
- **Plotly Express** – for an interactive choropleth map
- **Jupyter Notebook** (optional for inline viewing)

## Dataset

**Source**: [Our World in Data – COVID-19 Dataset](https://ourworldindata.org/coronavirus)

- Filename: `owid-covid-data.csv`
- Format: CSV
- Includes daily updates on:
  - Total cases, deaths, recoveries
  - Daily new cases/deaths
  - Total vaccinations
  - Country ISO codes

---

## Tools Used

- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Visualizations
- **Plotly Express** – Choropleth map
- **Jupyter Notebook / VS Code**

---

## Setup

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the environment:
   ```bash
   .\venv\Scripts\activate
   ```
4. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧪 Features & Analysis

- Data cleaning and missing value handling
- Trend analysis for:
  - Total and new cases
  - Total and new deaths
  - Vaccination rollouts
- Country comparison (e.g., Kenya 🇰🇪, USA 🇺🇸, India 🇮🇳)
- Global heatmap using a Plotly choropleth
- Markdown-based storytelling and key takeaways

---

## How to Run

1. Clone or download this project.
2. Ensure `owid-covid-data.csv` is in the same folder as the notebook.
3. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn plotly
   ```
4. Open the notebook with Jupyter or VS Code and run all cells.

---

## Sample Insights

- USA had one of the highest case counts globally.
- India's vaccination rollout ramped up sharply after initial delays.
- Kenya had lower total cases but a notable spike during mid-2021.
- Vaccination progress correlates with a drop in new case rates in many countries.

---

## License

This project is for educational and research purposes only.

---

## Acknowledgements

- [Our World in Data](https://ourworldindata.org/coronavirus)
- Johns Hopkins University
- Matplotlib, Seaborn, Plotly, and the Python community

---

## Author
Wayne Chibeu – PLP Africa Software Engineering Learner

---
## 📌 Note
This project was created for learning purposes as part of the Power Learn Project (PLP) software development track.
```

