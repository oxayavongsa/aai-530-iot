# Sample Template
## 🏡 Smarter Living: Unlocking Insights from IoT Data
### 📚 AAI-530 IoT and Machine Learning Final Project
University of San Diego, School of Engineering - Masters of Applied Artificial Intelligence

## 🚀 Project Overview
The rise of IoT in modern smart homes has created an explosion of sensor data that holds immense potential for optimizing comfort, efficiency, and sustainability.
This project dives deep into IoT sensor data with machine learning and deep learning techniques to extract valuable insights.
By analyzing data from temperature, humidity, air quality, and energy usage sensors, we aim to design intelligent solutions that make homes smarter. 🌟

## 🗂 Repository Contents
### 📁 What’s Inside?
### 📄 Final Report

A comprehensive report detailing methods, models, experiments, and conclusions.
File: Final Technical Report
### 💻 Codebase

Python scripts and Jupyter Notebooks for data preprocessing, modeling, and evaluations.
Open in Colab:

### 📊 Tableau Dashboard

An interactive dashboard showcasing real-time and historical trends.
Access it here: Smart House Dashboard
### 📂 Organized Files

/code: Core scripts for preprocessing, modeling, and evaluations.
/data: Processed datasets for training and testing.
/results: Visualizations, logs, and output files.
requirements.txt: Dependencies for quick setup.
## 🎯 Project Goals
### 🌟 This project focuses on:

Building a custom CNN for classification and anomaly detection.
Implementing an LSTM for forecasting trends in temperature, air quality, and energy usage.
Establishing a baseline with ARIMA for univariate time series prediction.
Experiment with advanced techniques like the Temporal Fusion Transformer (TFT) for multivariate analysis.
Visualizing actionable insights through an interactive Tableau Dashboard.
## 📊 Dataset Overview
### 📂 Smart House Data Pack
Source: IoT sensors from smart homes.
Features:
Temperature, humidity, air quality (PM2.5), energy usage, and solar radiation.
Observations: Multivariate time series covering diverse conditions.
Challenges Addressed:
Handling noisy data and missing values.
Forecasting non-linear trends across variables.
🔗 Dataset Access: Smart House Data Pack (Replace with the actual link)

## 🛠️ How to Use
1️⃣ Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/smart-house-analysis.git
2️⃣ Install required dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the pipeline
Open and execute the main_notebook.ipynb in Jupyter or Google Colab.

4️⃣ Explore the Dashboard
Visualize insights using the provided Tableau link.

## 📋 Results and Key Insights
Model	Metric	Score	Best Use Case
CNN	Accuracy	95%	Air quality classification and anomaly detection.
LSTM	RMSE	0.8	Forecasting temperature and humidity trends.
ARIMA	MAE	1.2	Baseline univariate predictions for energy usage.
TFT (Optional)	RMSE	0.5	Multivariate forecasting for complex relationships.
Key Findings:
CNN excels at detecting anomalies in air quality and classifying environmental conditions.
LSTM outperformed ARIMA in capturing non-linear dependencies over time.
Advanced preprocessing like normalization and handling missing values boosted model accuracy.
## 📈 Dashboard
Access the interactive Tableau Dashboard here:
Smart House Dashboard

Features:

Real-time Monitoring: Visualize live sensor data.
Historical Trends: Explore temperature, humidity, and energy usage over time.
Anomaly Detection: Identify unusual conditions at a glance.
## 📅 Task List - Team Members
🧑‍💼 Outhai Xayavongsa (Ms. Thai) (Team Leader)
Coordinated team efforts and created task lists.
Developed and validated the LSTM and CNN models.
Designed preprocessing pipelines for noisy and multivariate data.
Documented all processes and consolidated results.
💻 Aaron Ramirez (Tech Lead)
Designed and implemented the ARIMA and Temporal Fusion Transformer (TFT) models.
Optimized model hyperparameters for efficient training and evaluation.
Integrated modeling results into Tableau visualizations.
🔧 Team Member 3 (Add Name)
Conducted exploratory data analysis (EDA) and selected key features.
Assisted in preprocessing and dashboard design.
## ✨ Future Enhancements
Integrate real-time IoT data streams for live forecasting.
Explore hybrid models like LSTM-CNN for combined spatial and temporal analysis.
Expand preprocessing to handle edge cases like extreme weather conditions.
📫 Contact
Feel free to reach out for collaborations or questions!

Outhai Xayavongsa (Ms. Thai): Profile
Aaron Ramirez: Profile
