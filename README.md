# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

## Movie Recommendation System

## Dataset

This project uses the **TMDB 5000 Movie Dataset**, which is available on Kaggle: [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

### Steps to Load the Dataset:

1. Download the dataset from Kaggle.
2. Place the following CSV files in the same directory as the script:
   - `tmdb_5000_movies.csv`
   - `tmdb_5000_credits.csv`

## Setup

### Requirements:

- Python 3.7+
- Required libraries: `numpy`, `pandas`, `scikit-learn`

### Installation Steps:

1. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use: env\Scripts\activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Running the Code

You can run the recommendation system on jupyter notebook:

1. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Load the notebook and run the cells step by step.

## Example Output

### User Input:

```plaintext
"I love thrilling action movies set in space."
```

### System Output:

```plaintext
Top Recommendations:
1. Grindhouse (Score: 0.2312)
2. Space Pirate Captain Harlock (Score: 0.1832)
3. Lockout (Score: 0.1549)
4. Blow Out (Score: 0.1532)
5. Dragon Blade (Score: 0.1381)
```
