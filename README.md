# 🎬 Movie Recommender System

1. Download/clone this repository and extract `dataset.zip`.

2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn streamlit requests
````

3. Get a TMDB API key by creating an account at (https://www.themoviedb.org/) and going to Settings → API.

4. Add your TMDB API key in `app.py`.

5. Run movie-recommender.ipynb file which will save `movie_list.pkl` and `similarity.pkl` files, place them in the same folder as `app.py`.

6. Run the application:

   ```bash
   streamlit run app.py
   ```
