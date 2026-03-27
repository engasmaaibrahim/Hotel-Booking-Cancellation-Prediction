# Hotel Booking Cancellation Prediction

## Overview

This project is a **Machine Learning web application** that predicts whether a hotel booking will be **cancelled or not** based on user input.

It combines **data preprocessing, model training, and deployment** into a complete end-to-end solution using **Flask**.

---


## Model & Techniques

The model used:

* **K-Nearest Neighbors (KNN)**

### Data Processing:

* **SMOTE** → to handle class imbalance
* **PCA (Principal Component Analysis)** → for dimensionality reduction

---

## Features

* User-friendly web interface built with **Flask**
* Real-time prediction based on user input
* Handles imbalanced datasets effectively
* End-to-end ML pipeline (preprocessing → training → prediction)

---

## Dataset

* File: `Hotel Booking.csv`

### Includes features such as:

* Number of adults & children
* Number of weekend & week nights
* Meal plan type
* Room type
* Market segment
* Lead time
* Average price per room
* Special requests
* Reservation status date

---

## How to Run

### 1️- Clone the repository

```bash id="n9nqv2"
git clone https://github.com/engasmaaibrahim/Hotel-Booking-Cancellation-Prediction.git
cd Hotel-Booking-Cancellation-Prediction
```


### 2- Install dependencies

```bash id="ht2n5y"
pip install -r requirements.txt
```

---

### 3- Run the application

```bash id="2ys5w3"
python app.py
```


---


## Key Concepts

* Machine Learning Classification
* KNN Algorithm
* Data Preprocessing
* SMOTE (Imbalanced Data Handling)
* PCA (Dimensionality Reduction)
* Flask Web Deployment

---



## Author

**Asmaa Ibrahim**
AI & Machine Learning Engineer
