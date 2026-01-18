# Applied-Data-Science-Capstone
# 🚀 SpaceX Falcon 9 Landing Prediction: Applied Data Science Capstone

## 📌 Project Overview
This project predicts the success of SpaceX Falcon 9 first-stage landings. With launch costs reaching $165 million for traditional providers, SpaceX's ability to reuse the first stage (reducing costs to $62 million) creates a significant competitive advantage. This project uses machine learning to determine if a first stage will land successfully, allowing for better cost estimation.

## 🛠️ Tech Stack & Methodology
- **Data Engineering**: Python, Pandas, Requests (API), BeautifulSoup (Web Scraping).
- **Database Management**: SQL (IBM DB2 / SQLite) for complex data queries.
- **Exploratory Data Analysis**: Seaborn and Matplotlib for statistical visualization.
- **Geospatial Analysis**: Folium for interactive mapping of launch site proximity to coastlines.
- **Interactive Analytics**: Plotly Dash for a real-time flight monitoring dashboard.
- **Machine Learning**: Scikit-Learn (Logistic Regression, SVM, Decision Trees, KNN) optimized with GridSearchCV.

## 📊 Key Results
- **EDA**: Identified a strong correlation between Flight Number and landing success, indicating a "learning curve" in SpaceX's operational history.
- **Interactive Maps**: Confirmed all launch sites are strategically located near oceans to mitigate inland debris risk.
- **Predictive Modeling**: Achieved a **test accuracy of 83.33%** across all tuned models. While scores were tied, the SVM and Logistic Regression models demonstrated the highest stability during cross-validation.

## 📁 Repository Contents
- `Notebooks/`: Complete end-to-end data science pipeline.
- `Dashboard/`: Plotly Dash application for interactive visualization.
- `Presentation/`: Final executive summary and results in PDF format.
