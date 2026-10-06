# Predicting Grade 12 STEM Enrollment Across Philippine Schools Using Machine Learning

## 📌 Project Overview

This project explores whether **Grade 12 STEM male enrollment** across Senior High School–offering schools in the Philippines can be predicted using school characteristics, location, and other relevant school-level variables.

The project applies **machine learning for regression**, with a focus on **Random Forest Regression**, to identify patterns associated with Grade 12 STEM enrollment and evaluate how well school-level information can be used for prediction.

This project was developed as part of **STAT 516 – Applied Predictive Modeling**.

---

## 🎯 Research Question

> **Can we predict the number of Grade 12 STEM male students in Senior High School–offering schools using school location, characteristics, and other relevant school-level variables?**

### Target Variable

**Grade 12 STEM Male Enrollment (`g12_stem_male`)**

The analysis focuses specifically on schools that offer Senior High School and have available Grade 12 STEM male enrollment data.

---

## 📂 Repository Structure

```text
Predicting-Grade-12-STEM-Enrollment-Across-Philippine-Schools-Using-Machine-Learning/
│
├── Dataset/
│   ├── dataset.csv
│   └── README.md
│
├── Notebooks/
│   └── Predictive Modelling_ea.ipynb
│
├── Presentation/
│   ├── Key Insights.txt
│   └── Presentation.pptx
│
└── README.md
```

### `Dataset/`

Contains the dataset used for the analysis, along with information about its source and the original data provider.

The dataset was obtained from the **Department of Education (DepEd) Philippines**.

The `Dataset` folder also contains the source information and link to the original dataset.

### `Notebooks/`

Contains the Jupyter Notebook used for data preprocessing, exploratory data analysis, model development, evaluation, and visualization.

### `Presentation/`

Contains the project's presentation materials and key findings:

- **`.txt`** – Bite-sized summary of the key insights and findings.
- **`.pptx`** – Presentation of the project, methodology, results, and insights.

---

## 🚀 How to Run the Project

The main analysis is contained in the following notebook:

**[Predictive Modelling_ea.ipynb](https://github.com/mysteryea7107/Predicting-Grade-12-STEM-Enrollment-Across-Philippine-Schools-Using-Machine-Learning/blob/main/Notebooks/Predictive%20Modelling_ea.ipynb)**

To reproduce the analysis:

1. Open the notebook.
2. Download or clone this repository.
3. Make sure the required dataset is available from the `Dataset/` folder.
4. Open the notebook using **Google Colab or Jupyter Notebook**.
5. Run the notebook cells sequentially from data loading through model evaluation and visualization.

> **Recommended:** Run `Predictive Modelling_ea.ipynb` from beginning to end to reproduce the preprocessing, analysis, modeling, and results.

---

## 🔬 Methodology

The project follows a typical predictive modeling workflow:

1. **Data Selection**
2. **Data Understanding and Exploration**
3. **Data Cleaning and Preprocessing**
4. **Feature Selection**
5. **Exploratory Data Analysis**
6. **Train-Test Split**
7. **Random Forest Regression**
8. **Model Evaluation**
9. **Visualization and Interpretation**
10. **Key Findings and Insights**

Special attention was given to missing values and the structure of the dataset, particularly because not all schools offer Senior High School or the STEM strand.

---

## 🤖 Machine Learning Model

### Random Forest Regression

The primary predictive model used in this project is **Random Forest Regression**.

Random Forest was selected because it can capture **non-linear relationships and interactions between variables** without requiring strong assumptions about the underlying relationship between predictors and the target variable.

The model was used to estimate the number of Grade 12 STEM male students based on available school-level characteristics and other relevant predictors.

---

## 📊 Key Insights

The analysis investigates patterns in Grade 12 STEM enrollment across Philippine schools, including differences associated with:

- School characteristics
- School location
- Public and private schools
- Other Senior High School strand enrollment patterns
- Enrollment-related variables
- Factors associated with higher or lower Grade 12 STEM male enrollment

### 📌 Bite-Sized Insights

A concise summary of the project's key findings can be found in:

**`Presentation/Key Insights.txt`**

For the complete discussion of the findings, methodology, and results, see the presentation:

**`Presentation/Presentation.pptx`**

---

## 📚 Data Source

The dataset contains **school-level information from Philippine schools**, including school characteristics, location, grade levels offered, and enrollment-related information.

**Source:** Department of Education (DepEd), Philippines

The original source and dataset information are documented in the `Dataset/` folder.

---

## 🛠️ Tools & Technologies

- **R / RStudio / Google Colab**
- **Python / Jupyter Notebook** for notebook-based project organization
- **Random Forest Regression**
- **Data preprocessing and exploratory data analysis**
- **Data visualization**
- **GitHub** for version control and project documentation

---

## 📁 Project Deliverables

| Component | Description |
|---|---|
| `Dataset/` | Dataset and source information |
| `Notebooks/` | Predictive modeling notebook |
| `Presentation/` | Presentation and bite-sized key insights |
| `README.md` | Project documentation |

---

## 👤 Author

**Emerson**

Data Science | Data Analytics | Data Scientist

---

## 📌 Note

This project is intended for **academic and educational purposes**, demonstrating the application of predictive modeling and machine learning techniques to a real-world Philippine education dataset.
