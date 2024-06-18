# Shravani-s-CineMatch - Movie Recommendation System
Welcome to SP's Movie Recommendation System! This application allows users to manage a collection of movies, search for movies based on various criteria, get recommendations for top-rated movies, and more. It is built using Python and wxPython for the GUI.

## Features
* Add Movie: Add a new movie to the system.
* Search Movies: Search for movies by title, genre, language, or ID.
* Recommend Movies: Get a list of top-rated movie recommendations.
* Delete Movie: Remove a movie from the system.
* Display All Movies: Display all movies currently in the system.
* Exit Application: Exit the application.

## Requirements
* Python 3.x
* wxPython
* Installation

###  Clone the repository:
git clone https://github.com/yourusername/movierecommendationsystem.git
cd movierecommendationsystem

### Create a virtual environment and activate it:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

### Install the required packages:
pip install wxPython
Usage

### Run the application:
python main.py

## The main window of the application will appear with the following options:
* Add Movie: Opens a dialog to add a new movie.
* Search Movies: Opens a dialog to search for movies.
* Recommend Movies: Opens a dialog to get movie recommendations.
* Delete Movie: Opens a dialog to delete a movie.
* Display All Movies: Displays all movies in a message box.
* Exit Application: Prompts for confirmation before exiting the application.

## Code Overview
* Movie Class: Represents a movie with attributes like title, genre, rating, and language.
* MovieRecommendationSystem Class: Implements the core functionality of the system, including adding, searching, recommending, and deleting movies.
* MovieRecommendationApp Class: Defines the GUI for the application using wxPython.
