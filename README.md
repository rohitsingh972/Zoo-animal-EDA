# Zoo-animal-EDA
# Zoo Animals EDA

Exploratory Data Analysis (EDA) of the **UCI Zoo Dataset** using Python, NumPy, Pandas, and Matplotlib. This project examines animal class distributions, biological characteristics, and data quality without machine learning.

---

## Student Details
* **Name:** Rohit Singh
* **Roll Number:** 2026B01010067
* **Course:** B.Tech – Computer Science and Engineering (CSE)

---

## Dataset Overview
* **Dataset Name:** UCI Zoo Dataset
* **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/111/zoo)
* **Size:** 101 rows × 18 columns
* **Features:** Animal name, 15 binary biological traits (`hair`, `feathers`, `eggs`, `milk`, `airborne`, `aquatic`, `predator`, `toothed`, `backbone`, `breathes`, `venomous`, `fins`, `tail`, `domestic`, `catsize`), `legs`, and `class_type` (1–7).

---

## Analysis Questions Covered
1. How many animals are present in each animal type?
2. How many animals have hair, feathers, eggs, or milk?
3. Which animal types have the largest number of records?
4. Which animals are both aquatic and predator?
5. What are the most common characteristics in the dataset?
6. Are there any missing values or duplicate records?

---

## Tools & Libraries Used
* **Python 3**
* **Pandas** (`head()`, `tail()`, `info()`, `describe()`, `value_counts()`, filtering, sorting, `groupby()`)
* **NumPy** (array-based counts, percentages, and descriptive statistics)
* **Matplotlib** (bar charts for animal types and characteristic comparisons)

---

## Key Observations
1. **Mammals and Birds Dominate:** Out of 101 animals, Mammals (41) and Birds (20) account for over 60% of the dataset, while Amphibians (4) and Reptiles (5) have the fewest records.
2. **Most & Least Common Traits:** `backbone` (83), `breathes` (80), `tail` (75), and `eggs` (59) are the most common traits, whereas `venomous` (8) and `domestic` (13) are the rarest.
3. **Aquatic Predators & Data Quality:** 28 animals are both aquatic and predators across Fish, Mammals, Birds, and Invertebrates. The dataset has **0 missing values** and **0 exact duplicate rows** (with `"frog"` appearing twice as two distinct species variants: venomous and non-venomous).

---

## Repository Files
* `Zoo_Animals_EDA.ipynb` – Complete Google Colab / Jupyter Notebook with code, outputs, and charts
* `Zoo_Animals_EDA_SRS_Rohit_Singh.docx` – Software Requirements Specification (SRS) document
* `README.md` – Project overview

---

## How to Run
1. Open `Zoo_Animals_EDA.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Run all cells — the dataset loads directly from the UCI repository URL.
