# Genre-Specific Lyric Generation Project

## Project Overview
This project fine-tunes the GPT-2 model to generate genre-specific song lyrics based on datasets collected from Spotify and Genius APIs. The project demonstrates the potential of AI in creative applications such as songwriting.

---

## Project Directory Structure

### `datasets/`
Contains the raw and cleaned datasets used for training and fine-tuning:
- `Country_spotify_lyrics.csv`: Lyrics for Country genre.
- `Electronic_spotify_lyrics.csv`: Lyrics for Electronic genre.
- `Hip-Hop_spotify_lyrics.csv`: Lyrics for Hip-Hop genre.
- `Jazz_spotify_lyrics.csv`: Lyrics for Jazz genre.
- `Pop_spotify_lyrics.csv`: Lyrics for Pop genre.
- `Rock_spotify_lyrics.csv`: Lyrics for Rock genre.
- `cleaned_lyrics_dataset.csv`: A consolidated and preprocessed dataset of lyrics across genres.

### `models/`
Stores the fine-tuned GPT-2 models for each genre:
- Subdirectories for each genre (e.g., `Jazz`, `Pop`, `Rock`, etc.) containing the fine-tuned model files.

### `results/`
Contains the results of the project, including:
- Generated lyrics for each genre (e.g., `generated_lyrics_Jazz.txt`).
- Visualizations such as loss curves and other evaluation metrics.

### Jupyter Notebooks 
- `data_preprocessing_EDA.ipynb`: Performs exploratory data analysis (EDA) and preprocessing on the raw datasets.
- `get_dataset.ipynb`: Fetches the raw datasets using Spotify and Genius APIs.
- `fine_tune.ipynb`: Fine-tunes the GPT-2 model for each genre.
- `generate_lyrics.ipynb`: Generates lyrics using the fine-tuned models and evaluates the results.
- `model.ipynb`: Contains functions for model training, evaluation, and lyric generation.

---

