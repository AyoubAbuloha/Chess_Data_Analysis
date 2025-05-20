
Chess Game Data Analysis & Winner Prediction.

Stu: Ayoub_Abuloha . StuNum: 12144424


📌 Introduction
This project explores a dataset of online chess games to understand patterns in gameplay and to predict the winner using machine learning techniques. The goal is to perform data analysis, generate visual insights, and build a model capable of predicting the likely winner based on various in-game factors.


🎮 Gameplay Demonstration
The dataset, `games.csv`, includes detailed records of chess matches such as:
- Player ratings (white and black)
- Game duration in turns
- Opening strategies
- Victory conditions
- Game outcomes (winner, draw, resignation, etc.)

These records simulate gameplay and allow for rich data collection and analysis.


📊 Analytics Dashboard Features
Several visualizations were created to uncover trends:
- **Distribution of Game Length**: Showcases how long games typically last.
- **Victory Status Count**: Analyzes how games are won (checkmate, resignation, timeout, etc.).
- **Average Turns by Victory Status**: Compares game duration across different victory conditions.
- **Player Rating Distributions**: Highlights the skill range of players.
- **Top 10 Chess Openings**: Lists the most frequently used opening strategies.

These visuals offer insights into player behavior and strategies.


🤖 Machine Learning Implementation

🎯 Goal
To predict the winner (white or black) of a chess match based on:
- Player ratings
- Number of turns
- Opening ply
- Whether the game was rated

🔧 Models Used
1. Random Forest Classifier:
   - Robust ensemble model
   - Evaluated with classification report and confusion matrix

2. Decision Tree Classifier:
   - Provides clear visual interpretation of decisions
   - Exported as text and plotted as a decision tree diagram


🧪 ML Predictions on New Data
The dataset is split into training and testing sets. After training, predictions were made on the test set, and the models demonstrated the ability to classify the winner with good accuracy. Performance was evaluated with:
- Precision
- Recall
- F1-score
- Confusion matrix

The decision tree also provided readable decision rules based on game features.


✅ Conclusion

Key Insights:
- Victory by resignation is more common than checkmate.
- Rated games tend to be longer on average.
- Higher player ratings slightly correlate with win probability.
- Most popular openings show a tactical preference among players.
- ML models can reliably predict the winner with just a few game stats.

This project combines data science and chess to uncover patterns and build predictive tools that could assist in gameplay analysis or educational tools for players.

