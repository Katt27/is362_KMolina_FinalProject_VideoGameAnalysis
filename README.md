# Video Game Sales and Ratings Analysis

## **Project Overview**
This project analyzes video game sales and their relationship with critic (`meta_score`) and user (`user_review`) ratings. By combining two datasets, we aim to uncover trends and insights across platforms, genres, and regions. The analysis includes data cleaning, transformation, statistical exploration, visualizations, and predictive modeling.

---

## **Motivation**
As a passionate gamer, I wanted to explore the video game industry through data. This project combines sales figures and ratings to provide actionable insights into the factors influencing a game's success.

---

## **Datasets**
1. **Video Game Sales Dataset (`vgsales.csv`)**
   - Source: [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)
   - Description: Sales data for video games across different regions and platforms.

2. **Game Metadata and Ratings Dataset (`all_games.csv`)**
   - Source: [Kaggle](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023)
   - Description: Metadata for video games, including critic scores, user reviews, and release dates.

---

## **Project Workflow**
1. **Data Acquisition**:
   - Two datasets were sourced from Kaggle.
2. **Data Cleaning**:
   - Replaced missing and invalid values (e.g., `"tbd"` with `NaN`).
   - Normalized columns (game titles and platforms) for merging.
3. **Data Transformation**:
   - Merged datasets on normalized game titles and platforms.
   - Calculated regional sales contributions as percentages.
4. **Exploratory Analysis**:
   - Grouped data by genre and platform to identify trends.
   - Conducted correlation analysis between sales and ratings.
5. **Predictive Modeling**:
   - Built a regression model to predict global sales using critic and user scores.
6. **Visualization**:
   - Created scatterplots and bar charts to validate findings.

---

## **Key Features**
- **Data Transformation**: Merged two datasets with different structures using normalization techniques.
- **Statistical Analysis**:
  - Correlation analysis between ratings and global sales.
  - Regression modeling to predict global sales.
- **Visualizations**:
  - Scatterplots: Relationships between sales and scores.
  - Bar Charts: Global sales distribution by genre.

---

## **Technologies Used**
- **Python Libraries**:
  - `pandas`: Data cleaning and manipulation.
  - `numpy`: Numerical computations.
  - `matplotlib`: Data visualization.
  - `scikit-learn`: Predictive modeling and evaluation.

- **Platform**:
  - Jupyter Notebook: Interactive Python development and presentation.

---

## **Challenges**
1. Handling non-numeric values (`"tbd"`) in the ratings dataset.
2. Merging datasets with inconsistent naming conventions (e.g., platforms and titles).

---

## **Results**
1. **High critic scores correlate strongly with higher global sales.**
2. **Genres like Action and Sports dominate global sales.**
3. **The regression model demonstrated significant predictive power with an R² value of [insert result].**
