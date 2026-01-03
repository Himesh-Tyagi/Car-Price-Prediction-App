# 🚗 Car Price Prediction Using Machine Learning

## 📌 Project Overview
This project demonstrates the application of machine learning to predict the selling price of a car based on features such as year, mileage, engine specs, and more. It includes data exploration, model training, evaluation, and a simple web application to interact with the trained model.

---

## 📁 Repository Structure

```
Car-Price-Prediction/
│
├── Internship_Project.ipynb   # Main notebook with data analysis, model building & exploration
├── carapp.py                 # Python script for running the prediction web app
├── car data.csv              # Dataset used for training and testing
├── car.pkl                   # Saved machine learning model
├── requirements.txt          # Python libraries required
└── README.md                 # Project documentation
```

---

## 📊 Dataset Description
The dataset (`car data.csv`) contains car attributes such as:
- Brand / Make
- Model year
- Mileage / kilometers driven
- Fuel type
- Transmission type
- Engine size
- Price (target variable)

These features are used to train a regression model to estimate car prices.

---

## 🧠 Machine Learning Workflow
1. Load and explore the dataset  
2. Clean and preprocess the data  
3. Perform feature engineering  
4. Train regression models  
5. Evaluate model performance  
6. Serialize the best model (`car.pkl`)  
7. Build a web app for real-time price prediction

---

## 🛠️ Technologies & Libraries Used
- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Jupyter Notebook**
- **Flask / Streamlit (for web app)**
- **joblib / pickle**

---

## 📈 Key Outcomes
- Built a regression model to predict car prices
- Used exploratory data analysis to identify key price drivers
- Deployed a simple app to make predictions from user input

---

## 🔮 Future Enhancements
- Add more advanced models like Random Forest, XGBoost or Gradient Boosting  
- Perform Hyperparameter Tuning for better accuracy  
- Create an interactive UI with Streamlit  
- Deploy the app on cloud platforms like Heroku or Render

---

## 👨‍💻 Author
**Himesh Tyagi**  

⭐ If this project helped you, feel free to star the repo! ⭐
