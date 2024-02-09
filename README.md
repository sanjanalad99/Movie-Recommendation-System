# Movie Recommendation System

This Python script implements a simple movie recommendation system based on collaborative filtering using user ratings. It utilizes the Pearson correlation coefficient to find similarity between movies and recommends movies based on user preferences.

## Dependencies

- pandas
- scipy

Install the required dependencies using:

```bash
pip install pandas scipy
```

## Usage

1. **Collaborative Filtering Dataset:**
   - This script is designed to work with a collaborative filtering dataset.
   - Ensure you have the `ratings.csv` and `movies.csv` files or replace them with your own dataset.
   - Adjust the file paths in the script accordingly.

2. **Run the Script:**
   - Execute the script using a Python environment:

     ```bash
     python movie_recommendation.py
     ```

3. **Interpretation:**
   - The script will load the data, clean it, and generate a correlation matrix based on user ratings.
   - Example usage is demonstrated for romantic and action movie lovers.

4. **Customization:**
   - You can customize the script by providing your own movie preferences in the form of a list.

## How It Works

1. Load and clean the data by merging movies and ratings, then creating a user-movie rating matrix.
2. Calculate the Pearson correlation matrix between movies based on user ratings.
3. Define a function to get similar movies for a given movie and rating.
4. Demonstrate the recommendation system for different sets of movie preferences.

Feel free to explore and customize the script to suit your preferences and datasets.

Happy movie recommending! 🎬
