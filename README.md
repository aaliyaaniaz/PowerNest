 #  PowerNest – User Behavior-Based Energy Prediction System

PowerNest is a Machine Learning-powered web application that predicts household energy consumption based on user behavior and historical energy usage patterns. Built with **Streamlit**, the application provides an interactive interface for users to input energy-related parameters and receive accurate consumption predictions in real time.

---

## Features

-  Predicts household energy consumption using Machine Learning.
-  Interactive web interface built with Streamlit.
-  Performs data preprocessing and feature engineering.
-  Uses a trained Machine Learning model for prediction.
-  Displays prediction results through a simple and user-friendly interface.
-  Helps users understand and optimize their energy usage.

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

##  Project Workflow

1. Load and preprocess the energy consumption dataset.
2. Perform exploratory data analysis (EDA).
3. Train the Machine Learning model.
4. Save the trained model.
5. Launch the Streamlit application.
6. Enter energy-related input values through the web interface.
7. Generate and display the predicted energy consumption.

---

##  Machine Learning Model

The project uses the **Random Forest Regressor** to predict energy consumption. The model learns patterns from historical energy usage data and estimates future energy consumption based on user inputs.

---

##  Model Performance

The model was evaluated using standard regression metrics including:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The trained model achieved approximately **91% prediction accuracy**, providing reliable energy consumption predictions.

---

## Project Structure

```
PowerNest/
│── data/
│── models/
│── app.py
│── train_model.py
│── requirements.txt
│── README.md
```

##  Future Enhancements

- Real-time energy monitoring
- Smart energy-saving recommendations
- Interactive analytics dashboard
- IoT sensor integration
- Personalized energy usage insights

---

