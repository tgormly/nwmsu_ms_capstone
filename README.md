# Tim Gormly
## MS Data Analysis - Capstone Project
<strong>Email:</strong> tim.gormly@gmail.com

[Link to Overleaf Report](https://www.overleaf.com/read/qgdzxhsjpvdg#9be92b)
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
<li>Bronze_Data_Layer.ipynb</li>
<li>Silver_Data_Layer.ipynb</li>
<li>Gold_Data_Layer.ipynb</li>
</ol>

After Gold_Data_Layer.ipynb has ran and Data/Gold/main.csv has been created, other notebooks can be ran.