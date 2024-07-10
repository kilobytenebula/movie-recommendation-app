# Movie Recommendation App

This project is a movie recommendation system built with Streamlit and The Movie Database (TMDB) API. The system recommends movies based on similarity and displays movie posters in an interactive carousel.

## Prerequisites

Before you begin, ensure you have met the following requirements:

1. **Python**: Make sure you have Python 3.7 or later installed. You can download it from the [official website](https://www.python.org/).

2. **Node.js and npm**: This project uses npm to build frontend assets. Download and install Node.js and npm from the [official website](https://nodejs.org/).

## Installation

Follow these steps to set up the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-app.git
   cd movie-recommendation-app
   ```
   
2. **Install Node.js dependencies and build frontend assets**:
   ```bash
   cd frontend
   npm install
   npm run build
   cd ..
   ```

3. **Set up API keys**:

   Sign up for a free account on [themoviedb.org](https://www.themoviedb.org/signup) and create a new [API key](https://www.themoviedb.org/settings/api). Update the `fetch_poster` function in your code to include this API key.

## Generate Similarity Matrices

This project uses precomputed similarity matrices stored in pickle files, which are not included in the repository. You need to generate these files by running the `Main.ipynb` notebook.

1. **Open the `Main.ipynb` notebook** in your preferred Jupyter environment.
2. **Run all the cells** in the notebook. This will compute the necessary similarity matrices and save them as pickle files.
3. Ensure the generated pickle files are placed in the appropriate directory as specified in the notebook.

## Usage

To start the application, run the following command:
```bash
streamlit run app.py
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
