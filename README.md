# Titanic Survival Analysis | Python EDA & Visualization

This project focuses on statistical and visual exploration of the Titanic dataset using Python libraries such as Pandas, Matplotlib, and Seaborn. The objective is to analyze the patterns and factors that influenced passenger survival.

---

## Dataset

The repository includes the following files:
- `train.csv` – Main training dataset with survival labels.
- `test.csv` – Test dataset without survival labels.
- `gender_submission.csv` – Sample submission file.
- `Titanic_Exploration.ipynb` – Jupyter/Colab notebook containing the complete analysis.
- `Titanic_Exploration.pdf` – Exported report version of the notebook.

Dataset Source: [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

---

## Tools and Libraries

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Exploratory Analysis

The following steps were performed:
- Loaded and understood dataset structure using `.info()`, `.describe()`, and `.value_counts()`.
- Visualized feature distributions and relationships:
  - Histogram of Age
  - Boxplot of Age vs. Survival
  - Countplot of Sex vs. Survival
  - Countplot of Pclass vs. Survival
  - Correlation heatmap

---

## Key Insights

- Female passengers had a significantly higher survival rate compared to males.
- First-class passengers had better survival chances, indicating the influence of socio-economic status.
- Younger passengers, especially children, were more likely to survive.
- Passengers who paid higher fares were more likely to survive.
- Age showed a slight negative correlation with survival.

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/ajaygande/titanic-survival-analysis-python.git
   ```

2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Open `Titanic_Data_Exploration_Python.ipynb` in Jupyter Notebook or upload it to Google Colab.

4. Run the notebook to explore the data and generate visualizations.

---

## Author

**Ajay Sudhakar Gande**  
Email: ajaygande1@gmail.com  
LinkedIn: [https://www.linkedin.com/in/ajay-gande-5a38b2273](https://www.linkedin.com/in/ajay-gande-5a38b2273)

