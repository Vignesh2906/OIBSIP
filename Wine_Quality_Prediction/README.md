# Wine Quality Prediction using Machine Learning

This project involves predicting wine quality based on physicochemical properties using machine learning models. 
The dataset used is the **Wine Quality Dataset** from Kaggle Wine Quality Dataset, and the project was implemented in **Python using Google Colab**.

---

## Objectives

- Explore and understand the wine quality dataset
- Perform data cleaning and preprocessing
- Visualize relationships between features and target variable
- Build and evaluate multiple machine learning models
- Compare performance and select the best model for prediction

---

## Tools & Libraries Used

- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset Info

- **Source:** [Kaggle Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)
- **Columns:**
  - Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar, Chlorides  
  - Free Sulfur Dioxide, Total Sulfur Dioxide, Density, pH, Sulphates, Alcohol

---

## 🧹 Data Preprocessing

- Checked and handled missing values
- Scaled features using **StandardScaler**
- Converted quality scores into binary classification (Good vs Bad)
- Split data into training and testing sets

---

## 📊 Exploratory Data Analysis (EDA)

**Insights Discovered:**
- **Alcohol** and **sulphates** show a positive correlation with quality
- **Volatile acidity** negatively impacts wine quality
- Most wines fall between quality scores of **5 to 7**
- Class imbalance exists — more average wines than high/low quality

**Visualizations Included:**
- Correlation heatmap
- Distribution plots
- Box plots of features vs quality
- Countplot of wine quality
- Feature importance from ML models
  
_All plots are available in the notebook._

## Model Building
- **Model Used:** Random Forest Classifier
- Achieved ~70% accuracy on test data.
- Evaluated using accuracy score and confusion matrix.

---

## Conclusion
This project shows that it's possible to reasonably predict wine quality using machine learning based on chemical properties alone. This could help wine producers in quality control.

---

## Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/vignesh-m-536642166/) or check out more projects!
