# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective:
To explore the Titanic dataset (`tested.csv`) using Python and uncover patterns related to passenger survival based on variables such as age, sex, passenger class, fare, and embarkation point.

---

## 🛠️ Tools Used:
- Google Colab
- Python
  - pandas
  - matplotlib
  - seaborn

---

## 🔍 Key Steps:

1. **Data Loading and Inspection**
   - Loaded `tested.csv` using pandas
   - Used `.head()`, `.info()`, `.describe()`, and `.isnull().sum()` to understand the structure and quality of the dataset

2. **Univariate Analysis**
   - Histograms and count plots for features like `Age`, `Fare`, `Survived`, `Sex`, and `Pclass`

3. **Bivariate and Multivariate Analysis**
   - Count plots and bar charts showing relationships between `Survived` and:
     - `Sex`
     - `Pclass`
     - `Embarked`
   - Box plots and violin plots for visualizing distribution of `Age` and `Fare` by survival status
   - Pair plot for numeric columns
   - Correlation heatmap

4. **Missing Value Detection**
   - Identified missing values in `Cabin`, `Age`, and `Embarked`
   - No imputation or cleaning done in this version

---

## 📊 Insights:
- Survival rates were higher for females and first-class passengers
- Third-class passengers had a lower survival rate
- Most passengers embarked from port 'S'
- Younger passengers had slightly better survival rates

---

## 📁 Files Included:
- `tested.csv`: The Titanic dataset used
- `task5_texted(1).ipynb`: Google Colab notebook containing the EDA
- `task5_texted-Colab-pdf`: PDF version of the analysis (optional export)
