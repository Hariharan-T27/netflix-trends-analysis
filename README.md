 # Netflix User Behaviour Analysis

This project explores user viewing behavior on Netflix through exploratory data analysis (EDA), visualization, and segmentation techniques. By analyzing ratings, watch hours, genres, and binge-watching patterns, the project uncovers insights into viewing trends and creates user segments for better personalization.

## Project Structure
```bash
User Behaviour-Netflix/
  ├──data/
  |  ├──processed/
  |  |   ├── netflix_viewing_data_clean.csv    # Cleaned dataset
  |  |   └── user_segments.csv                 # Clustered user segments
  |  └──raw/
  |      └── netflix_viewing_data.csv          # Raw dataset
  ├── reports/
  |   └──figures/
  |        ├── Rating Vs Watch.png               # Visualization: Ratings vs Watch Hours
  |        ├── Total Watch Hour.png              # Visualization: Total Watch Hours by Genre
  |        └── User Segments.png                 # Visualization: User segmentation in 3D
  |
  ├── eda_and_process.ipynb             # Jupyter Notebook with analysis
  └── README.md                         # Project documentation
```

## Tech Stack
- **Python** (Data Analysis & ML)

- **Pandas, NumPy** (Data Processing)

- **Matplotlib, Seaborn, Plotly** (Visualization)

- **Scikit-learn** (Clustering & ML models)

- **Jupyter Notebook** (Exploratory Analysis)

## Key Analysis & Insights
### 1. Ratings vs Watch Hours
Scatter plot showing the relationship between user ratings and watch hours, colored by genres.

### 2. Total Watch Hours by Genre

Bar chart showing which genres dominate total watch time. Comedy, Romance, and Thriller appear as top genres.


### 3. User Segmentation (Clustering)

3D visualization of user clusters based on ratings, watch hours, and binge-watching behavior.


## Key Findings

- Comedy and Romance are the most-watched genres.

- High ratings are not always linked with high watch hours, suggesting preference-driven behavior.

- User segmentation identified different groups:

    - Binge Watchers (high watch hours, moderate ratings)

    - Selective Viewers (low hours, high ratings)

    - Casual Viewers (low hours, mixed ratings)

    - Balanced Users (moderate across all metrics)



## Future Improvements

- Add demographic features (age, region, device type) for deeper insights.

- Apply recommendation systems based on user clusters.

- Build an interactive dashboard (Streamlit / Plotly Dash) for real-time insights.


## Author

**Hariharan**

📧 [thariharan76@gmail.com]

🌐 [https://www.linkedin.com/in/hariharanthirunagari]
