Youtube Data Scraping Course Project: Digital Business Analytics (DS-464)
=======
# 🏎️ Formula 1 Data Analytics Dashboard

An end-to-end **data analytics project** focused on **Formula 1 racing**, integrating **descriptive analytics**, **predictive modeling**, and an **interactive dashboard** to deliver meaningful insights from motorsport data.

---

## 📌 Project Description

This project aims to analyze historical Formula 1 data and extract insights through:

* **Descriptive Analytics** to understand past trends and performance
* **Predictive Analytics** to forecast race-related outcomes
* **Dashboard Integration** for interactive data exploration

The repository follows **clean Git practices**, avoids committing large/generated files, and ensures full **reproducibility**.

---

## 📂 Folder Structure

```
.
├── Descriptive/                 # Descriptive analytics
│   ├── data/
│   │   ├── processed/
│   │   └── raw/
│   ├── notebooks/
│   │   ├── 01_extraction.ipynb
│   │   ├── 02_cleaning.ipynb
│   │   ├── 03_feature_eng.ipynb
│   │   └── 04_eda_vis.ipynb
│   ├── src/
│   │   ├── __init__.py
│   │   ├── analytics.py
│   │   ├── config.py
│   │   ├── utils.py
│   │   └── youtube_extractor.py
│   └── run_analytics.py
├── Predictive/                  # Predictive modeling
│   ├── f1_dashboard.py          
│   ├── main_script.py
│   ├── driver_rankings_2024.csv
│   ├── driver_performance_2024.csv
│   ├── 2025_predictions.csv
│   ├── 2025_champion_prediction.txt
│   ├── f1_cache/                # Cached intermediate files
│   └── f1_data_cache/           # Auto-generated datasets
├── 2025_champion_prediction.txt
├── .gitignore
├── README.md
└── requirements.txt
```

---

## 📊 Descriptive Analytics

The **Descriptive** module focuses on understanding historical Formula 1 data through:

* Driver and constructor performance analysis
* Season-wise trends and comparisons
* Race result distributions
* Data visualization for insights

**Technologies used:**

* Pandas
* Matplotlib / Seaborn
* Scikit
* Jupyter Notebook

---

## 🤖 Predictive Analytics

The **Predictive** module applies machine learning techniques to:

* Perform feature engineering on historical race data
* Train predictive models
* Evaluate model performance
* Analyze patterns affecting race outcomes

**Approaches include:**

* Regression models
* Classification models
* Feature-based prediction pipelines

---

## 📈 Dashboard

The dashboard serves as a **unified interface** for both the **Descriptive** and **Predictive** parts of the project.

The dashboard serves as a **unified interface** that:

* Integrates descriptive and predictive insights
* Enables interactive exploration
* Presents results in a user-friendly format

This allows both technical and non-technical users to explore the data effectively.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/ahmedmusharaf31/dba-reddit-project.git
cd dba-youtube-project
```

### 2️⃣ Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🗄️ Data Handling & Git Policy

> **Large database and cache files are intentionally excluded from version control.**

### Ignored via `.gitignore`:

```gitignore
*.db
f1_cache/
f1_data_cache/
```

### Why?

* `.db` files are large and auto-generated
* They are environment-specific
* Best practice is to regenerate data via scripts

✔ Clean Git history
✔ No GitHub file-size issues
✔ Reproducible workflows

---

## 🔁 Reproducibility

To recreate data or results:

1. Run the F1_dashbaord via this command:
   ```bash
   python -m streamlit run f1_dashboard.py
   ```
   (It will take some time to run for the very first time, then it will store the data in the cache)
3. Enjoy!

No committed binary or database files are required.

---

## 🚀 Future Enhancements

* Advanced machine learning models
* Real-time data integration
* Enhanced dashboard interactivity
* Automated data pipelines

---

## 👨‍💻 Contributors

* **Saaim Ali Khan**
* **Ahmed Musharaf**
* **Muhammad Arsal** 

---

## 📄 License

This project is developed for **academic and educational purposes**.

---

## ⭐ Final Notes

This repository demonstrates a **complete data analytics lifecycle**, from raw data exploration to predictive insights, while following **industry-standard Git practices**.

If you find this project useful, feel free to ⭐ the repository!
