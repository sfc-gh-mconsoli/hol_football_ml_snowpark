# Football Player Classification
### Hands On Lab : Snowflake & Snowpark | ML - Random Forest Classifier

This project aims to provide an all-in-one Jupyter notebook covering the entire pipeline for football player classification in Snowpark. 

The only step not included in the notebook is downloading the dataset from Kaggle which I recommend doing it directly from the source, it's free and it will take just a few seconds! Download the football dataset [here](https://www.kaggle.com/datasets/davidcariboo/player-scores).

- **Pre-Reqs** are described in the [setup.md](https://github.com/matteo-consoli/hol_football_ml_snowpark/blob/main/setup.md) file. A few steps are required to create a conda env and to install  Jupyter Notebook and required libraries.

- In this Jupyter notebook, we will start from the very beginning, by creating database objects and feature engineering views on Snowflake. 

- Once the data is prepared, we'll use Snowpark to train and test a random forest model to predict the football player's position. 

NOTE: Model accuracy is not the primary goal of this project; instead, it aims to provide a comprehensive, step-by-step example (on a very cool use case).

![Introduction - Design](https://github.com/matteo-consoli/hol_football_ml_snowpark/blob/main/images/design_football_ml.png?raw=true)


Thanks ChatGPT for making markdown so easy <3 

