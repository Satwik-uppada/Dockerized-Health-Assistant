# Dockerized-Health-Assistant
# Health Assistant: Disease Prediction with Machine Learning (Streamlit Web App)



## Introduction

The Health Assistant is a user-friendly web application designed to leverage machine learning for disease prediction, empowering individuals to take a more active role in their health. It offers functionalities for predicting Diabetes, Heart Disease, and Parkinson's disease based on user-provided information.

## Key Features

* **Disease Prediction Models:** Employs well-established machine learning models (SVM with linear kernel and Logistic Regression) for accurate predictions.
* **User-Friendly Interface:** Streamlit facilitates a seamless and interactive web application interface, making disease prediction accessible and convenient.
* **Proactive Health Management:** Encourages early detection of potential risks and promotes preventative measures through awareness.

## Installation 
**Prerequisites:**

* Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
currently i'm using (python 3.12.0)
* pip (usually comes bundled with Python)
* Streamlit

**Installation:**

1. Clone this repository:

   ```bash
   git clone https://github.com/Satwik-uppada/Dockerized-Health-Assistant.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

2. Access the web application in your browser at http://localhost:8501 by default (the port might vary).

## Machine Learning Models

* **Diabetes Prediction:** Support Vector Machine (SVM) with a linear kernel
* **Heart Disease Prediction:** Logistic Regression
* **Parkinson's Disease Prediction:** Support Vector Machine (SVM) with a linear kernel


## Streamlit Web Application

Streamlit enables the creation of a user-centric web interface that facilitates easy interaction with the system. The application provides:

* **Sidebar Menu:** Users can navigate between different disease prediction options.
* **User Input Forms:** Users can enter their data points through clear and labeled forms.
* **Prediction Button:** Initiates the prediction process based on user-provided data.
* **Result Display:** Presents the predicted outcome in a concise and informative manner.

## Dockerization 

The project can be Dockerized for easier deployment and consistent environments. Refer to the `Dockerfile` for details.

If you are aware of docker you can directly pull the image from docker hub by running the below command.

1. Pull image from docker hub
```bash
docker pull sathvi782/docker_project:disease_predictor
```

3. Check the images list
```bash docker images ```

5. Run the container using this image with port 8501
```bash
docker run -itd -p 8501:8501 disease_predictor

```

## Future Work

* **Expanding Disease Coverage:** Incorporate additional diseases for a more comprehensive assessment.
* **Model Improvement:** Explore more complex models or feature engineering techniques to enhance prediction accuracy.


## Contributions

I welcome contributions! 

