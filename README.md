# Netflix-EDA-Project

Exploratory Data Analysis (EDA) of Netflix titles to uncover insights about content trends, genres, ratings, and more. This project uses Python, Pandas, Matplotlib, Seaborn to clean, analyze, and visualize the Netflix dataset.

## Project Structure

EDA-Project/
│
├── data/                 # Raw and cleaned datasets, database
├── notebook/             # Jupyter notebooks for analysis
├── venv/                 # Virtual environment (not pushed)
├── visuals/              # All plotted visuals
├── README.md/            # Here, hey!!!
└──requirements.txt       # Project dependencies

## Purpose

* Understand the distribution of movies vs TV shows
* Analyze content by country, rating, and year
* Discover popular genres and directors
* Explore trends in content addition over time

## Data Cleaning

* Removed null values in important columns
* Converted date columns to datetime format
* Extracted year from `date_added`
* Standardized rating and duration formats
* Created new columns such as `release_year`, `added_year`

## Key Insights

* **Content Ratio**: 70% Movies, 30% TV Shows
* **Top Countries**: US leads in production
* **Ratings Distribution**: TV-MA is the most common
* **Peak Addition Year**: 2019 saw the most content additions
* **Top Genres**: International Movies, Dramas, and Comedies are dominant

Check the Notebook and Visuals!

## Technologies Used

* **Python** (Pandas, Matplotlib, Seaborn, WorldCloud)
* **SQLite**
* **Jupyter Notebook**
* **Git & GitHub** 

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/sudeirmaak/Netflix-EDA-Project.git
   cd Netflix-EDA-Project
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   Open `notebook/main.ipynb` in Jupyter or VS Code


## Dataset Source

[Netflix Titles on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Contact

**Zeynep Sude Irmak**
GitHub: [@sudeirmaak](https://github.com/sudeirmaak)
Email: `sudeirmak14@gmail.com`

