# Human Development Index (HDI) Prediction System

A Machine Learning-based web application that predicts the Human Development Index (HDI) category of a country based on various socio-economic indicators. The application uses a trained Random Forest Classifier integrated with the Flask web framework to provide instant HDI predictions through a simple and responsive web interface.

---

# Project Links

| Resource              | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------  |
| **Live Demo**         | https://drive.google.com/file/d/1grtu0XB9wCJRV0PG_IvAf8nrBp5TeTVz/view?usp=drivesdk   |
| **GitHub Repository** | https://github.com/himeshsaiharinaghpolisetti-lab/HDI-Predictor                       |

---

# Project Overview

The Human Development Index (HDI) is a statistical measure used to assess the overall development of a country based on key indicators such as life expectancy, education, and income.

This project leverages Machine Learning to classify a country's Human Development level using socio-economic data. Users can enter the required indicator values through a web interface, and the application predicts the corresponding HDI category in real time.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, feature engineering, model training, evaluation, model serialization, deployment, and user interaction through a Flask web application.

---

# Features

* User-friendly prediction interface
* Real-time Human Development Index prediction
* Machine Learning-based classification model
* Automatic data preprocessing
* Responsive web interface
* Random Forest Classifier
* Flask backend integration
* Cloud deployment support using Render

---

# Machine Learning

The project uses the following Machine Learning algorithm:

* Random Forest Classifier

The dataset was preprocessed by handling missing values, converting categorical variables into numerical values using Label Encoding, and cleaning numerical features before training the model.

The trained model was evaluated using prediction accuracy and then serialized using Joblib for deployment.

---

# Technology Stack

| Layer                | Technologies                           |
| -------------------- | -------------------------------------- |
| Programming Language | Python                                 |
| Web Framework        | Flask                                  |
| Machine Learning     | Random Forest Classifier, Scikit-learn |
| Data Processing      | Pandas, NumPy                          |
| Data Visualization   | Matplotlib, Seaborn                    |
| Model Storage        | Joblib                                 |
| Frontend             | HTML5, CSS3, Jinja2                    |
| Development Tools    | Jupyter Notebook, VS Code              |
| Version Control      | Git, GitHub                            |
| Deployment           | Render                                 |

---

# Project Structure

```text
HDI-Prediction-System/
│
├── app.py
├── model.py
├── model.pkl
├── HDI.csv
├── requirements.txt
├── runtime.txt
├── README.md
│
├── templates/
│   ├── home.html
│   ├── indexnew.html
│   └── resultnew.html
│
├── static/
│   ├── style.css
│   ├── script.js
│   └── images/
│
└── notebook.ipynb
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/HDI-Prediction-System.git
```

## Navigate to the Project Directory

```bash
cd HDI-Prediction-System
```

## Create a Virtual Environment

```bash
python -m venv venv
```

## Activate the Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
python app.py
```

## Open in Browser

```text
http://127.0.0.1:5000
```

---

# Input Features

The prediction model uses socio-economic indicators from the dataset, including:

1. Country
2. Life Expectancy at Birth
3. Expected Years of Schooling
4. Mean Years of Schooling
5. Gross National Income (GNI) per Capita
6. Additional development indicators available in the dataset

---

# Prediction Output

The application predicts one of the following Human Development categories:

* Low Human Development
* Medium Human Development
* High Human Development
* Very High Human Development

---

# Dataset

The project uses the **Human Development Index (HDI)** dataset containing socio-economic indicators for multiple countries. The dataset is preprocessed by handling missing values, converting categorical variables into numerical representations, and cleaning numerical features before training the Machine Learning model.

---

# Future Improvements

* Compare multiple Machine Learning algorithms
* Hyperparameter tuning for improved accuracy
* Interactive data visualization dashboard
* Country-wise historical HDI trend analysis
* REST API integration
* Database connectivity
* User authentication system
* Docker containerization
* Deployment using CI/CD pipelines

---

# Deployment

The application can be deployed on **Render** for public access.

**Live Application**

*Add your Render deployment link here.*

---

# License

This project was developed for educational and academic purposes.
