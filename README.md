### DSA_210
**INTRODUCTION TO DATA SCIENCE** 
/ Nur Deren Sakin 29078
https://colab.research.google.com/drive/1QnahKF-GxMMNd7jTOo8WqFQ3fD24JQg8?authuser=2

# **Screen Time Data Analysis Project**

### **Motivation :**
This project aims to analyze daily screen time data to gain insights into personal application usage patterns, especially during exam days. It seeks to understand how application usage changes in different contexts and predict future storage and time needs based on current habits. This project is both a personal exploration and a step towards improving productivity.


### **Data Source:**
The data is collected directly from the screen time feature available on a smartphone. It includes:
  * Daily usage duration of each application.
  * Time of day for usage (hourly breakdown).
  * Specific data for exam days versus regular days.

    
### **Implementation and Tools:**
The analysis and code will be written in Google Colab.
Using Python for data analysis and visualization.
Applying machine learning models, for advanced predictions.
Libraries:
* Pandas and NumPy for data manipulation
* Matplotlib and Seaborn for data visualization
* Scikit-learn for predictive modeling

### **Data Analysis:** 
Retrieve screen time data from the phone, ensuring minute-level granularity.

* Exploratory Data Analysis (EDA):
  Visualize daily usage patterns.
  Identify which applications are used more/less during exam days.
  Analyze total daily screen time variations.

* Stages of the analysis:
  * Data extraction and formatting.
  * Visualizing application usage patterns across different days.
  * Analyzing differences in application usage duration on exam days versus regular days.
  * Calculating the daily number of photos and videos taken based on time spent in the camera app and estimating the required storage space.
  * Estimating the time needed to complete a course playlist on YouTube.


### **Predictive Insights:**
* Calculate the number of photos taken based on the time spent in the camera app.
* Estimate future storage requirements for photos.
* Predict the completion time for a planned TV series based on current viewing habits.
* Forecast the duration needed to complete a course playlist on YouTube, considering current daily usage trends.

Through this project, I aim to discover significant differences in how I use applications during exam days versus regular days. For instance, I plan to analyze if I spend more time on productivity apps and less on entertainment. Additionally, I will estimate photo storage needs and predict how long it will take to complete a course playlist on YouTube based on my daily habits.

### **Limitations and Future Work:**
* Limitations:

The analysis is limited to my personal screen time data and may not be generalized to others.
Predictive accuracy depends on the completeness and reliability of the data.
* Future Work:
  
Automate the data collection process for real-time analysis.
Expand the scope to include other behavioral data such as physical activity and sleep tracking.
Build a dashboard to visualize the insights interactively.
