# 🧠 Data Science Bootcamp 2025

This repository contains hands-on projects from the **Data Science Bootcamp 2025**, focused on building core skills in exploratory data analysis (EDA), visualization, and data storytelling.

---

## 📁 Project: Hospital Readmission Analysis

### 📌 Objective

Analyze hospital admission data to uncover useful patterns related to gender, age, department, admission type, and room assignments. The goal is to support hospitals in improving resource allocation and reducing patient waiting times.

---

## 📊 Dataset

- **Source**: [Kaggle – Hospital Admissions Data](https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data)
- **File**: `hospital_admissions_data.csv`
- **Fields**:
  - `age`, `gender`, `admission_type`, `department`, `room_type`, `admission_day`, etc.

---

## 🛠 Installation

To run this project locally:

### 1. Clone the repository

```bash
git clone https://github.com/sohaibzafar89/Data-Science-Bootcamp-2025.git
cd Data-Science-Bootcamp-2025
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv .venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies 

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Open the Jupyter Notebook to explore and run the code:

```bash
jupyter notebook
```

Navigate to:

```markdown
Phase_1_Exploratory_Data_Analysis/
└── Project_01_Hospital_Readmission_Analysis/
    └── Hospital Readmission Analysis.ipynb
```

Run the notebook cell-by-cell to understand the analysis and visualizations.

## 📈 Results

Key insights from the EDA include:

- **Gender Distribution**: Balanced or skewed gender in admissions.
- **Age Patterns**: Higher admission frequency among elderly patients.
- **Common Admission Types**: Emergency admissions are most common.
- **Department Load**: Certain departments handle a higher patient load.
- **Room Preferences**: Semi-private or general rooms are most frequently assigned.
- **Admission Days**: Specific weekdays show peaks in patient admissions.
- **Previous Visits**: A good portion of patients have been previously admitted.

Visualizations include bar charts and count plots built using **Matplotlib** and **Seaborn**.

## 📦 Folder Structure

```markdown
Data-Science-Bootcamp-2025/
├── .gitignore
├── .gitattributes
├── Phase_1_Exploratory_Data_Analysis/
│   └── Project_01_Hospital_Readmission_Analysis/
│       ├── Hospital Readmission Analysis.ipynb
│       ├── hospital_admissions_data.csv
|       ├── requirements.txt
```

## 🧰 Tools Used

- **Python (Jupyter Notebook)**
- **Pandas**
- **Matplotlib**
- **Seaborn**

## 📬 Contact

For questions or suggestions, feel free to reach out via GitHub Issues or fork and contribute to this repo!
