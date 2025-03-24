# Using SQL in Python 

This is a PyLadies LA meetup material on how to use SQL in Python.
Hosted at USC by Annie Flippo. https://www.meetup.com/pyladies-la/events/306728785/

## Introduction

Why would you use SQL with Python? Why not just use SQL in the database and retrieve the data you need?

There are many reasons you might like to run SQL within Python:  

1. __Convenience__: Perhaps you ran a super long query that reduced the data set to a manageable size to work with.  It's a hassle to re-run the query in the numerous databases just to apply a simple filter.

2. __Easy to Use__: Why don't you just subset the dataframe instead of using SQL? Have you tried to subset a dataframe then apply an aggregation while applying a filter? I bet you'll get frustrated doing it and will probably have to ask an AI co-pilot to help you. SQL is super flexible and quite intuitive to read. 

3. __No Internet__: Maybe you're traveling on a plane or at a coffee shop where the wifi has low bandwidth, you don't want to query a live database right at this moment but you already have the data locally in a csv file to work with.  Just apply your quick SQL on your dataset and finish your task quickly.

Hope I've convinced you that it's a good skill to have.  Let's get going.

## 1. Google Colab

There is a Google Colab Notebook for this workshop:
https://colab.research.google.com/drive/1TkafYQE0vhgTzUY7TIaFdW8DzcmdFZrU?usp=sharing 

or, here at __PyladiesLA_using_SQL_in_Python_colab.ipynb__

Solution key is not provided in this repo 😅

## 2. SQL in Python Notebook

In this repo, you will find __SQL_Dataframe_Notebook.ipynb__.
The pre-requisites to running this notebook are:

1. You have a local python environment (i.e. Anaconda, mini-Conda or venv)
2. Python 3.9 or higher
3. You have Pandas and SQLite3 packages installed

    Conda: <br>
    &nbsp; &nbsp; &nbsp; - conda install conda-forge::pandas <br>
    &nbsp; &nbsp; &nbsp; - Jupyter Notebook or appropriate plugin in VS Code (or your IDE of choice)

    Venv: <br>
    &nbsp; &nbsp; &nbsp; - pip install pandas
    
Note: You don't need to install sqlite3 module. It is included in the standard library (since Python 2.5)

If you want to learn more about the capabilities of SQLite3 check out: https://docs.python.org/3/library/sqlite3.html

## 3. Advanced SQL for Interview Question

See: employee_salary_window_function_pyladies.sql <br>
Use https://www.db-fiddle.com/ using the latest PostgreSQL version to answer the questions.