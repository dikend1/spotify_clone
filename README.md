# Spotify Clone

This is a simple clone of the Spotify application built with Python and Django. The goal of this project is to replicate the core features of Spotify, including music streaming, playlist management, and user authentication, while maintaining a clean and functional UI.

## Features

- **User Authentication**: Users can sign up, log in, and manage their accounts.
- **Music Streaming**: Play and listen to music directly from the platform.
- **Playlist Management**: Create, update, and delete playlists.
- **Search Functionality**: Users can search for songs, artists, and albums.
- **Responsive Design**: The app is designed to work on both desktop and mobile devices.

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Python 3.x
- Django
- Pip (Python package manager)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/dikend1/Spotify_clone.git
cd Spotify_clone
python -m venv .venv
.venv\Scripts\activate  # On Windows
source .venv/bin/activate  # On MacOS/Linux
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
