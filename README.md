# Tableau Project for COVID

## Project Description
For all intensive purposes this project is to specifially setup Excel files needed to use Tableau to show the results of the project from the COVID Database from [SQL-Data-Exportation-COVID-using-Python](https://github.com/JChrisWolfe/SQL-Data-Exportation-COVID-using-Python).The results of the information for the data can be viewed on Tableau's website for [James C. Wolfe](https://public.tableau.com/app/profile/james.c.wolfe).

## Required Software and Modules
For this project Jupyter was used via Anaconda. This would insure that you'd have all the necessary software and even modules are installed to use the project files. In addition depanding on the Operating System you are using you are going to want to install modules with Conda via the command line prompt:

<ul>
  <li><code>conda install -c anaconda sqlite</code></li>
  <li><code>conda install -c anaconda sqlalchemy</code></li>
</ul>

Then add the following modules to your Python Code:

<ul>
  <li><code>import pandas as pd</code></li>
  <li><code>import sqlite3</code></li>
  <li><code>from sqlalchemy import create_engine</code></li>
</ul>

## Run the Notebook using Jupyter
All that is required once you've installed the necessary software and modules is to only run this Jupyter Python Notebook is to just startup Jupyter alone or using the Anaconda Software. This project was created on a Windows 10 Operating System using Anaconda.

# Where to Start
`COVID-19 Data SQL Results to Excel.ipynb` is the file used to create the Excel files needed for the result of [COVID Covid Dashboard using Tableau](https://public.tableau.com/app/profile/james.c.wolfe/viz/CovidDashboard_16465109164560/Dashboard1). If you have SQLite installed on your PC, you can investigate the `COVID_DB.db` database that was used to create the Dashboard for this project.
