# TMDB Movie Recommendation System 🎬

Welcome to the TMDB Movie Recommendation System—your AI-powered movie matchmaker! Struggling to find a film after Inception? This recommendation engine, powered by the TMDB 5000 Movie Dataset, suggests exactly 5 movies you’ll love, wrapped in a sleek Streamlit app. As a data science fresher, I built this to showcase my Python, NLP, and ML skills, ready to impress recruiters. Lights, camera, action—let’s find your next favorite!


# 🚀 What’s This About?
This content-based recommendation system uses TF-IDF and cosine similarity to match movies based on genres, cast, directors, and overviews. It delivers exactly 5 recommendations per selection, like Rogue One for Star Wars fans, displayed in a user-friendly Streamlit app. Perfect for movie buffs and recruiters checking out my skills!


# 🎥 Features

**Five Perfect Picks:** Get exactly 5 movie recommendations tailored to your selection.

**NLP-Driven Matching:** Combines genres, cast, directors, and overviews for spot-on suggestions.

**Sleek Streamlit App:** A clean interface with a dropdown, red “Show Recommendations” button, and movie posters.

**Super Fast:** Uses .pkl files for instant data loading and recommendations.


# 🛠️ Tech Stack

**Python:** For all the data magic.

**Pandas & Scikit-learn:** Data handling and ML algorithms.

**NLTK:** Text preprocessing for NLP.

**Streamlit:** For the intuitive web app.

**Pickle Files:** movie_dict.pkl (movie data), movie_list.pkl (movie list), similarity.pkl (similarity matrix).


# 📂 Project Structure
TMDB-Movie-Recommendation-System/

├── Movie_recommendation_system.ipynb  # Core notebook: preprocessing, model, recommendations

├── movie_dict.pkl                    # Movie data dictionary

├── movie_list.pkl                    # Movie list for quick access

├── README.md                         # You’re reading it!

**Notes:**similarity.pkl is in GitHub Releases due to its size.

The TMDB 5000 Movie Dataset (tmdb_5000_movies.csv, tmdb_5000_credits.csv) is sourced from Kaggle.

Live app is available at Streamlit.(https://tmdb-movie-recommendation-system-5xdgoqjowxkewicmuzoj9m.streamlit.app/)


# ⚙️ Setup Instructions

**1. Clone the Repository:**

git clone https://github.com/DivyaSriThatikonda/TMDB-Movie-Recommendation-System.git
cd TMDB-Movie-Recommendation-System

**2. Download similarity.pkl:**

Visit GitHub Releases and Download similarity.pkl and place it in the project root.


**3. Get the Dataset (optional, for preprocessing):**

Download tmdb_5000_movies.csv and tmdb_5000_credits.csv from Kaggle.

Place them in the project root if you want to rerun preprocessing.


**4. Install Dependencies:**

Set up a virtual environment and install packages:

python -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install pandas scikit-learn nltk streamlit


**5.Set Up NLTK:** Run this in a Python shell:

import nltk

nltk.download('punkt')

nltk.download('stopwords')



# 🎬 How to Use

**Try the Live App:**

https://tmdb-movie-recommendation-system-5xdgoqjowxkewicmuzoj9m.streamlit.app/

**Visit the Streamlit app.**

Select a movie (e.g., Tangled) from the dropdown.

Click the red “Show Recommendations” button to see exactly 5 suggestions, like Aladdin and Frozen, with their posters.


**Run Locally (Optional):**

If you have app.py (not in the repo but required for local running), launch the app:streamlit run app.py


Follow the same steps as above to get recommendations.



# 🙌 Acknowledgments

**TMDB:** For the awesome movie dataset.

**Kaggle:** For hosting the TMDB 5000 Movie Dataset.

**Open-Source Community:** For Pandas, Scikit-learn, NLTK, and Streamlit.


# 🌟 Try It Out!
Visit GitHub or the live app to find your next movie obsession. 

https://tmdb-movie-recommendation-system-5xdgoqjowxkewicmuzoj9m.streamlit.app/
