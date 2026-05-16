# AI-powered-smart-agriculture-platform-built-using-Flask
It is an AI-powered agriculture platform built with Flask. It provides crop prediction, weather-based recommendations, demand forecasting, and a farmer marketplace with WhatsApp contact integration to help farmers make smarter farming and selling decisions.

# Project Structure

```text
smart-farmlink/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── data/
│   ├── app.db
│   ├── india_major_district_rainfall.csv
│   ├── crop_dataset_final.csv
│   ├── crop_demand_price_5years.csv
│   └── marketplace.csv
│
├── models/
│   ├── crop_model.pkl
│   └── crop_labels.pkl
│
├── ml/
│   ├── forecast_demand.py
│   └── explain_model.py
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   └── images/
│
├── templates/
│   ├── dashboard.html
│   ├── login.html
│   ├── register.html
│   ├── predict.html
│   ├── result.html
│   ├── market.html
│   ├── add_listing.html
│   ├── edit_listing.html
│   └── forecast.html
│
└── screenshots/
    ├── dashboard.png
    ├── marketplace.png
    └── prediction.png
```

---

# Files You Should Remove Before Uploading

Delete these unnecessary files before uploading to GitHub:

```text
app.db-journal
New Text Document.txt
marketpplace.csv
```

Also remove duplicate or unused datasets if not required.

---

# Recommended .gitignore

Create a file named:

```text
.gitignore
```

Add this:

```gitignore
__pycache__/
*.pyc
*.pyo
*.pyd
.env
venv/
.env/
.idea/
.vscode/
*.db-journal
```

---

# Recommended requirements.txt

Create:

```text
requirements.txt
```

Add:

```txt
Flask
pandas
numpy
scikit-learn
joblib
requests
matplotlib
```

---

# Recommended README.md

````markdown
# Smart FarmLink 🌾

AI-powered agriculture platform built using Flask and Machine Learning.

## Features

- Crop Recommendation
- Weather-based Prediction
- Demand Forecasting
- Farmer Marketplace
- WhatsApp Contact Integration

## Technologies Used

- Python
- Flask
- Machine Learning
- SQLite
- HTML/CSS
- JavaScript

## Run Project

```bash
pip install -r requirements.txt
python app.py
````

## Screenshots

Add screenshots inside screenshots/ folder.

````

---

# GitHub Upload Steps

## 1. Open Terminal

```bash
cd smart-farmlink
````

## 2. Initialize Git

```bash
git init
```

## 3. Add Files

```bash
git add .
```

## 4. Commit

```bash
git commit -m "Initial commit"
```

## 5. Connect GitHub Repo

```bash
git remote add origin YOUR_GITHUB_REPO_LINK
```

## 6. Push Code

```bash
git push -u origin main
```

---

# Final Tips

* Keep dataset files inside `data/`
* Keep ML files inside `ml/`
* Keep all HTML files inside `templates/`
* Keep CSS/JS/images inside `static/`
* Add screenshots for better GitHub presentation
* Rename project folder from:

```text
smart farmlink
```

to:

```text
smart-farmlink
```

for professional GitHub formatting.


## Features

- Crop Recommendation
- Weather-based Prediction
- Demand Forecasting
- Farmer Marketplace
- WhatsApp Contact Integration

## Technologies Used

- Python
- Flask
- Machine Learning
- SQLite
- HTML/CSS
- JavaScript

## Run Project

```bash
pip install -r requirements.txt
python app.py
