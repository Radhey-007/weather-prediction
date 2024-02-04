# 🌧️ Next-Day Rain Prediction in Australia 🇦🇺

## 🎯 Project Overview
This project leverages machine learning to predict whether it will rain the next day in Australia. The prediction is based on a variety of weather observations collected from numerous locations across the country.

## 📊 Dataset
The dataset spans approximately 10 years and includes daily weather observations from various Australian locations. The target variable, `RainTomorrow`, indicates whether it rained the following day (Yes or No). A 'Yes' value signifies that the rainfall for that day was 1mm or more.

## 📚 Source & Acknowledgements
The weather observations were sourced from numerous weather stations, with daily observations available from the Bureau of Meteorology. Definitions were adapted from the Bureau of Meteorology.

## 🚀 Getting Started
1. **Clone the repo:** `git clone https://github.com/yourusername/your-repo-name.git`
2. **Install required packages:** `pip install -r requirements.txt`
3. **Run the Jupyter notebook:** `jupyter notebook your-notebook-name.ipynb`

## 📈 Results
In this project, we trained several machine learning models to predict next-day rain in Australia. Here's a summary of how each model performed:

| Model                 | Score    |
|-----------------------|----------|
| Logistic Regression   | 0.846865 |
| k-Nearest Neighbors   | 0.839887 |
| GaussianNB            | 0.662106 |
| SVM                   | 0.831088 |

The **Logistic Regression** model achieved the highest score of **0.846865**, making it the most effective model for this dataset.

!Model Performance

*Above is a bar chart illustrating the performance of each model.*

These results demonstrate the effectiveness of machine learning in predicting weather patterns. Future work could explore the use of more complex models or the inclusion of additional features to further improve prediction accuracy.

## 📜 License
This project is licensed under the terms of the MIT license.

## 📫 Contact
*Your Name* - *Your Email* - *Your LinkedIn*
