# 🏥 Medical Insurance Cost Prediction

A Machine Learning web application that predicts a person's medical insurance charges based on personal and health-related information. The model is trained on historical insurance data and deployed using **Streamlit**.

---

## 📌 Project Overview

Medical insurance costs vary depending on several factors such as age, BMI, smoking habits, region, and number of children. This project uses Machine Learning to estimate insurance charges accurately.

The application allows users to enter their details through an interactive web interface and instantly predicts the estimated insurance premium.

---

## ✨ Features

- Predict medical insurance charges
- Interactive Streamlit web interface
- Fast and accurate predictions
- User-friendly design
- Trained Machine Learning model
- Real-time prediction

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Pickle

---

## 📂 Project Structure

```
Medical-Insurance/
│
├── App.py                     # Streamlit application
├── insurance.csv              # Dataset
├── MIPML.pkl                  # Trained machine learning model
├── health.ipynb               # Data preprocessing & model training
├── costomer_segmentation.ipynb
├── requirements.txt           # Dependencies
├── retrain_model.py.save
└── README.md
```

---

## 📊 Dataset

The dataset contains information about:

- Age
- Gender
- BMI
- Number of Children
- Smoking Status
- Region
- Insurance Charges (Target Variable)

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/khushibagari14/Medical-Insurance.git
```

### Navigate to the project

```bash
cd Medical-Insurance
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run App.py
```

---

## 🖥️ Application Workflow

1. User enters personal information.
2. Data is preprocessed.
3. The trained ML model predicts insurance charges.
4. Estimated medical insurance cost is displayed.

---

## 📈 Machine Learning Workflow

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Model Serialization using Pickle
- Streamlit Deployment

---

## 📸 Sample Input

| Feature | Example |
|----------|---------|
| Age | 28 |
| Gender | Female |
| BMI | 26.5 |
| Children | 2 |
| Smoker | No |
| Region | Southeast |

---

## 🎯 Sample Output

```
Estimated Medical Insurance Cost

$5,840.27
```

---

## 📦 Requirements

```
streamlit
pandas
numpy
scikit-learn
pickle
```

Install all packages using:

```bash
pip install -r requirements.txt
```

---
## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 👩‍💻 Author

**Khushi Bagari**

- GitHub: https://github.com/khushibagari14
- LinkedIn: https://www.linkedin.com/in/khushibagari

---

## ⭐ Support

If you found this project useful, don't forget to **star ⭐ the repository**.
