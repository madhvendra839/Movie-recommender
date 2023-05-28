# Movie Recommender System

This is a movie recommender system built using Python and Streamlit. It provides movie recommendations based on user selection and similarity scores between movies.

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/movie-recommender-system.git
   ```
## Install the required dependencies:

```
pip install -r requirements.txt
```
## Download the pre-trained model and data files. Place them in the root directory of the project:
`
movie_list.pkl
similarity.pkl
`
## Run the application:

```
streamlit run app.py
```
Open your web browser and navigate to http://localhost:8501 to access the application.

Usage
Select a movie from the dropdown menu or type its name in the input box.

Click the "Show Recommendation" button to view the recommended movies.

The top 5 recommended movies will be displayed, along with their titles and posters.

Dependencies
`
Python 3.7+
`
`
streamlit 0.80.0
`
`
requests
`
## Data Sources
The Movie Database (TMDb) API
