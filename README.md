# 🧪 Clustering Analysis on Air Quality Dataset

## 📌 Overview
This project explores unsupervised clustering techniques on an urban air quality dataset. The dataset includes environmental measurements such as pollutant concentrations, sensor outputs, and weather-related features. This work was done using Google Colab.

- **Source**: Likely from the UCI Machine Learning Repository  
- **Total Records**: 9,471  
- **Valid Records**: 9,357 (after handling missing values)  
- **Features**: 17 total (including 2 non-informative columns)  
- **Date Range**: Starting from October 3, 2004

---

## 🎯 Objective
The primary goal is to apply clustering algorithms to identify similar air quality patterns and explore pollution behavior in an unsupervised manner.

---

## 📚 Why This Dataset?
This dataset was chosen due to its richness in real-world environmental and urban monitoring data. It offers opportunities to practice:
- Time series forecasting
- Clustering analysis
- Anomaly detection
- Correlation studies  
These are relevant to public health, environmental policy, and smart city planning.

---

## 📊 Column Overview
- **Date and Time**: Measurement timestamps
- **Air Pollutants**: `CO(GT)`, `NOx(GT)`, `NO2(GT)`, `NMHC(GT)`, `C6H6(GT)`
- **Sensor Readings**: `PT08.S1` to `PT08.S5`
- **Weather Data**: `Temperature (T)`, `Relative Humidity (RH)`, `Absolute Humidity (AH)`
- **Other Columns**: Two unnamed columns (`Unnamed: 15`, `Unnamed: 16`) with NaN only

---

## 🛠️ Data Cleaning Steps
1. Dropped `Unnamed: 15` and `Unnamed: 16` columns (contained only NaN).
2. Combined `Date` and `Time` into a single `Datetime` column.
3. Handled missing values using time-based interpolation techniques.

---

## 🔍 Clustering Algorithms Explored
- **K-Means Clustering**: Fast and effective for partitioning pollution patterns.
- **DBSCAN**: Good for finding anomalies and noise in the data.
- **Mean Shift**: Identifies clusters without predefining the number.
- **Gaussian Mixture Models (GMM)**: Probabilistic model for soft clustering.
- **Agglomerative Clustering**: A hierarchical approach, useful for exploring tree-like structures.

---

## 📈 Analysis Opportunities
- Visualizing pollutant levels over time
- Identifying trends and clusters in pollution data
- Exploring anomalies and outliers
- Understanding feature influence on air quality

---

## 💻 Tools Used
- Google Colab
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📎 [View Notebook in Google Colab](https://colab.research.google.com/drive/17_I4Hk_UxWzRYKTMubTFDqOuuEnY9w6J?usp=sharing)
## 📎 [View Project Repository](https://github.com/sojunrakib/Air-Quality-Dataset-Clustering/blob/main/Air_Quality_.ipynb)

---

## 📬 Contact
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/rakibul-hasan20?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BXOjHOpSwSfmdSlgofIinZQ%3D%3D) for collaboration or feedback!
