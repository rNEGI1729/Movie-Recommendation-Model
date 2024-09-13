## Movie Recommender System
# Overview
This repository contains the code for a Movie Recommender System built using Python and machine learning techniques. The recommender system suggests movies to users based on their similarity to other movies. This project demonstrates how to process a dataset of movies and build a recommendation engine using a combination of techniques like cosine similarity.

Features
Movie Recommendations: The system recommends five movies based on the input movie provided by the user.
Similarity Calculation: Utilizes cosine similarity to find movies that are most similar to the one provided.
Streamlit App: The project has been deployed as a web app using Streamlit, providing an easy-to-use interface for users to enter a movie and receive recommendations.
Data Handling: Efficiently handles large datasets and provides fast and relevant recommendations.
Installation
To run this project locally, you need to have Python and the necessary dependencies installed. Follow the instructions below to set up the project on your local machine.

Requirements
Python 3.x
Pandas
Numpy
Scikit-learn
Streamlit
Pickle (for loading pre-saved similarity matrices)
# Steps
1.Clone the repository:
git clone https://github.com/username/Movie-Recommender-System.git
cd Movie-Recommender-System
2.Install the required dependencies:
pip install -r requirements.txt
3.Run the Streamlit app:
streamlit run app.py
4.Open your browser and go to http://localhost:8501 to access the recommender system.
#Data
The recommender system uses a dataset containing movie details such as title, genre, and metadata. The similarity between movies is pre-computed and stored in two parts (similarity_part1.pkl and similarity_part2.pkl), which are loaded into the system during runtime to calculate movie recommendations.

Usage
To get movie recommendations:

Enter the name of a movie in the search bar.
The system will return a list of five recommended movies based on their similarity to the input movie.
# Project Structure
- app.py: The main file for running the Streamlit web app.
- similarity_part1.pkl & similarity_part2.pkl: Precomputed similarity matrices for movies.
- Movie-Recommender-System.ipynb: Jupyter Notebook containing the code for building the recommender system.
- requirements.txt: List of required packages and dependencies.
# Future Improvements
- Enhance recommendation accuracy by incorporating user ratings.
- Add more filtering options, such as genre or release year.
- Implement collaborative filtering techniques.
- Deploy on a cloud service for wider access.
