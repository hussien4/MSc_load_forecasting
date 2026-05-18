# ⚡ Big data resolving using Apache Spark for load forecasting and demand response in smart grid: a case study of Low Carbon London Project

> **Master of Science (MSc) Thesis Repository**  
> *Author:* Hussien Ali El-sayed
> *Institution:* Cairo university 

This repository contains the core implementation, data pipelines, and predictive models developed for my MSc thesis. The research focuses on leveraging big data architecture and machine learning algorithms to optimize grid asset performance, manage load distributions, and improve overall electrical grid reliability.

---

## 🔬 Core Objectives & Methodology
The framework addresses the processing of high volume smart meters data to forecast load consumption for aggergated households. Accurate forecasting is the motive for applying demand response programs and integrating renewable energy resources efficiently. The problem is resolved in the big data context to handle the high volume fast pacing smart meters data using Pyspark. 

* **Core Language:** Python, Pyspark
* **Data Engineering & Big Data:** PySpark, NumPy, Pandas
* **Machine Learning & Deep Learning:** Spark SQL, Spark MLlib
* **Development Environment:** Google cloud Platform (GCP) on *Dataproc*. Google colab

---

## 📂 Repository Structure

```text
├── block0_eda_categorical/                        # Data down sampling for EDA to investigate insights
├── eda_block0/                                    # EDA for block 0 (A collection of 50 house holds)
├── hour_and_month_vs_energy/                      # Aggregated average energy consumption against hour and months.  
├── paper published.pdf/                           # The PDF format of the paper published on Journal of big data (https://link.springer.com/article/10.1186/s40537-024-00909-6) 
├── random_forest_regression_project_mllib.ipynb   # Random forest regression model for load forecasting
├── regression_model_all_blocks_final_version      # Regression model for all blocks including comapring model performance in computaional complexity and accuracy
├── regression_model_block0_final_version          # Regression model for block 0 including comapring model performance in computaional complexity and accuracy
└── README.md                                      # Project documentation

---

## Conclusion of the work

Accuracy of machine learning models surpassed 96 % for R2 metric with low comptational power. Also, a flowchart is proposed to utilize load forecasting results for demand response programs enabling integrating renewables for sustainable and efficient operation of smart grid.

