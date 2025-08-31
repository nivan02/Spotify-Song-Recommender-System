# Spotify-Song-Recommender-System  

This project was developed to explore how Spotify’s music recommendation system can be enhanced through data-driven approaches. My goal was to build a recommender that leverages audio features of songs to generate personalized music discovery experiences. By analyzing attributes such as danceability, energy, tempo, and valence, I designed a system that suggests tracks most similar to a given input song, with the aim of improving user engagement through tailored recommendations.  

The recommendation model works by processing a dataset of Spotify tracks, extracting their key features, and applying similarity measures to identify the closest matches. Users can input a song and receive recommendations based on its characteristics, with the system ensuring that suggestions align closely with the input. This makes it possible to discover songs that share the same vibe, mood, or structure, even when the song titles don’t directly match.  

The dataset used extends until 2020, so recommendations are limited to songs available in that timeframe. While this provides a solid base for experimentation, the accuracy and diversity of the results depend on the completeness of the dataset. Expanding the dataset in the future would allow for even more relevant and up-to-date recommendations.  

The implementation is done in Python using libraries like pandas, numpy, and scikit-learn, with Jupyter Notebooks for analysis and visualization. I also created a simple interface where users can input a track name and explore recommendations interactively. For demonstration purposes, the system can take a song such as *“Shape of You”* and return a list of other tracks with similar audio patterns.  

The project demonstrates how structured music data can be transformed into practical recommendation systems. Looking ahead, I plan to extend this work by incorporating playlist-level recommendations, clustering-based methods, and potentially integrating with the Spotify API to allow for real-time, personalized suggestions.  
