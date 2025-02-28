# Movie Recommendation Search Engine

## Project Overview
This project implements a **Movie Recommendation Search Engine** using **Apache Spark on Databricks**. It leverages **collaborative filtering** and **content-based filtering** techniques to provide personalized movie recommendations. The project is designed to handle large-scale movie datasets efficiently using Databricks' distributed computing capabilities.

## Features
- **User-based and item-based collaborative filtering**
- **Content-based recommendations** using movie metadata
- **Spark MLlib for scalable machine learning**
- **Databricks notebooks for seamless development**
- **Optimized query execution with SparkSQL**

## Technologies Used
- **Databricks (Community Edition)**
- **Apache Spark (PySpark, Spark MLlib)**
- **Python (Pandas, NumPy, Scikit-Learn)**
- **Delta Lake for data storage**
- **MovieLens Dataset**

## Prerequisites
- A **Databricks Community Edition** account
- Basic understanding of **Spark and Machine Learning**
- Python libraries: `pyspark`, `pandas`, `numpy`, `scikit-learn`

## Installation & Setup
1. **Clone the repository** (or create a new GitHub repo for version control):
   ```bash
   git clone https://github.com/prathameshbhavsar19/movie-recommendation.git
   cd movie-recommendation
   ```
2. **Import the notebook into Databricks**:
   - Open Databricks Community Edition
   - Go to **Workspace** → **Import**
   - Upload `movie_recommendation.ipynb`
3. **Load the dataset**:
   - Upload the **MovieLens dataset** to Databricks' **DBFS**.
   - Use `spark.read.csv()` to load the dataset.

## Usage
1. Run the notebook in Databricks.
2. Train the recommendation model using **ALS (Alternating Least Squares)** for collaborative filtering.
3. Query the search engine for personalized movie recommendations.
4. Optimize performance with Spark SQL queries.

## Sample Output
```
Top 5 movie recommendations for user 123:
1. Inception (2010)
2. The Dark Knight (2008)
3. Interstellar (2014)
4. The Matrix (1999)
5. Fight Club (1999)
```

## Future Enhancements
- Implement **deep learning-based recommendation systems**
- Deploy as an **API using FastAPI or Flask**
- Integrate with **real-time streaming data** for dynamic recommendations

## Author
**Prathamesh Bhavsar**

## License
This project is open-source and available under the MIT License.

