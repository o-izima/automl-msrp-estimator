# AutoPricer: Predicting Car MSRP with Machine Learning

## 📍 Project Description

This project aims to predict the Manufacturer's Suggested Retail Price (MSRP) of vehicles using a variety of machine learning regression models. It demonstrates a practical application of ML to real-world datasets and is part of a professional data science portfolio by Obinna, PhD (EEE, ML, Data Science & Network Engineering).

## 📊 Dataset

- Source: [Kaggle - Car Dataset](https://www.kaggle.com/datasets/CooperUnion/cardataset)
- Features: Make, Model, Engine, Transmission, Drive Type, MPG, etc.
- Target: MSRP

## 🧠 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

## ⚙️ Tech Stack

- Python 3.8+
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter/VS Code

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/autopricer-msrp-prediction.git
   cd autopricer-msrp-prediction

2. Install dependencies
   ```bash
   pip install -r requirements.txt

3. Run the script:
   ```bash
   python car_msrp_prediction.py

Note: Download the dataset from Kaggle and save it as data.csv in the root directory.

📈 Results
The models are evaluated using R² score and Mean Squared Error. The best-performing model is plotted against actual MSRP values.

🧑‍💼 About the Author
Obinna — PhD in Electrical & Electronic Engineering with research in Machine Learning, Data Science, and Network Engineering. This project forms part of a broader data science dashboard and analytics portfolio.

📂 Folder Structure
kotlin
Copy
Edit
autopricer-msrp-prediction/
├── car_msrp_prediction.py
├── data.csv
├── requirements.txt
└── README.md
📬 Contact
For inquiries, collaborations, or hiring, feel free to reach out via LinkedIn or email.
