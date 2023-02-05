# Plotly-Python
Produced interactive data visualizations with Plotly Python.  Used Plotly Python and Seaborn during EDA and feature engineering.


Task 1: Analyzing Movie Release Dates

In Part 1, we focused on exploratory data analysis. In this task, we identify the release_date column as ripe for feature engineering.

Task 2: Preprocessing Features

Before we can create new features based on release_date, we need to define a function to process the dates and convert them to a standard datetime format. 

Perform data imputation to account for missing values, after which we will apply our processing on the training and test sets.

Task 3: Create Features Based on Release Date

Now that we have standardized the date format, define a function to create new columns for the year, weekday, month, week of the year, day, and quarter. 

Task 4: Using Plotly to Visualize the Number of Films Per Year

We will use Plotly to create an interactive visualization of the number of films released per year in both the training and test sets.   

We use the generic go.Scatter function from plotly.graph_objects, and specify the mode argument to choose between markers or lines. 

Task 5: Number of Films and Revenue Per Year

In this task, we will visualize both the number of films and total revenue per year, and the number of films vs the average revenue per year. 

We will be able to compare and contrast trends we observe to that of the previous task.

Task 6: Do Release Days Impact Revenue?

Is it reasonable to assume that movies released on weekends will gross higher revenues? 

Let's put this assumption to the test in this task by creating a categorical plot of the day of the week on the x-axis and revenue on the y-axis. 

Are you surprised by the results? Why or why not?

Task 7: Relationship between Runtime and Revenue

We will create two plots in this task. The first describes the distribution of the duration of films. The second plots revenue against duration. Let's find out if the data illustrates the optimal duration of a movie to maximize revenue.
