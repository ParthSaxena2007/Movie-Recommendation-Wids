# Content-Based Movie Recommendation System

## Project Objective
The objective of this project is to build a **content-based movie recommendation system** using movie metadata such as genres, cast, director, and keywords.

## Work Completed

### Week 2 – Exploratory Data Analysis
- Performed genre-wise analysis of movies
- Visualized distribution of movies across different genres

### Week 3 – Dataset Creation
- Merged multiple datasets:
  - Movies metadata
  - Credits
  - Keywords
  - Links
- Filtered valid movies and created a master dataset

### Week 4 – Data Preprocessing
- Cleaned and processed text-based features
- Extracted genres, cast, director, and keywords
- Created a combined **`soup`** feature representing each movie
- Selected the **top 2500 movies based on popularity**
- Generated the final dataset used for recommendations

### Week 5 – Recommendation System
- Converted movie features into numerical form using **CountVectorizer**
- Used **cosine similarity** to compute similarity between movies
- Implemented a recommendation function that:
  - Takes a movie title as input
  - Returns similar movies
  - Displays movie title, director, and release date

## Files in Repository
- Week-wise Jupyter notebooks documenting each stage of the project
- `master_dataset_final.csv`: Final processed dataset used for the recommendation system

## Usage
The recommendation system can be used by calling the `recommend()` function in the Week 5 notebook with a movie title as input.
