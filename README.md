# Smart Squad AI ⚽🤖

🏆 **1st Place Winner — IEEE Project Contest**  
📍 Bahria University Islamabad  
📅 2026

📘 Developed as a Semester Project for the **Machine learning** and **Introduction to Data Science** course at Bahria University.

---

# Overview

Smart Squad AI is a Machine Learning-powered football analytics and tactical management desktop application developed in Python.

The system predicts football player positions using a Soft Voting Ensemble Classifier trained on FIFA/SoFIFA datasets and provides tactical analysis tools including:

- Player Role Prediction
- Tactical Formation Visualization
- Radar Chart Comparison
- AI-Based Player Scouting
- Squad Depth Analysis
- Set-Piece Assignment
- Substitution Management

The project combines Machine Learning, Data Science, Visualization, and Tactical Football Intelligence into a single offline desktop application.

---

# Academic Context

This project was developed as part of the **Introduction to Data Science** semester course at Bahria University Islamabad.

The objective was to apply Machine Learning, data preprocessing, feature engineering, ensemble learning, and visualization techniques to solve a real-world football analytics and tactical management problem.

The project was later presented at the IEEE Project Contest and secured **1st Place**.

---

# Features

## ⚽ Player Analysis Hub

- Predicts the most suitable football position
- Displays top 3 possible roles with confidence percentages
- Tactical reasoning generation
- Radar chart visualization
- Top 3 scouting matches

## 🧠 Machine Learning Ensemble

The system uses a Soft Voting Ensemble of:

- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- Logistic Regression

## 📊 Tactical Board

- Automatic position assignment
- Multiple football formations
- Squad depth ranking
- Set-piece role recommendation
- Substitution simulation

## 📈 Data Visualization

- Interactive radar charts
- Formation visualization
- Tactical pitch rendering using Tkinter Canvas

---

# Machine Learning Details

## Dataset

The system uses FIFA/SoFIFA datasets:

- FIFA 18
- FIFA 19
- FIFA 20
- FIFA 22

Combined dataset size:
~27,000 player records

## Features Used

The model trains on 7 football attributes:

- Pace
- Shooting
- Passing
- Dribbling
- Defending
- Physic
- Goalkeeping

## Model Pipeline

1. Dataset Loading
2. Data Cleaning
3. Feature Extraction
4. StandardScaler Normalization
5. Train/Test Split
6. Soft Voting Ensemble Training
7. Prediction & Tactical Analysis

---

# Supported Formations

- 4-3-3
- 4-4-2
- 3-5-2
- 5-4-1
- 4-2-3-1

---

# Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Tkinter
- Machine Learning
- Ensemble Learning
- Data Science Pipeline
- Data Visualization

---

# Project Structure

```text
Smart-Squad-AI/
│
├── datasets/
│   ├── players_18.csv
│   ├── players_19.csv
│   ├── players_20.csv
│   ├── FIFA22_DATA.csv
│   └── NOORANI_FC.csv
│
├── screenshots/
│   ├── home_screen.png
│   ├── analysis_hub.png
│   ├── tactical_board.png
│   └── radar_chart.png
│
├── docs/
│   ├── Smart_Squad_AI_Report.pdf
│   ├── IEEE_Certificate.jpg
│   └── Presentation.pptx
│
├── models/
│   ├── RF_model.py
│   ├── SVM_model.py
│   ├── KNN_model.py
│   ├── LR_model.py
│   └── GradientBoost_model.py
│
├── ML_engine.py
├── MAIN.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# Installation

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Smart-Squad-AI.git
```

## 2. Open Project Folder

```bash
cd Smart-Squad-AI
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 4. Run Application

```bash
python MAIN.py
```

---

# Screenshots

## Analysis Hub

(Add screenshot here)

## Tactical Board

(Add screenshot here)

## Radar Chart

(Add screenshot here)

---

# Results

The Voting Ensemble achieved approximately:

| Configuration | Accuracy |
|---|---|
| All FIFA Datasets Combined | 88% – 93% |
| FIFA 22 Only | 85% – 90% |

---

# Educational Objectives

This project demonstrates practical implementation of:

- Supervised Machine Learning
- Ensemble Learning
- Feature Engineering
- Data Cleaning & Preprocessing
- Model Evaluation
- Data Visualization
- Football Tactical Analytics
- GUI Development using Tkinter

The system was designed to bridge theoretical Data Science concepts with a practical real-world application.

---

# Future Improvements

- Flask + React Web Deployment
- Live Football API Integration
- Opponent Tactical Analysis
- More Formation Support
- Positional Compatibility Checks
- Cross Validation
- Real-Time Match Analysis

---

# Authors

## Muhammad Hammad
## Saim Bin Shahid

---

# Achievement

🏆 1st Place — IEEE Project Contest  
📍 Bahria University Islamabad

---


# Acknowledgements

- FIFA / SoFIFA Dataset
- Scikit-learn
- Matplotlib
- Bahria University Islamabad
- IEEE Bahria Student Chapter

---
