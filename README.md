# Amazon Product Reommendation System

## Project overview:
I analyzed an Amazon product database to build recommendation models using 4 different methods: Rank-based using averages, User-user similarity-based collaborative filtering, Item-item similarity-based collaborative filtering, and Model-based (matrix factorization) collaborative filtering.

## Installation and setup:
- Language: Python 3.11.5
- Environment: Google colab (Jupyter Notebook)
- Other dependencies: Other dependencies were installed in the Jupyter notebook (including numpy, pandas, scikit, seaborn, matplotlib).

## Data
 - Information regarding the data is inside the Jupyter notebook, and a data dictionary written by the dataset’s creator is in the beginning of the notebook.

## Code structure:
- Begins with an overview of the Amazon dataset and the goal of the program.
- This is followed by installing necessary dependencies and loading in the dataset.
- I then get a better understanding of the data before doing exploratory data analysis, using primarily univariate analysis to discover patterns or trends. 
- I then make the classification models, and try to optimize each.
- I end it with a conclusion and possible future steps.

## Results and Evaluations
- I found that the optimized matrix factorization was the most impactful succesful model, with an RMSE of 0.9856 and an F1-score of ~0.64. To create better results, a more complex model maybe integrating multiple methods could be a next step in improving the recommendation metrics.
