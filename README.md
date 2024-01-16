# NFL2024DataBowl_Kaggle
Code and data used for the Kaggle 2024 NFL Data Bowl Competition

Link to the competition information page: https://www.kaggle.com/competitions/nfl-big-data-bowl-2024

Link to datasets that were provided: https://www.kaggle.com/competitions/nfl-big-data-bowl-2024/data

Link to my competition submission: https://www.kaggle.com/code/neilgulati/nfl2024databowlsubmission-neilgulatitomkoch

In the notebook that was submitted all code and a writeup is included.

The goal was to generate actionable insights from a coaching perspective with an emphasis on tackling. For each frame of each play, I performed clustering methods and analyzed the concentration of offensive and defensive players within a cluster around the ball over time. Additionally, I developed new metrics such as snap-to-tackle time, average tackler acceleration, and average tackler speed. 

Using the data, I created an XGBoost model, Random Forest model, and Neural Network for each offensive formation. From there, I found for a given formation approximately how long the QB had to throw the ball. 
