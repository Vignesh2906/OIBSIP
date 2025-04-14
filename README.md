# 🗽 NYC Airbnb Data Cleaning & Exploratory Data Analysis (EDA)

This project involves **data cleaning** and **exploratory data analysis** on the [New York City Airbnb Open Data (2019)](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data).  
It was implemented using Python in Google Colab.

---

## 📌 Objectives

- Clean and preprocess the raw Airbnb dataset
- Remove null values, duplicates, and irrelevant features
- Explore key patterns through visualizations
- Understand trends related to room types, pricing, availability, and location

---

## 🧰 Tools & Libraries Used

- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset Info

- 📊 **Source:** [Kaggle NYC Airbnb Dataset](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)
- 🧾 **Columns:** id, name, host_id, neighbourhood, room_type, price, minimum_nights, number_of_reviews, availability_365, etc.
- 📌 **Size:** 49,000+ rows

---

## 🔧 Data Cleaning Steps

- Removed unnecessary columns (`id`, `host_id`, etc.)
- Handled missing values and removed rows with `NaN`
- Eliminated duplicates
- Converted data types for analysis
- Filtered extreme outliers (e.g., price > $1000 or minimum_nights > 365)

---

## 📊 Exploratory Data Analysis (EDA)

Here are some of the questions we explored:

- What are the most common room types?
- Which neighborhoods have the highest number of listings?
- What’s the average price distribution?
- How many days per year are listings usually available?
- Are there any correlations between price, availability, and reviews?

### 🔍 Visualizations Used:

- Count plots
- Bar plots
- Box plots
- Histograms
- Correlation heatmap

_All plots are available in the notebook._

---

## 📁 Project Structure

```
NYC-Airbnb-Data-Cleaning-and-EDA/
│
├── NYC_Airbnb_Data_Cleaning_and_EDA.ipynb
├── AB_NYC_2019.csv (optional)
├── README.md
└── visuals/ (optional folder for saved plots)
```

---

## 📌 Key Insights

- Most listings are **Entire home/apt**, followed by **Private rooms**
- **Manhattan** and **Brooklyn** dominate the listings
- Price mostly ranges from **$50 to $200**
- Entire homes are often less available across the year than private rooms

---

## 📽️ Video Walkthrough (Optional)

[👉 Click here to watch the walkthrough]() *(Add your YouTube/LinkedIn video link here)*

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://linkedin.com/in/yourprofile) or check out more projects!
