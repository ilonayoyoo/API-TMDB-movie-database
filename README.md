# Movie and Actor Trend Analysis Tool

This repository contains a collection of Python scripts designed for interacting with The Movie Database (TMDB) API to fetch and analyze trending movies and actors. The scripts allow users to discover movies based on popularity and release date, retrieve trending movies, discover popular actors, and replace genre IDs with their names for better readability.

## Features

- **Discover Movies**: Fetch movies released after a specific year, sorted by popularity.
- **Trending Movies**: Retrieve a list of movies trending on a daily basis.
- **Trending Actors**: Discover actors trending on a daily basis, with additional details and movies they are known for.
- **Genre Mapping**: Enhance movie and actor data with human-readable genre names instead of numerical IDs.

## Getting Started

### Prerequisites

Before running the scripts, ensure you have the following:

- Python 3.x installed on your system.
- `requests` library installed. You can install it using `pip install requests`.
- A valid TMDB API key. You can obtain one by signing up at [TMDB website](https://www.themoviedb.org/account/signup).

### Installation

1. Clone the repository to your local machine.
2. Install the required Python libraries using the following command:

    ```bash
    pip install -r requirements.txt
    ```

3. Replace the placeholder API keys in the scripts with your actual TMDB API key.

### Usage

#### Discover Movies Script

- The script `fetch_movies_released_after_2000.py` discovers movies released after 1990, sorted by popularity.
- To run the script:

    ```bash
    python fetch_movies_released_after_2000.py
    ```

#### Trending Movies Script

- Use `trending_movies.py` to fetch a list of trending movies for the day.
- Execute the script as follows:

    ```bash
    python trending_movies.py
    ```

#### Trending Actors Script

- The script `trending_actors.py` retrieves trending actors and their known movies, enhancing the dataset with readable genre names.
- Run the script using:

    ```bash
    python trending_actors.py
    ```

### Customization

You can customize the scripts by modifying the API call parameters such as the release date for movies or the page numbers for pagination.

## Data Output

The scripts output CSV files containing the fetched data with timestamped filenames for easy tracking. For example:

- `trendings_2024-02-15_22-55-55.csv` for trending movies.
- `Actors_2024-02-15_22-55-55.csv` for trending actors.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This tool is for educational and research purposes only. Please use responsibly and in accordance with TMDB's terms of service.

---

Feel free to customize the README.md file to better suit your project's needs or to add any additional instructions or documentation that might be helpful to users.
