<h1 align="center">🩺 Diabetes Prediction Web App</h1>
<p align="center">
  A machine learning–powered web app built using Django to predict diabetes risk based on user health parameters.
</p>

---

## 📊 Project Overview

This web-based application leverages a pre-trained machine learning model to assess the likelihood of diabetes in individuals based on medical input data. The app provides instant predictions and user-friendly results via a clean Django-powered interface.

---

## 💡 Features

- 📈 Trained using **Scikit-learn** with high accuracy
- 🌐 Web interface built with **Django**
- 📄 Input fields include health metrics like glucose, BMI, age, etc.
- 🧠 Prediction logic served via a trained model integrated in backend
- 🎨 Styled frontend using Bootstrap & HTML
- 📁 Includes interactive Jupyter Notebook for model training & evaluation

---

## 🛠️ Tech Stack

| Layer        | Technology               |
|--------------|---------------------------|
| ML Model     | Scikit-learn, Pandas, NumPy|
| Framework    | Django                    |
| Frontend     | HTML, CSS, Bootstrap      |
| Data Source  | PIMA Indian Diabetes Dataset |
| Deployment   | GitHub Pages (static preview) |

---

## 🚀 Getting Started

### 🔧 Installation

```bash
# Create and activate a virtual environment
python3 -m venv diabetesenv
source diabetesenv/bin/activate

# Install required libraries
pip install -r requirements.txt
```

---

### **▶️ Run the Project**
```bash
python manage.py runserver
```
Visit http://127.0.0.1:8000/ in your browser to access the app.

---

###**📁 Directory Structure**
Diabetes-Prediction/
├── DiabetesPrediction/     # Django app folder
├── templates/              # HTML templates
├── static/                 # Static files (images, CSS)
├── db.sqlite3              # SQLite database
├── diabetes.ipynb          # Jupyter notebook (model training)
├── manage.py               # Django project manager
└── requirements.txt        # Python dependencies

---

###**👨‍💻 Author**
Created with care by Abhay Kumar  🔗 GitHub 🔗 LinkedIn

---

###**📄 License**
This project is licensed under the MIT License. See the LICENSE file for more details.
