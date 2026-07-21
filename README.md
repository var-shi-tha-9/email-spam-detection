# 📧 Email Spam Detection System

A Machine Learning-based Email Spam Detection web application built using **Python**, **Flask**, **Scikit-learn**, and **Natural Language Processing (NLP)**. The application classifies email messages as **Spam** or **Not Spam (Ham)** through a simple and interactive web interface.

---

## 📖 Overview

Email spam is one of the most common problems in digital communication. This project uses Machine Learning techniques to automatically detect whether an email is spam or legitimate. It leverages text preprocessing, feature extraction, and a trained classification model to provide accurate predictions in real time.

---

## 🎯 Objectives

- Detect spam emails automatically.
- Improve email security by filtering unwanted messages.
- Demonstrate the use of Machine Learning for text classification.
- Provide a user-friendly web interface for spam prediction.

---

## ✨ Features

- 📩 Predicts whether an email is Spam or Not Spam.
- ⚡ Real-time prediction using a trained Machine Learning model.
- 🌐 Interactive web interface built with Flask.
- 📝 Text preprocessing using NLP techniques.
- 💾 Uses pre-trained model and vectorizer for faster predictions.
- 🚀 Lightweight and easy to deploy.

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Framework:** Flask
- **Machine Learning:** Scikit-learn
- **Natural Language Processing:** TF-IDF / CountVectorizer
- **Frontend:** HTML, CSS
- **Model Storage:** Pickle (.pkl)

---

## 📂 Project Structure

```
Email-Spam-Detection/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. User enters an email message.
2. The text is preprocessed and transformed into numerical features using the saved vectorizer.
3. The trained Machine Learning model predicts whether the email is Spam or Not Spam.
4. The result is displayed instantly on the web page.

---

## 🧠 Workflow

```
Email Text
     │
     ▼
Text Preprocessing
     │
     ▼
Feature Extraction (TF-IDF / CountVectorizer)
     │
     ▼
Machine Learning Model
     │
     ▼
Spam / Not Spam
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Email-Spam-Detection.git
```

### Navigate to the project folder

```bash
cd Email-Spam-Detection
```

### Install the required packages

```bash
pip install -r requirements.txt
```

*(If you don't have a requirements.txt file, install manually:)*

```bash
pip install flask scikit-learn pandas numpy
```

### Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

## 💻 Usage

1. Launch the application.
2. Enter an email message into the text box.
3. Click the **Predict** button.
4. View the prediction result.

---

## 📸 Sample Output

### Example 1

**Input**

```
Congratulations! You have won a free iPhone. Click here to claim your prize.
```

**Output**

```
Spam
```

---

### Example 2

**Input**

```
Hi Team,

Please find the meeting agenda attached.

Thank you.
```

**Output**

```
Not Spam
```

---

## 📚 Applications

- Email spam filtering
- Business communication systems
- Personal email management
- Cybersecurity solutions
- Educational Machine Learning projects

---

## 🔮 Future Enhancements

- Improve accuracy using Deep Learning models.
- Add multiple language support.
- Store prediction history in a database.
- Deploy the application on Render or AWS.
- Add user authentication.
- Integrate with email services for automatic filtering.

---

## 🎓 Learning Outcomes

This project demonstrates knowledge of:

- Machine Learning
- Natural Language Processing (NLP)
- Flask Web Development
- Text Classification
- Python Programming
- Model Deployment
- Git & GitHub

---


