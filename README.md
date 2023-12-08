# Chess-Data-Analysis
Decoding Chess: Analysis of 20,000 games

Our project explores the game of chess in an effort to identify the underlying patterns, strategies, and variables that have an impact on a game's result. Our project attempts to provide useful insights into winning strategies for both the white and black pieces, while also examining the relationship between particular chess openings and game outcomes, with an emphasis on meeting the needs of casual and beginner-level chess players.

Our process involved loading the dataset from Kaggle using pandas, followed by doing an exploratory data analysis of this raw data and further cleaning it. We did so by excluding irrelevant columns, removing the outliers from various important columns, and excluding "draws" from our games. We also condensed the rating range of our chess games and encoded the categorical column of "opening_name" using One-Hot Encoder. After this, we trained 4 different machine learning models (Logistic Regression, MLP Classifier, Random Forest, and K-Nearest Neighbour) and got the respective accuracies. We used the model with the highest accuracy, which was the Logistic Regression model, and tested the model. Furthermore, we made a data visualization showcasing the win rates of popular chess openings. FInally, we drew results from this analysis process and concluded the project. 

The findings can be useful in selecting chess openings for our target audience, for example some openings like the Italian Game and Scotch Game have higher win rates for the player with the white pieces whilst other openings such as the Sicilian Defense have better win rates for the player using the black pieces. Despite the valuable knowledge gained from our analysis, it is important to acknowledge our limitations including limited dataset size, unequal opening representation, exclusion of draws, and assumption of a single strategy.
