# Personalized Healthcare Recommendation System

## Overview

The Personalized Healthcare Recommendation System is an AI-powered healthcare application that predicts diseases, assesses health risks, and provides personalized recommendations based on patient health data.

The system integrates Angular, Spring Boot, FastAPI, Machine Learning, and MySQL to provide an end-to-end healthcare prediction platform.

---

## Features

### Patient Management

* Store patient health records
* Retrieve patient information
* Manage healthcare data using MySQL

### Disease Prediction

Predicts possible health conditions such as:

* Diabetes
* Hypertension
* Heart Disease
* Obesity
* Underweight
* Healthy

### Health Risk Assessment

Provides:

* Heart Disease Risk
* Diabetes Risk
* Overall Health Risk

### Personalized Recommendations

Generates:

* Medication Recommendations
* Diet Recommendations
* Exercise Recommendations

---

## Technology Stack

### Frontend

* Angular
* TypeScript
* HTML
* CSS

### Backend

* Spring Boot
* Java
* REST APIs
* Maven

### Machine Learning Service

* Python
* FastAPI
* Scikit-Learn
* Pandas
* NumPy
* Joblib

### Database

* MySQL

---

## System Architecture

User

↓

Angular Frontend

↓

Spring Boot Backend

↓

FastAPI ML Service

↓

Machine Learning Models

↓

Prediction Results

---

## Project Structure

PersonalizedHealthcareSystem

├── backend

├── frontend

│   └── healthcare-ui

├── ml-service

├── Project_Screenshots

└── README.md

---

## API Endpoints

### Patient APIs

#### Get All Patients

GET /patients

#### Add Patient

POST /patients

---

### Prediction API

POST /prediction

Example Request:

{
"age": 35,
"gender": "Male",
"bmi": 24.5
}

---

## Machine Learning Models

The project uses:

* diagnosis_model.pkl
* risk_model.pkl

The models predict:

* Disease Diagnosis
* Heart Disease Risk
* Diabetes Risk
* Overall Health Risk

---

## Workflow

1. User enters health details through Angular UI.
2. Spring Boot receives the request.
3. Backend forwards prediction data to FastAPI.
4. Machine Learning models generate predictions.
5. Results are returned to Spring Boot.
6. Angular displays diagnosis and recommendations.

---

## Future Enhancements

* JWT Authentication
* Doctor Dashboard
* Appointment Scheduling
* Medical Report Upload
* Real-Time Monitoring
* Cloud Deployment

---

## Author

Karthikadevi



