PRODIGY DS TASK-02 - TITANIC EDA WITH PYTHON:
- This project completes Task‑02 of the Prodigy InfoTech Data Science internship, which is to perform data cleaning and exploratory data analysis (EDA) on a dataset of choice. The classic Titanic dataset is used to explore relationships between passenger features and survival, and to identify key patterns and trends in the data.

FEATURES:
- Uses the Titanic train, test, and gender_submission CSV files provided in the Prodigy sample dataset.
- Cleans missing values, encodes categorical variables (e.g., Sex, Embarked), and engineers useful features in PT_Task2.ipynb.
- Performs EDA visualizations to study relationships between Survived and variables like Sex, Pclass, Age, Fare, SibSp, Parch, and Embarked.
- Summarizes important findings about which groups of passengers had higher or lower survival rates.

INSTALLATION:
- git clone https://github.com/IshanGain/PRODIGY_DS_02.git
- cd PRODIGY_DS_02
- pip install pandas numpy matplotlib seaborn

- Open the folder in your preferred IDE or Jupyter environment.

USAGE:
1. Start Jupyter:
   - jupyter notebook
2. Open PT_Task2.ipynb.
3. Run all cells to:
   - Load train.csv, test.csv, and gender_submission.csv.
   - Clean and preprocess the data.
   - Generate descriptive statistics and plots (histograms, bar plots, count plots, correlation heatmaps, etc.) to understand survival patterns.

PROJECT STRUCTURE:
- PRODIGY_DS_02/
- ├── PT_Task2.ipynb        # Main notebook for Task‑02 EDA
- ├── train.csv             # Titanic training data
- ├── test.csv              # Titanic test data
- ├── gender_submission.csv # Sample submission file
- ├── .gitattributes
- └── README.md             # Project documentation

