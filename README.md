# Railway Delays Analysis: Holidays and Weather Impact

## 1. Overview

This project explores railway delay patterns with a focus on two main factors: major holidays and weather conditions.  
The dataset covers train operations in China’s high-speed railway network from October 2019 to January 2020, including detailed delay information, weather records, and holiday indicators.  

The analysis zooms in on two representative months — October and December — to compare how different conditions affected train punctuality. While holidays had only a minor influence on delays, weather conditions played a much stronger role. In particular, rainy and snowy weather in December led to significantly higher delays compared to October.  

This project shows how large railway datasets can help reveal patterns in train delays. Besides the main results, the analysis points to future work, such as looking at data from more years to see if certain types of weather or holidays cause delays in a regular, repeating way. 

---

## 2. Dataset

### 2.1 Source
The dataset was taken from Figshare:  
[A high-speed railway network dataset from train operation records and weather data](https://figshare.com/articles/dataset/A_high-speed_railway_network_dataset_from_train_operation_records_and_weather_data/15087882/4?file=30853027)

### 2.2 Dataset Structure
The dataset contains train operation data in different directions from October 8, 2019 to January 27, 2020, including train delay records, weather conditions, and major holidays.  

Columns:  
- date: Date of the train ride  
- arrival_delay: Delay in minutes upon arrival at the destination  
- departure_delay: Delay in minutes upon departure  
- major_holiday: Boolean indicating whether the train ride occurred on a major holiday  

---

## 3. Analysis

### 3.1 Tools Used
- Python (pandas, numpy)  
- Jupyter Notebook  

### 3.2 Structure of the Analysis
- Import libraries and load dataset  
- Data preprocessing and preparation  
- Analysis of train rides on holidays vs. non-holidays  
- Impact of weather conditions on delays  
- Key findings and future research  

### 3.3 Key Findings
- Holidays overall had only a minor effect on railway delays  
- Weather conditions had a much stronger effect on railway delays  

---

## 4. Usage / Installation

1. Clone the repository: https://github.com/lilalaser/Python-Data-Analysis-Railway-Delays
2. Install required Python libraries (pandas, numpy)
3. Run the Jupyter Notebook to reproduce the analysis

---

## 5. Contact

For questions or contributions, please contact me through GitHub.
Thank you.
