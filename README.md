## Food_Adulteration_Health_Risk_using_ML

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)

# Project Overview

This project aims to predict the health risk due to food adulteration based
on adulteration type and product using a Gradient Boosting model. The project
includes a Streamlit web application that allows users to input product name,
adulteration type, chemicals and get predictions.

# Project Details

The dataset used for this project includes various products, adulterants and
detection methods. It also contains information about health risk, such as:

1. product_name
2. brand
3. category
4. adulterant
5. detection_method
6. severity
7. health_risk

# Model

A Gradient Boosting Model was trained on the basis of the features listed
above, excluding the 'health_risk' column.

# Streamlit App

The Streamlit app provides an interactive interface to input product name,
brand, category, adulterant, detection method, severity and visualize the
predictions. The app includes:

1. A form to input product name, brand, category, adulterant, detection
   method, severity
2. A "Predict" button to generate prediction

# Installation

## Prerequisites

Ensure you have the following installed:
- Python 3.12 or higher
- Git

## Steps

1. Clone the repository
```bash
git clone https://github.com/Nehu2021/Food_Adulteration_Health_Risk_using_ML.git
```

2. Navigate to the project directory
```bash
cd Food_Adulteration
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

# Run the predictor

This model is pre-trained so simply run the predictor:
```bash
streamlit run app.py
```

# If you want to train the model on your own

1. Install Jupyter Notebook:
```bash
pip install notebook
```

2. Open the Notebook: navigate to the directory where the `.ipynb` file
   is located using your command line or terminal.

3. Start Jupyter Notebook:
```bash
jupyter notebook
```

---

## 👩‍💻 Author
**Neha Khatri** — [GitHub](https://github.com/Nehu2021) · [LinkedIn](https://www.linkedin.com/in/neha-khatri-1a5917335/)
