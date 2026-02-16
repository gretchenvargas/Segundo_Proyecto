# 📊 Mobile App A/B Test Analysis

This project analyzes the results of an A/B experiment conducted on a mobile application to evaluate the impact of interface changes on user behavior.

The study is based on event logs and seeks to determine if the implemented modifications generate significant improvements in conversion rates.

---

## 📁 Project Content

- `Segundo_Proyecto.ipynb` → Complete analysis in a Jupyter Notebook  
- `logs_exp_us.csv` → Experiment dataset (not included)

---

## 🎯 Objective

The main objectives are:

- **Analyze user behavior** within an A/B testing framework.
- **Compare control groups** against the test group.
- **Evaluate conversion funnels** to identify drop-off points.
- **Statistically validate** the experiment results.
- **Determine effectiveness** of the implemented interface changes.

---

## 🧹 Data Preparation

During the analysis, the following tasks were performed:

- **Column Renaming:** Standardizing headers for clarity.
- **Timestamp Conversion:** Transforming raw data into date/time formats.
- **Feature Engineering:** Creating time-based variables.
- **Data Integrity:** Handling null values and removing duplicates.
- **Validation:** Cleaning logs to ensure consistent records.

---

## 📈 Analysis Performed

- **Exploratory Data Analysis (EDA):** Initial data discovery.
- **Event Volume:** Measuring event frequency per group.
- **User Behavior:** Tracking user interactions.
- **Conversion Funnel:** Visualizing the journey from start to finish.
- **Visualizations:** Custom charts using Matplotlib.

---

## 🧪 Hypothesis Testing

Statistical tests were applied to evaluate differences between groups:

- **Proportion Tests:** Comparing conversion rates between groups.
- **Statistical Significance:** Assessing p-values and confidence levels.
- **Multiple Testing:** Ensuring validity when comparing multiple groups (A/A/B).

**Key Hypotheses:**
- Is there a significant difference between the control groups (A/A)?
- Does the experimental group (B) outperform the control groups in conversion?

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn
- **Statistics:** SciPy
- **Environment:** Jupyter Notebook
