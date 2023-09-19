# Spotify Artist Search

A simple Python script that interfaces with the Spotify Web API to fetch an artist's top tracks.

## Prerequisites

- Python 3
- A Spotify Developer account to access the Client ID and Client Secret

## Setup

1. **Clone the Repository**:

   ```
   git clone https://github.com/TishaMazumdar/using-spotify-api.git
   cd using-spotify-api
   ```

2. **Virtual Environment (optional but recommended)**:

   Create a virtual environment to keep dependencies scoped to the project:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:

   ```bash
   pip install requests python-dotenv
   ```

4. **Setting up `.env`**:

   Create a `.env` file in the root of the project. Add your Spotify `CLIENT_ID` and `CLIENT_SECRET` to this file:

   ```env
   CLIENT_ID = your_spotify_client_id
   CLIENT_SECRET = your_spotify_client_secret
   ```

   Replace `your_spotify_client_id` and `your_spotify_client_secret` with your actual credentials from the Spotify Developer Dashboard.

## Usage

Execute the script:

```bash
python main.py
```

## Features

- Retrieves an OAuth token from Spotify.
- Searches for an artist using their name.
- Fetches the top tracks for the found artist specific to a country (set to "IN" or India by default).

## Contributing

Feel free to fork this repository, make your changes, and submit a pull request. We're open to your suggestions!
