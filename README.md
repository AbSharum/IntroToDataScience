# Intro to Data Science Coursework

Jupyter notebook labs, problem sets, and a final project from an Introduction to Data Science course. Each notebook works with a different real-world dataset to practice cleaning, exploratory analysis, statistics, and basic ML.

## Contents

- `Final Project/cars.ipynb` — Exploratory analysis of Dubai used-car listings (`dubaiCars.csv`): price distributions, correlations between price and features (mileage, year, engine size, etc.) using pandas/numpy/scipy stats and matplotlib plots. Includes an exported `cars.html` report and a write-up (`Abraham Sharum.docx`).
- `Labs/Lab1` & `Lab2` — Pandas data-wrangling exercises (custom `Customer` class, basic OOP + data manipulation).
- `Labs/Lab3`, `Lab4` — Data cleaning/manipulation with pandas, numpy, and `datetime`.
- `Labs/Lab5`, `Lab6` — Statistical analysis (ANOVA/multiple comparisons via `statsmodels.stats.multicomp`, `scipy.stats`) with matplotlib visualization.
- `Labs/Lab7` — Exploratory analysis/visualization with pandas, matplotlib, and seaborn.
- `Labs/Lab8/Lab8P1.ipynb` — Classification model comparison (Logistic Regression, LDA, KNN, Decision Tree, Naive Bayes, SVM) with stratified k-fold cross-validation, using scikit-learn.
- `Labs/Lab8/Lab8P2.ipynb` — NLP preprocessing with NLTK (tokenization, stopword removal, stemming, lemmatization).
- `Problem Sets/PS1-3` — Supporting problem sets on data manipulation (pandas/numpy/datetime) and statistical testing (scipy.stats, statsmodels).

## Stack

Python, Jupyter Notebook. Libraries used across the notebooks: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `nltk`.

## Running

```
pip install pandas numpy scipy matplotlib seaborn scikit-learn statsmodels nltk jupyter
python -m nltk.downloader punkt stopwords wordnet
jupyter notebook
```

Then open any `.ipynb` file under `Final Project/`, `Labs/`, or `Problem Sets/`. Datasets referenced by the notebooks (e.g. `dubaiCars.csv`) are included alongside them.
