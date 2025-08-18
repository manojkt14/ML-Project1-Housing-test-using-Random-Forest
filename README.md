
# 🏡 ML Project 1 - Housing Price Prediction (Random Forest)

This project predicts **housing prices** using the **Random Forest Regression** model.  
It involves data preprocessing, feature engineering, model training, evaluation, and testing on sample datasets.

---

## 🚀 Features
- Data cleaning and preprocessing (handling missing values, outliers, encoding, scaling)
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering for better model accuracy
- Model training using **Random Forest Regressor**
- Model evaluation with metrics (RMSE, MAE, R²)
- Prediction on test dataset

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Model:** Random Forest Regressor
- **Environment:** Jupyter Notebook / Python Script

---

## 📂 Project Structure
```bash
ML-Project1-Housing-test-using-Random-Forest/
│── data/                # Training and test datasets
│── notebooks/           # Jupyter notebooks with step-by-step process
│── src/                 # Python scripts (data prep, model, evaluation)
│── models/              # Saved trained models (pickle files)
│── reports/             # EDA reports, charts, model results
│── README.md            # Project documentation
│── requirements.txt     # Python dependencies
````

---

## ⚡ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/manojkt14/ML-Project1-Housing-test-using-Random-Forest.git
cd ML-Project1-Housing-test-using-Random-Forest
pip install -r requirements.txt
```

---

## ▶️ Usage (Google Colab)
1. Open the project notebook in Google Colab.  
  
     ```
     https://colab.research.google.com/drive/1_20DLhZnsY8BhueLQL5y6XyM7IWiWLFF#scrollTo=12fd9f0a
     ```
2. Make sure the dataset is available:  
   - Upload manually to Colab `data/` folder, **OR**  
   - Mount Google Drive and place the dataset there.  
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
3. Install required dependencies (if not already available in Colab):  
   ```python
   !pip install -r requirements.txt

---

## 📊 Model Performance

* **R² Score:** 0.78
* **RMSE:** 57917.70
* **MAE:** 58111.01

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repo
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m 'Added feature'`)
4. Push to branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file.

---

## 👤 Author

* **Manoj**
  [GitHub](https://github.com/manojkt14) | [LinkedIn](https://www.linkedin.com/in/manoj-kumar-67983918a/)

```

