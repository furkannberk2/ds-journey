Titanic EDA
Exploratory data analysis on the Titanic passenger dataset. The goal was to understand which factors influenced survival — not to build a model, just to ask questions of the data and let the visualizations answer them.

What I looked at

Overall survival rate and its distribution
How survival varied by sex, passenger class, and age
Missing data — where it was, how much, and how I handled it
Correlations between numerical features

Key findings
Women survived at nearly 3x the rate of men. First-class passengers survived at roughly double the rate of third-class. Children under 10 had noticeably higher survival rates than adults. Passenger class and sex turned out to be the two strongest predictors — which tracks with the "women and children first" evacuation policy.
What I used
Python · Pandas · Matplotlib · Seaborn
What I learned
Handling missing data isn't one-size-fits-all. Age (~20% missing) was filled using per-class median rather than the overall median. Cabin (~77% missing) was dropped entirely. Embarked (2 rows) was filled with the mode. Each decision was different because the situation was different.
