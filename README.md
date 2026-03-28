# AI-ML-project
# 🩺 Healthcare: Stay Healthy, Live Better

**Healthcare** is an interactive **AI/ML-based wellness dashboard** designed to help users understand their health, predict potential risks, and take practical steps toward a healthier lifestyle.

It uses inputs such as **age, weight, height, lifestyle habits, exercise, diet, and sleep patterns** to generate:

- **Overall Health Score** (0–100)
- **Lungs & Liver Risk Assessment**
- **Life Expectancy Prediction**
- **Frequency-Based Habit Impact** (Daily / Weekly / Occasionally)
- **Personalized Health Recommendations**

Healthcare is built to be **simple, engaging, and visually interactive**, making health awareness more informative and user-friendly. 🏋️‍♂️🍎💤

---

## 🌟 Features

- Interactive sliders for entering **biometric and lifestyle details**
- **Health Score Prediction** using a **Random Forest ML model**
- **Frequency-based analysis** to show the impact of habits performed daily, weekly, or occasionally
- **Risk alerts** for lungs and liver health
- **Life expectancy estimation**
- **Personalized wellness recommendations**
- Health **visualizations, insights, and motivational notes**

---

## 🖥️ How It Works

### 1. Data Simulation
- A **synthetic dataset of 500 users** is generated using attributes such as:
  - age
  - weight
  - height
  - smoking
  - alcohol consumption
  - exercise
  - sleep
  - calorie intake
  - caffeine intake
- An **overall health score** is calculated using weighted lifestyle, BMI, and age-related factors.

### 2. Machine Learning Model
- A **Random Forest Regressor** is used to predict the **overall health score** based on user input.
- Input features are scaled using **MinMaxScaler** to improve consistency and model performance.

### 3. Prediction & Frequency Analysis
- The system calculates:
  - **Health Score**
  - **Lungs Risk**
  - **Liver Risk**
  - **Life Expectancy**
- It also adjusts predictions based on **habit frequency**:
  - **Daily**
  - **Weekly**
  - **Occasionally**

### 4. Interactive Dashboard
- The dashboard is built using **ipywidgets** and **matplotlib** for real-time interaction and visualization.
- Users can explore their health through:
  - **sliders**
  - **graphs**
  - **tables**
  - **insight cards**
  - **motivational messages**

### 5. Personalized Recommendations
Based on the user’s input, Healthcare provides suggestions related to:

- 🚭 **Smoking**
- 🍷 **Alcohol Consumption**
- 💤 **Sleep Quality**
- 🚶 **Exercise Habits**
- ⚖️ **BMI / Weight Balance**
- 🍽️ **Diet & Calorie Intake**

---

## 🎯 Objective

The goal of Healthcare is to make **health tracking more accessible, interactive, and meaningful** by combining **machine learning predictions** with **easy-to-understand wellness insights**.

It is not intended to replace professional medical advice, but rather to serve as a **wellness awareness and lifestyle guidance tool**.

---

## 💡 Why Healthcare?

Healthcare stands out because it does more than just track numbers — it helps users **see the impact of their habits**, understand possible risks, and stay motivated to improve their health in a more engaging way.
