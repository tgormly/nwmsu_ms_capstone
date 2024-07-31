# Tim Gormly
## MS Data Analysis - Capstone Project
<strong>Email:</strong> tim.gormly@gmail.com

<strong>Overleaf Report:</strong>[https://www.overleaf.com/read/qgdzxhsjpvdg#9be92b](https://www.overleaf.com/read/qgdzxhsjpvdg#9be92b)
<hr>

# National Ties: Exploring Team Composition and Player Success

What is the impact of having multiple teammates who share your nationality? This repo explores data found in the Professional Hockey Database to see if having a greater number of teammates who share a player's birth country will have an impact on that player's personal performance.

<hr>

## Managing Project Environment
A valid installation of Python is required. This repo was developed on Python 3.11.9. Creating and using a virtual environment is recommended. Instructions below are for Windows users.

To create a virtual environment, run this command in your project terminal:
~~~
python -m venv venv
~~~

To activate the environment, run this command:
~~~
venv\Scripts\activate
~~~

To install dependencies, run:
~~~
pip install -r requirements.txt
~~~

## Creating Dataset
Once your project environment has been created, you will need to create the dataset. You can do this by running the following jupyter notebooks in order:
<ol>
<li><a href="Bronze_Data_Layer.ipynb">Bronze_Data_Layer.ipynb</a></li>
<li><a href="Silver_Data_Layer.ipynb">Silver_Data_Layer.ipynb</a></li>
<li><a href="Gold_Data_Layer.ipynb">Gold_Data_Layer.ipynb</a></li>
</ol>

After Gold_Data_Layer.ipynb has ran and Data/Gold/main.csv has been created, other notebooks can be ran.

## Exploratory Data Analysis
<a href="Exploratory_Data_Analysis.ipynb">Exploratory_Data_Analysis.ipynb</a> will create several new features, and then provide exploratory analysis focusing on input features and target variables.

Exploratory data analysis reveals no real correlation between the number of teammates who share a player's nationality and that player's performance.

## Machine Learning Analysis
Because of the lack of evidence supporting a linear correlation between teammates with the same nationality and player performance, Random Forest analysis is used. Three different target variables were predicted for in three different notebooks:
<ol>
<li><a href="ML_Performance_Score.ipynb">Player Performance Score</a></li>
<li><a href="ML_Stint_VS_Prev_Sint.ipynb">Stint Performance vs Previous Stint Performance</a></li>
<li><a href="ML_PIM_VS_Prev_Stint.ipynb">Penalty Minutes vs Previous Stint</a></li>
</ol>

