# Music Recommender System

This project implements a music recommender system using the **KNN (K-Nearest Neighbors)** algorithm. The app recommends songs based on **audio features** such as **danceability**, **energy**, and **valence**. It integrates with the **Spotify API** for song data retrieval and playback.

## Features
- Song recommendations based on audio features.
- Integration with the Spotify API for fetching song data.
- Future enhancements will include:
  - User interaction tracking (e.g., play count, skips).
  - Hybrid recommendation model combining user data and audio features.
  - Mobile version (React Native).

## Requirements
- Python 3.x
- Node.js (for frontend)
- React (for the frontend app)
- Flask/FastAPI (for the backend)

### Python Dependencies
You can install all necessary Python dependencies with:

##### pip install -r requirements.txt


## Frontend Setup
To set up the frontend (React app):

### Install required Node packages:
- npm install

### Run the frontend:

- npm start

## Backend Setup
To run the backend (Flask/FastAPI app):

- Set up a virtual environment (optional but recommended):

  -python -m venv venv
- Activate the virtual environment:

  - On Windows:
    - venv\Scripts\activate
  - On Mac/Linux:
    - source venv/bin/activate

- Install required Python packages:
  - pip install -r requirements.txt

- Run the backend:
python app.py  # or uvicorn for FastAPI

## API Integration
This project uses the Spotify API to retrieve song data. To use the API, you need to set up your Spotify Developer credentials.
#### Steps to set up Spotify API:
- Go to the Spotify Developer Dashboard.
- Create a new app and get your Client ID and Client Secret.
- Set up OAuth authentication for user login and API access.

## Future Enhancements
- User Interaction Tracking: Use Spotify API to track how users interact with the music (e.g., play, skip).
- Hybrid Recommendation Model: Combine audio features and user data to make more personalized recommendations.
- Mobile Version: Build a mobile version using React Native