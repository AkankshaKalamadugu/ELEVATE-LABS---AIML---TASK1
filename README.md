# 🧹 Titanic Dataset - Data Cleaning & Preprocessing

## 📁 Dataset Used
**Name**: Titanic Survival Dataset  
**Source**: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)

## 🔍 Steps Performed

### 1. Data Exploration
- Loaded dataset using `pandas`
- Displayed info, summary statistics, and null value counts

### 2. Handling Missing Values
- Filled missing `Age` values with mean
- Filled missing `Embarked` values with mode
- Dropped `Cabin` column due to excessive missing data

### 3. Encoding Categorical Variables
- Used **one-hot encoding** for `Sex` and `Embarked`
- Used **Label Encoding** for `Pclass` (optional)

### 4. Feature Scaling
- Standardized `Age` and `Fare` using `StandardScaler`

### 5. Outlier Detection & Removal
- Visualized `Age` and `Fare` using boxplots
- Removed outliers in `Fare` column using the IQR method

---

## 🛠️ Tools & Libraries Used
- Python (Google Colab)
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📦 Files Included
├── Titanic_Preprocessing.ipynb # Google Colab Notebook
├── titanic.csv # Raw dataset (uploaded in Colab)
├── titanic_cleaned.csv # Final cleaned dataset
└── README.md # Project overview and documentation
