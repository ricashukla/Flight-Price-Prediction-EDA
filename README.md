# Flight Price Prediction - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Flight Price Prediction** dataset. The objective is to analyze key factors affecting flight ticket prices and identify trends that impact airfare.

## 📂 Dataset Information
- **Dataset Name**: Flight Price Prediction Dataset
- **Number of Entries**: 10,683
- **Features**:
  - Airline
  - Date_of_Journey
  - Source
  - Destination
  - Route
  - Dep_Time
  - Arrival_Time
  - Duration
  - Total_Stops
  - Additional_Info
  - Price (Target Variable)

## 🛠️ Key Steps in Analysis
1. **Data Cleaning**
   - Handled missing values in the `Route` and `Total_Stops` columns
   - Converted categorical features into numerical representations
2. **Descriptive Statistics**
   - Summary statistics of numerical and categorical features
   - Distribution of flight prices across airlines, routes, and stops
3. **Feature Analysis**
   - Impact of journey date, time of departure, and total stops on price
   - Correlation between duration and ticket cost
4. **Correlation Analysis**
   - Higher prices for premium airlines
   - Non-stop flights tend to have higher ticket prices
5. **Visualization Techniques Used**
   - Histograms, boxplots, scatter plots, bar charts, and heatmaps

## 📊 Key Observations & Findings
- **IndiGo and Jet Airways have the highest number of flights**, whereas **Vistara and Air India** have fewer flights.
- **Non-stop flights are generally more expensive** than flights with layovers.
- **Prices fluctuate significantly based on departure time and journey date.**
- **Duration and price have a moderate correlation**, indicating longer flights tend to cost more.

## 💻 Technologies Used
- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Seaborn 🎨
- Jupyter Notebook 📒

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/ricashukla/Flight-Price-EDA.git
   cd Flight-Price-EDA
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run `Flight price pred EDA.ipynb`

## 🔥 Future Work
- Train a Machine Learning model to predict flight prices based on given features.
- Perform time-series analysis on historical flight pricing trends.
- Build an interactive visualization dashboard for real-time flight price analysis.

---
✨ **If you find this project useful, give it a ⭐ on GitHub!**
