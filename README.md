# Task_3-full-datascience-project
End-to-end Iris Flower Prediction API using Python, Flask, and ngrok. Includes data preprocessing, model training, and a live API for predicting Iris species from flower measurements. Tested in Colab and Postman.”
# Task 3 - Iris Flower Prediction API

## Overview
This project is an **end-to-end Iris Flower Prediction API** using Python, Flask, and ngrok.  
The API predicts the species of an Iris flower based on four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The project demonstrates a full data science workflow:
1. Data loading and preprocessing
2. Model training and saving
3. API deployment using Flask
4. Live testing via ngrok URL

---

## Files in Repository

| File | Description |
|------|-------------|
| `iris_clean.csv` | Cleaned Iris dataset used for training |
| `iris_model.pkl` | Trained Random Forest model |
| `Task3_Iris_API.ipynb` | Colab notebook with full workflow, API code, and test examples |

---

## How to Run

### 1. Open the Notebook
Open `Task3_Iris_API.ipynb` in **Google Colab**.

### 2. Install Dependencies
Run the following command in a Colab cell:

```python
!pip install pandas scikit-learn flask pyngrok
Load Dataset and Model

The notebook automatically loads iris_clean.csv and the trained model iris_model.pkl.

4. Start Flask APIRun the Flask API cell in Colab. The notebook will display a ngrok public URL
