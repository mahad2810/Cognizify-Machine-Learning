# Machine Learning Internship Submission

## Project Overview
This submission includes three machine learning tasks focused on the restaurant industry, demonstrating proficiency in data preprocessing, machine learning modeling, data visualization, and recommendation systems.

### Task 1: Predict Aggregate Restaurant Ratings
**Objective:** Build a regression model to predict the aggregate rating of a restaurant based on its features.

#### Steps:
1. **Data Preprocessing:**
   - Handled missing values by filling numeric columns with the median and categorical columns with "Unknown."
   - Encoded binary and categorical features using mapping and label encoding.
   - Split the dataset into training and testing sets.

2. **Model Selection and Training:**
   - Used a Random Forest Regressor to train the model.

3. **Evaluation:**
   - Evaluated performance using Mean Squared Error (MSE) and R-squared metrics.
   - Identified feature importance to analyze influential features.

#### Results:
- **Mean Squared Error:** <output value>
- **R-squared:** <output value>
- **Feature Importance:** Features such as "Votes," "Average Cost for Two," and "Price Range" had the highest influence on restaurant ratings.

---

### Task 2: Geographical Analysis of Restaurants
**Objective:** Perform geographical analysis to identify patterns and insights based on restaurant locations.

#### Steps:
1. **Data Visualization:**
   - Plotted the geographical distribution of restaurants using latitude and longitude coordinates.
   - Created a heatmap to visualize restaurant density.
   
2. **Analysis:**
   - Grouped restaurants by city to analyze concentration, average ratings, and price ranges.
   - Explored the correlation between price range and aggregate rating.

3. **Findings:**
   - Top cities with the most restaurants were <list top cities>.
   - Popular cuisines included <list cuisines>, with Italian and Chinese leading.
   - Cities with higher price ranges tended to have slightly better ratings.

#### Visualizations:
- Heatmap of restaurant locations.
- Bar charts for top cities, average ratings, and popular cuisines.

---

### Task 3: Restaurant Recommendation System
**Objective:** Build a recommendation system based on user preferences.

#### Steps:
1. **Data Preprocessing:**
   - Handled missing values and encoded categorical variables.
   - Combined multiple features into a single text column for similarity calculations.

2. **Model Development:**
   - Used content-based filtering with a CountVectorizer and cosine similarity to calculate similarity scores.

3. **Testing:**
   - Provided sample user preferences and evaluated the quality of recommendations.

#### Example:
**User Preferences:**
- Cuisines: Italian
- City: New York
- Locality: Manhattan
- Price Range: 3
- Minimum Rating: 4.0

**Recommended Restaurants:**
| Restaurant Name | Cuisines | City       | Locality   | Average Cost for Two | Aggregate Rating |
|-----------------|----------|------------|------------|-----------------------|------------------|
| <Restaurant 1> | Italian  | New York   | Manhattan  | $50                  | 4.5              |
| <Restaurant 2> | Italian  | New York   | Manhattan  | $60                  | 4.2              |

---

## Files Included
1. **task1.ipynb:** Code for building and evaluating the regression model.
2. **task2.ipynb:** Code for visualizing and analyzing geographical data.
3. **task3.ipynb:** Code for the recommendation system.
4. **Dataset.csv:** The dataset used for all tasks.
5. **summary_insights.csv:** Summary insights from Task 2.

## Requirements
- Python 3.8+
- Libraries: pandas, numpy, sklearn, seaborn, matplotlib, folium, geopandas, shapely
- Jupyter Notebook (for interactive exploration)



### How to Run the Project

1. **Clone the Repository**  
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Folder**  
   ```bash
   cd <project-folder-name>
   ```

3. **Install Dependencies**  
   Make sure you have Python and `pip` installed. Then, install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**  
   Start Jupyter Notebook in the project folder:  
   ```bash
   jupyter notebook
   ```

5. **Execute Tasks**  
   Open and run the following notebooks in Jupyter Notebook:
   - `task1.ipynb` for predicting aggregate restaurant ratings.
   - `task2.ipynb` for geographical analysis of restaurants.
   - `task3.ipynb` for the restaurant recommendation system.

6. **View Results**  
   Follow the outputs and visualizations generated in each notebook to analyze results for each task.

---

