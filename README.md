
# Sentiment Analysis Web Application

A web application built with **Django** that predicts the sentiment (Positive / Negative) of user input text using **TF-IDF vectorization** and a **Logistic Regression model**.  
The project also supports user authentication and stores analyzed sentences along with their predicted sentiments.

---

##  Features

-  **User Authentication**: Signup, Login, and Logout functionality.
-  **Sentiment Prediction**: Enter any text and get instant prediction.
-  **Sentence Records**: Stores sentences with their predicted sentiment and timestamp.
-  **Date/Time Records**: Keep track of when each prediction was made.
-  **User Management**: Each user can view their analyzed data separately.

---

##  Tech Stack

- **Backend**: Django (Python)  
- **Machine Learning**: TF-IDF Vectorizer + Logistic Regression  
- **Database**: SQLite (default Django DB)  
- **Frontend**: HTML, CSS, Bootstrap (Django Templates)

---

##  Project Structure
├── sentiment_app/ # Main Django app
│ ├── models.py # Models: Sentiment, Sentence, User, DateTime
│ ├── views.py # Views for prediction & user authentication
│ ├── urls.py # App-level routes
│ └── templates/ # HTML templates
│ ├── home.html
│ ├── login.html
│ ├── signup.html
│ ├── sentiment.html
│ └── ...
├── static/ # Static files (CSS, JS, Images)
├── model/ # Pre-trained ML model & vectorizer
│ ├── sentiment_model.pkl
│ └── vectorizer.pkl
├── manage.py # Django entry point
└── requirements.txt # Python dependencies


