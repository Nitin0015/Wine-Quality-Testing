# **Wine Quality Prediction**

This repository contains a Jupyter Notebook that demonstrates how to predict wine quality using machine learning techniques. The dataset used in this project provides chemical properties of wine and their corresponding quality scores.

---

## **Overview**

The goal of this project is to predict wine quality based on its physicochemical properties. Wine quality is scored on a scale from 0 to 10, and this project uses a classification approach to predict whether a wine is of good quality or not. The model implemented in this notebook is based on a **Random Forest Classifier**, a robust ensemble learning method.

The dataset includes features such as acidity, sugar content, alcohol level, and more, with the target variable (`quality`) indicating the wine's quality score.

---

## **Dataset**

- **Source**: The dataset appears to be related to publicly available wine datasets, such as those from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).
- **Features**:
  - `fixed acidity`: Tartaric acid concentration in g/dm³.
  - `volatile acidity`: Acetic acid concentration in g/dm³.
  - `citric acid`: Citric acid concentration in g/dm³.
  - `residual sugar`: Amount of sugar remaining after fermentation (g/dm³).
  - `chlorides`: Sodium chloride concentration (g/dm³).
  - `free sulfur dioxide`: Free SO₂ concentration (mg/dm³).
  - `total sulfur dioxide`: Total SO₂ concentration (mg/dm³).
  - `density`: Density of the wine (g/cm³).
  - `pH`: Acidity level of the wine.
  - `sulphates`: Potassium sulphate concentration (g/dm³).
  - `alcohol`: Alcohol content (% by volume).
- **Target Variable**:
  - `quality`: Quality score of the wine (integer values from 0 to 10).

---

## **Project Workflow**

1. **Data Loading**:
   - The dataset (`WineData.csv`) is loaded into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics and visualizations are generated using Seaborn and Matplotlib.
3. **Data Preprocessing**:
   - Features are scaled and normalized where necessary.
   - Outliers and missing values are handled appropriately.
4. **Model Training**:
   - A Random Forest Classifier is trained to classify wine quality.
   - The dataset is split into training and testing sets using `train_test_split`.
5. **Model Evaluation**:
   - Accuracy score and other performance metrics are calculated to evaluate the model's performance.

---

## **Dependencies**

To run this project, you need the following Python libraries:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

---

## **How to Run**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/WineQualityPrediction.git
   cd WineQualityPrediction
   ```

2. Ensure that the dataset file (`WineData.csv`) is in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Wine-Test.ipynb
   ```

4. Run all cells in the notebook to execute the code.

---

## **Results**

The Random Forest Classifier provides predictions for wine quality based on its chemical properties. Accuracy and other evaluation metrics indicate how well the model performs in classifying wines as good or poor quality.

---

## **Acknowledgments**

- The dataset was sourced from publicly available wine datasets, such as those hosted by platforms like [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).

---
