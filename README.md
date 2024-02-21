# project 7 Predictive Analytics 

# Datafun-07-applied

**overview**

*Project Purpose*
To implement the guided projects in 10.16 and 15.4 of textbook:
**Intro to Python for Computer Science and Data Science:** Learning to Program with AI, Big Data and the Cloud.

Our Project 7 is a guided project on machine learning. At a high-level, supervised learning has been employed also simple linear regression, to train a model and use the resulting model (a "best-fit" straight line) to make predictions. .

# Objective

 * Build a model
 * Make predictions
 * Visualize the model
 * Publish insights

# Environment setup

 Create new repository in github name: Datafun-07-applied

 # Clone repository to local with git

 `git clone https://github.com/Priyankanaskar/Datafun-07-applied`

# create virtual env with .venv

`python3 -m venv .venv`

# activate virtual environment

` source .venv/bin/activate`

# Deliverable Names
 GitHub Repository: Datafun-07-applied

 Documentation: README.md

 requirements.txt

# External Dependencies imported

  Virtual environment created and activated
  
# Install dependencies into your .venv and freeze into your requirements.txt.
`pip install pandas`

`pip install pyarrow`

`pip install scipy`

`pip install seaborn`

`pip install matplotlib`

`pip install scikit-learn`

`pip freeze > requirements.txt`

`git add `.

`git commit -m "initial commit"`

`git push origin main`

# Project Organization & Data Files

* Access and download associated files and data from *IntroToPython/examples*
* Create *data* subfolder in the root project repository folder.
* Add downloaded associated files and data to the data subfolder.

# Start the Project

* Open datafun-07-applied root project repository in VS code.
* Open a terminal in your root project repository folder and run.
* Create new notebook in root project repository named: priyanka_ml.ipynb
* Add Markdown cell at the top of new notebook with Title, Author, and clickable link to project repository.
* Add Python cell with import statements.

# Import dependencies

`import matplotlib`

`from matplotlib import pyplot as plt`

`import pandas`

`import pyarrow`

`import scipy`

`from scipy import stats`

`import seaborn as sns`

`import sklearn`

`from sklearn.model_selection import train_test_split`

`import numpy as np`

# Project Analysis

 ## Project 1

**Part-1. Chart a Straight Line** 

* Add a Markdown heading for Part 1 - Chart a Straight Line.
* Follow the instructions from 10.16 (starting page 414).
* Use Markdown cells to create section headings as you work. 
* Use pandas DataFrames to plot Celsius vs Fahrenheit .
* Refresh your understanding of the equation for a line(y = mx + b)and be familiar with the use of:
*m = the slope of the line (rise over run or delta y over delta x)*
*b = the y-intercept of the line (where the straight line crosses the y axis)*
* Git add / commit / push changes to GitHub.

**Part-2. Predict Avg High Temp in NYC in January**

*Use Linear Regression on Average High Temperatures in NYC in January.*

* 1 - Data Acquisition.
* 2 - Data Inspection.
* 3 - Data Cleaning.
* 4 - Descriptive Statistics.
* 5 - Build the Model.
* 6 - Predict.
* 7 - Visualizations.
* Git add / commit / push changes to GitHub.

# Part-3. Predict Avg High Temp in NYC in January 

* 1. Build the Mode.
* 2. Test the Model.
* 3. Predict.
* 4. Visualization.
* Git add / commit / push changes to GitHub.

# Part-4. Insights 

* 1. Complete section per Project 7 requirements.
* 2. Publish insights.
* Git add / commit / push changes to GitHub.

# Optional Bonus Project

## California Housing Dataset

*Complete section per Project 7 requirements*

* 1. Loading the data.
* 2. Training and testing the data.
* 3. Visualizing the data.
* 4. Choosing the best model from the 4 listed.
* Git add / commit / push changes to GitHub.

# Contributing:

You are welcome contributions to this project. If you have suggestions to improve the analysis or encounter issues, please open an issue or submit a pull request.

# References & Acknowledgments:

*Guided projects in 10.16 and 15.4 of textbook:* Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud.

Special thanks to *OpenAI* for assistance with project design and coding structure.

Additional references used for this project include: 

*JUPYTER.md* for Jupyter Notebook keyboard shortcuts and recommendations.

*MARKDOWN.md* for Markdown syntax and recommendations.

*Data Visualization* using Python, Matplotlib and Seaborn for visualization project ideas.

*Seaborn Tutorial* for assistance with plotting functions.

*Linear Regression* in Python using Jupyter Notebooks! to create forecasting projections.

*3D Scatter* Plots in Python to create 3D scatter plots.

A special thanks to **Dr.Case** for guiding this projects.