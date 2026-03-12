# 🎬 Movie Recommender System (Streamlit Frontend)

A modern **Streamlit web application** that recommends movies using a backend API.  
The app fetches movie recommendations and displays them in a clean card-style interface with posters and movie details.

---

## 🚀 Features

- 🎥 Movie recommendation system
- 🔎 Search and discover movies
- 🖼️ Displays movie posters using TMDB
- 📄 Movie details page
- ⚡ Fast API integration
- 📱 Clean and responsive Streamlit UI
- 🔁 Navigation between home and details page

---

## 🛠️ Tech Stack

- Python
- Streamlit
- REST API
- Requests
- TMDB Image API

---

## 📂 Project Structure
movie-recommender-ui
│
├── app.py # Main Streamlit application
├── requirements.txt # Project dependencies
└── README.md # Project documentation


---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/hms-69/movie-recommender
cd movie-recommender-ui

2️⃣ Create Virtual Environment (Optional)
python -m venv venv

Activate environment

Windows

venv\Scripts\activate

Mac / Linux

source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
▶️ Run the Application
streamlit run app.py

Then open in browser:

http://localhost:8501
🔗 API Configuration

The app connects to a backend recommendation API.

Inside app.py:

API_BASE = "https://movie-recommender-system-34pb.onrender.com"

You can also run it locally:

API_BASE = "http://127.0.0.1:8000"
🖼 Movie Posters

Movie posters are fetched from TMDB:

https://image.tmdb.org/t/p/w500
💡 How It Works

User opens the app.

The frontend sends requests to the movie recommendation API.

API returns recommended movies.

Streamlit displays them as movie cards.

Clicking a movie opens a details page.

🔮 Future Improvements

Movie trailers

User ratings

Genre filters

Watchlist feature

Authentication system

👨‍💻 Author

Developed by Himanshu
