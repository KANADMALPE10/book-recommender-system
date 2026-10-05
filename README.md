📚 Book Recommender System

A machine learning-based book recommendation system built using Python, Pandas, Scikit-learn and Flask.

🚀 Features

* 📖 Browse popular books
* 🔍 Search for books
* 🤖 Get book recommendations
* 📊 Similarity-based recommendation system
* 🌐 Flask-based web application

🛠️ Tech Stack

* Python
* Flask
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* HTML/CSS

🧠 How It Works

The system uses book ratings and user interactions to create a recommendation system.

The data is processed using Pandas, and a book-user matrix is created. Similarity scores are then calculated to identify books that are similar to a selected book.

The recommendation model is stored using Python pickle files and loaded by the Flask application.

Recommendation Pipeline

Books + Ratings Data
        ↓
Data Cleaning & Processing
        ↓
User-Book Matrix
        ↓
Similarity Calculation
        ↓
Recommendation Engine
        ↓
Flask Web Application

📂 Project Structure

book-recommender-system/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── data/
│   ├── Books.csv
│   ├── Ratings.csv
│   └── Users.csv
│
├── model/
│   ├── books.pkl
│   ├── popular.pkl
│   ├── pt.pkl
│   └── similarity_scores.pkl
│
├── notebooks/
│   └── book-recommender-system.ipynb
│
├── templates/
│   └── ...
│
└── screenshots/

⚙️ Installation

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/book-recommender-system.git
cd book-recommender-system

2. Create a virtual environment

python -m venv .venv

3. Activate the virtual environment

macOS/Linux:

source .venv/bin/activate

4. Install dependencies

pip install -r requirements.txt

5. Run the application

python app.py

Then open:

http://127.0.0.1:5001

📊 Dataset

The project uses book, user and rating data to generate recommendations.

🔮 Future Improvements

* Deploy the application online
* Improve recommendation accuracy
* Add user authentication
* Add book covers and metadata
* Add search/autocomplete
* Improve the user interface
* Explore advanced recommendation algorithms

👨‍💻 Author

Kanad Malpe

Electronics & Telecommunication Engineering Student interested in Artificial Intelligence, Machine Learning and Data Science.