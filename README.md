# SingaporeDream Project : Data-Driven TOTO Analysis

### ⚠️ Responsible Play Disclaimer

**This project is for educational and research purposes only.** The creator of this repository **does not condone or encourage participation of Prediction Markets**. Results derived from this exploration should be treated as a form of entertainment, not a way to make money. 

If you or someone you know is struggling with gambling-related issues, please seek help from the following resources:

* **Gambling Regulatory Authority (GRA):** [https://www.gra.gov.sg](https://www.gra.gov.sg)
* **National Council on Problem Gambling (NCPG):** [https://www.ncpg.org.sg](https://www.ncpg.org.sg)
* **National Problem Gambling Helpline:** 1800-6-668-668 (8 am to 11 pm daily)

---

## 📌 Overview

This project aims to build a comprehensive data pipeline and analytical toolset for Singapore Pools TOTO data. By combining web scraping, geospatial analysis, and machine learning, the project explores patterns in winning frequencies, outlet distributions, and historical results.

### Key Objectives

1. **Web Scraping:** Automated extraction of:
* Physical Singapore Pools outlet locations.
* Historical TOTO draw results.
* Specific "Winning Outlets" data for past draws.


2. **Exploratory Data Analysis (EDA):** Utilising Python and Jupyter Notebooks to visualise winning trends and geographic clusters.
3. **Predictive Modeling:** Exploring Machine Learning (ML) techniques to analyse frequency and statistical probability, while acknowledging the inherent randomness of lottery systems.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Libraries:**
* `BeautifulSoup4` / `Selenium`: For web scraping and data extraction.
* `Pandas`: For data manipulation and cleaning.
* `Matplotlib` / `Seaborn`: For data visualization.
* `Scikit-learn`: For machine learning and statistical modeling.
* `Geopy` / `Folium`: For mapping physical outlet locations.



---

## 📂 Project Structure

```text
├── data/               # Raw and processed CSV files
├── notebooks/          # Jupyter Notebooks for Analysis & ML
│   ├── 01_scraping.ipynb
│   ├── 02_eda.ipynb
│   └── 03_ml_modeling.ipynb
├── src/                # Python scripts for reusable functions
├── requirements.txt    # List of dependencies
└── README.md

```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. It is recommended to use a virtual environment.

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

```


2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Launch Jupyter:**
```bash
jupyter notebook

```



---

## ⚖️ Legal & Ethical Note

When using the scraping scripts in this repository, please ensure you:

* Respect the `robots.txt` of the target website.
* Do not overwhelm the servers with high-frequency requests (use `time.sleep()`).
* Acknowledge that data scraped is for personal, non-commercial use. The legality of web scraping depends on the website's Terms of Service and local regulations (e.g., Singapore's Computer Misuse Act).

---

## 🔮 Future Work

* Integrate smart extraction of batch updates for data compilation of new draw results.
* Develop a heatmap visualisation of "Lucky Outlets" across Singapore.
* Experiment with Deep Learning (LSTMs) to test the hypothesis of "hot" or "cold" numbers, purely for statistical curiosity.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
