Movie Recommender System
Overview
This project is a movie recommender system built using content-based filtering. It leverages the TMDB movie dataset to provide personalized movie recommendations based on movie attributes like genres, descriptions, and other metadata. The recommender system is implemented with Python and presented through a web interface using Streamlit.

Features
Movie Recommendations: Get recommendations based on a selected movie using content-based filtering.
Interactive Web Interface: Built with Streamlit for a user-friendly experience.
Poster Display: Shows movie posters alongside recommendations.
Technologies
Python: Programming language used for development.
Streamlit: Framework for creating the web app interface.
Pandas: For data manipulation and handling.
Scikit-learn: For implementing content-based filtering techniques.
Requests: For fetching movie posters from the TMDB API.
TMDB API: Provides movie metadata and poster images.
Dataset
The project uses the TMDB movie dataset, which includes information about movies such as titles, genres, descriptions, and more.

Required Files
movies.pkl: Pickle file containing the movie data.
similarity.pkl: Pickle file containing the similarity matrix.
Download similarity.pkl
The similarity.pkl file is required for the recommendation algorithm. You can download it from Google Drive using the following link:

Download similarity.pkl

Setup and Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/Nishnat14/Movies-recommender-system.git
cd Movies-recommender-system
Create a Virtual Environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Required Packages:

bash
Copy code
pip install -r requirements.txt
Obtain TMDB API Key:

Sign up at TMDB and get an API key.
Replace your_api_key in the code with your actual API key.
Download and Place Files:

Download movies.pkl and similarity.pkl from the provided links.
Place them in the project directory.
Usage
Run the Streamlit App:

bash
Copy code
streamlit run app.py
Access the Web App:

Open a web browser and navigate to http://localhost:8501.
Select a movie from the dropdown and click the "Recommend" button to get movie recommendations.
Screenshots
Here are some screenshots of the project in action:

Home Screen

Recommendation Results

Movie Poster Display

Files
app.py: Main Streamlit application file.
movies.pkl: Pickle file containing the movie data.
similarity.pkl: Pickle file containing the similarity matrix.
requirements.txt: File listing the required Python packages.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

Contact
For questions or feedback, please contact me at singhnishantwork@example.com.
