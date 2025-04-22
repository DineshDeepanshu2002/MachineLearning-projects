🏏 First Innings Score Prediction - IPL
This project predicts the first innings score in an IPL (Indian Premier League) match based on various match features using machine learning techniques. It provides insights into how team compositions, match location, and game progression affect the projected score.

📌 Problem Statement
Predict the final score of the first innings in an IPL match using available match details up to a certain point (e.g., after 5 or 10 overs). This helps in real-time score estimation and can be useful for broadcasters, betting markets, and analysts.

📂 Dataset
The dataset consists of historical IPL match data.

Key features include:

Batting team

Bowling team

City

Current score

Overs completed

Wickets lost

Runs in previous 5 overs

Wickets in previous 5 overs

🧠 Machine Learning Techniques
Preprocessing:

Encoding categorical variables (e.g., team names, city)

Handling missing values

Feature scaling (if applicable)

Models Used:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Possibly others (based on notebook content)

Evaluation Metrics:

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

📈 Results
The Random Forest model performed best with [insert accuracy or metric results here].

Visualizations show model comparisons, feature importance, and prediction vs. actual score plots.

🚀 How to Run
Clone this repo

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook "First Innings Score Prediction - IPL.ipynb"
📊 Visualizations
Run Distribution Graphs

Overs vs. Run Rate

Actual vs. Predicted Score Plots

Feature Importance Charts

📚 Future Improvements
Use ball-by-ball data for even more granular predictions.

Incorporate player stats, weather data, and pitch reports.

Build a real-time web app or dashboard for live predictions.
