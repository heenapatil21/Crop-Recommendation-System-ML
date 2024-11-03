**🌾 Crop Recommendation System**

This project uses machine learning to predict the best crop to grow based on soil and environmental factors like nitrogen, phosphorus, potassium levels, temperature, humidity, pH, and rainfall. It aims to assist farmers 🌱 in making informed crop selection decisions, boosting productivity 📈 and sustainability 🌍.

**📝 Problem Statement**

In agriculture, crop selection plays a crucial role in maximizing yield and maintaining sustainable farming practices. Farmers often face challenges in choosing the best-suited crops for their land due to variability in soil nutrients, climate, and rainfall patterns. This project addresses the following problems:

**1.Optimizing Crop Selection for Diverse Agricultural Regions 🌍**
Providing farmers with accurate crop recommendations based on soil and climate data, which can help improve productivity and reduce crop failure risks.

**2.Data-Driven Agriculture for Enhanced Yield 🌱**
Leveraging machine learning to enable farmers to make informed crop choices, considering factors like soil nutrients, temperature, humidity, and rainfall.

**3.Reducing Crop Failures through Predictive Recommendations 📉**
Offering a predictive approach to crop selection to minimize the risk of planting incompatible crops, leading to more stable and reliable yields.

**4.Improving Resource Efficiency in Agriculture 💧🌡️**
Assisting farmers in making resource-efficient crop decisions by matching crop needs with soil nutrient profiles and climate conditions, promoting sustainable resource usage.

**📂 Dataset**

The dataset contains 2200 entries with these features:

* 🧪 N: Nitrogen content in soil
* 🧪 P: Phosphorus content in soil
* 🧪 K: Potassium content in soil
* 🌡️ Temperature: in degrees Celsius
* 💧 Humidity: Relative humidity percentage
* 🌱 pH: Soil pH level
* ☔ Rainfall: in mm
* 🏷️ Label: Crop type (target variable)
  
**📦 Requirements**

Install the necessary libraries using:

* 📊 pandas
* 🧮 numpy
* 📉 matplotlib
* 📊 seaborn
* 🧠 scikit-learn

**🔍 Data Exploration**
  
Data visualizations help us explore the distribution of features and crop types:

* 📈 Histogram of Nitrogen content in soil
* 🌡️ Scatter plot of Temperature vs. Humidity
* 📊 Box plot of pH levels for each crop
* 🔥 Heatmap of feature correlations
* 🤖 Model Training
  
**Several classification models were trained to predict crop types:**

* 🌳 Decision Tree
* 📏 Logistic Regression
* 🐦 Gaussian Naive Bayes
* 🛠️ Support Vector Machine
* 🌲 Random Forest
* 📊 Model Accuracy
  
**Model	Accuracy 🏆**

1. 🌳 Decision Tree	 =  95.9%
2. 📏 Logistic Regression = 	95.2%
3. 🐦 Gaussian Naive Bayes = 	99.1%
4. 🛠️ Support Vector Machine = 	97.7%
5. 🌲 Random Forest	 = 97.7%

**✅ Conclusion**
 
The **Gaussian Naive Bayes model achieved the highest accuracy**, making it a top choice for crop recommendation. For future improvements, ensemble techniques like Bagging and Boosting could be considered.

