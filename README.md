# ✈️ Flight Delay Analytics with Apache Spark

This project focuses on Big Data processing and analysis using **Apache Spark**. We analyzed a large dataset of flight records to identify delay patterns, calculating departure delays and cancellation rates.

The core objective was to perform a **comparative analysis between Spark RDD and DataFrame APIs**, evaluating their execution efficiency and performance optimization mechanisms (Catalyst Optimizer).

## 📄 Project Report
For a detailed analysis of the methodology, performance metrics, and conclusions, please refer to the full report:
👉 **[View Project Report (PDF)](Project_Report.pdf)**

## 🚀 Key Features

* **Big Data Processing:** Handling large-scale flight data using PySpark.
* **API Comparison:** Implementing the same queries using both **RDD** (Resilient Distributed Dataset) and **DataFrame** APIs to benchmark performance.
* **Data Cleaning:** Preprocessing raw CSV data, handling null values, and type casting.
* **Visualization:** Creating insight charts (Hourly Delays, Airline Delays) using `matplotlib` and `seaborn`.

## 📊 Performance Insights

As detailed in the report, the **DataFrame API** consistently outperformed RDDs due to:
* **Catalyst Optimizer:** Automatic query optimization plan.
* **Tungsten Execution Engine:** Optimized memory management and code generation.

## 🛠️ Technologies Used

* **Language:** Python 3
* **Framework:** Apache Spark (PySpark)
* **Environment:** Google Colab
* **Libraries:** `pyspark`, `pandas`, `matplotlib`, `seaborn`

## ⚙️ How to Run

1.  Open the notebook `flight_delay_spark.ipynb` in **Google Colab** or a local Jupyter environment.
2.  Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Load your dataset (ensure the path in the code matches your file location).
    **Dataset Setup:**
    * This project uses a specific flight dataset provided for the academic course.
    * **Note:** Due to GitHub's file size limits, the dataset is not included in this repository.
    * To run the code, please place your own flight data CSV file (e.g., `flights.csv`) in the project root directory and update the file path in the notebook if necessary.
4.  Run all cells to execute the Spark jobs.

## 👥 Authors

* **Aliki Bliona** - *Data Engineering & RDD Implementation*
* **Theodoros Panagiotidis** - *Data Analysis & Visualization*

---
*This project was developed as part of the "Big Data Analytics" course at the University of Macedonia.*