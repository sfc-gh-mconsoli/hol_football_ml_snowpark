# Pre-Reqs: Setting up Conda Environment for the HOL

## Step 1: Install Conda

Make sure you have Conda installed. Download and install Miniconda, a minimal installer for Conda, from [here](https://docs.conda.io/en/latest/miniconda.html).

## Step 2: Create a Conda Environment

Open a terminal and run the following command to create a new Conda environment named "data_env". Replace "data_env" with your preferred environment name.

```bash
conda create --name football_env python=3.8
```
## Step 3: Activate the Environment

Activate the newly created environment:

```bash
conda activate football_env
```

## Step 4: Install Jupyter Notebook

Install Jupyter Notebook within the environment:

```bash
conda install jupyter
```

## Step 5: Install Conda Libraries

Install essential data science libraries like NumPy, Pandas, Matplotlib, and Seaborn, Scikit-Learn

```bash
conda install numpy pandas==2.0.3 matplotlib seaborn scikit-learn
```

## Step 6: Install Snowflake Snowpark

Install the Snowflake connector:

```bash
pip install snowflake-snowpark-python==1.11.1
pip install "snowflake-connector-python[pandas]"
```

## Step 8: Clone / Downlaod the GitHub Repository

If you downloaded this repository already, go to the folder.

## Step 7: Launch Jupyter Notebook

Start Jupyter Notebook within the activated environment. 
Run the command below from the folder you saved the ipynb file.

```bash
jupyter notebook
```

This will open Jupyter Notebook in your default web browser. 
