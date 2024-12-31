# Movie Recommendation System

This repository demonstrates various types of recommender systems for movies, including demographic filtering, content-based filtering, and collaborative filtering.

## Project Overview

The project explores different recommendation techniques:

- **Demographic Filtering**: Recommends popular movies based on general trends.
- **Content-Based Filtering**: Suggests movies similar to those a user has liked, based on movie attributes.
- **Collaborative Filtering**: Recommends movies by analyzing user-item interactions to find patterns among users and items.

## Repository Structure

- `Demographic_Filtering_Recommender.ipynb`: Notebook demonstrating demographic filtering techniques.
- `Content_Based_Filtering.ipynb`: Notebook implementing content-based filtering methods.
- `Collaborative_Filtering.ipynb`: Notebook showcasing collaborative filtering approaches.
- `data/`: Directory containing datasets used in the project.
- `LICENSE`: License information.
- `README.md`: Project overview and instructions.

## Getting Started

To explore the recommender systems:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/al-chris/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```

2. **Set up a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebooks**:

   ```bash
   jupyter notebook
   ```

   Open the desired notebook to explore the corresponding recommender system.

## Dataset

The project utilizes a movie dataset containing information such as movie titles, genres, and user ratings. The dataset is located in the `data/` directory.

## Contributing

Contributions are welcome. Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Dataset: [MovieLens](https://grouplens.org/datasets/movielens/)
- Inspiration: Various open-source movie recommendation projects on GitHub.

For any questions or suggestions, please contact [Christopher Aliu](https://github.com/al-chris). 
