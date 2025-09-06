# 🎵 Spotify Song Recommender System

This project implements a **content-based music recommendation system** that suggests songs based on their audio features and similarities. The goal is to enhance user engagement by creating personalized music discovery experiences.

The system uses **cosine similarity** to match songs based on multiple attributes such as **danceability, loudness, speechiness, tempo, valence, and energy**. To make it user-friendly, a **Tkinter-based GUI** was developed where users can input a song name and adjust sliders for different feature weights (e.g., loudness, popularity, tempo). The model then generates a list of recommended songs closest to the user’s preferences.

Additionally, a **Tableau dashboard** was built for interactive data exploration, and a **PowerPoint presentation** was prepared to explain the system objectives, design, and business use cases.

---

## 📌 Key Features
- **Song Matching Algorithm**: Uses cosine similarity to find closest matches.  
- **Interactive GUI**: Tkinter interface with sliders for user-defined feature weighting.  
- **User Personalization**: Recommendations tailored to mood and preferences.  
- **Visualization**: Tableau dashboard to explore dataset trends and song attributes.  
- **Dataset**: Derived from Kaggle’s [Music Recommendation System dataset](https://www.kaggle.com/code/tubaniksarl/music-recommendation-system).  

---

## 🛠️ Tools & Technologies
- **Python**: pandas, numpy, scikit-learn, tkinter  
- **Tableau**: Visualization and exploratory analysis  
- **Cosine Similarity**: Core recommendation algorithm
- **PowerPoint**: Presentation
