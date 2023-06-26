# Movie Recommendation

This project is a Python-based movie recommendation system that suggests movies to users based on their watching history, ratings, and genres. It utilizes a dataset stored in the "movies.csv" file.

## Project Overview

The recommendation system follows these key steps:

1. Data Preprocessing:
   - The dataset, stored in the "movies.csv" file, is loaded and preprocessed.
   - The relevant features, including watching history, ratings, and genres, are extracted from the dataset.

2. Recommendation Algorithm:
   - Using the collected user data, the recommendation algorithm generates personalized movie suggestions.
   - The algorithm considers a user's watching history, ratings, and preferred genres to make recommendations.

3. Recommendation Generation:
   - The system generates a list of 10 recommended movies for each of the 600 users in the dataset.
   - These recommendations are tailored to each user's preferences and aim to enhance their movie-watching experience.

## Usage

To use the movie recommendation system:

1. Ensure you have the required dependencies installed. You can find a list of dependencies in the `requirements.txt` file.

2. Obtain the dataset:
   - Download the dataset file, "movies.csv," which contains the necessary movie data, including watching history, ratings, and genres.
   - Place the dataset file in the designated directory: `data/movies.csv`.

3. Run the main code or execute the Jupyter Notebook:
   - The main code file, "movie_recommendation.py," or the Jupyter Notebook file, "movie_recommendation.ipynb," contains the implementation of the recommendation system.
   - Running the code or executing the notebook will generate movie recommendations for each user based on their watching history, ratings, and preferred genres.

Please note that the recommendations provided by this system are specific to the dataset and algorithm used. Modifications may be required to adapt the code to different datasets or to incorporate additional features.

## File Descriptions

- `movie_recommendation.py` or `movie_recommendation.ipynb`: The main code file or Jupyter Notebook containing the implementation of the movie recommendation system.
- `data/movies.csv`: The dataset file containing movie data, including watching history, ratings, and genres.

## Results

The movie recommendation system successfully generates personalized movie recommendations for all 600 users based on their watching history, ratings, and preferred genres. Each user receives a list of 10 recommended movies, tailored to their individual preferences and movie preferences.

These recommendations aim to enhance the movie-watching experience by suggesting movies that align with the user's previous choices and interests. By considering the user's watching history, ratings, and genres, the system provides targeted suggestions that increase the likelihood of user satisfaction.

## Contributing

Contributions to this project are currently not accepted. However, you are encouraged to use the code and methodology provided as a foundation for further research and development. Feel free to adapt the code to different datasets, explore alternative recommendation algorithms, or enhance the user experience of the system.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please refer to the `LICENSE` file for more details.

For any questions or inquiries regarding this project, please contact the project team at [email address].
