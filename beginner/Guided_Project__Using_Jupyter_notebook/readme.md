## U.S. Births

This folder contains data behind the story [Some People Are Too Superstitious To Have A Baby On Friday The 13th](http://fivethirtyeight.com/features/some-people-are-too-superstitious-to-have-a-baby-on-friday-the-13th/).

There are two files:

`US_births_1994-2003_CDC_NCHS.csv` contains U.S. births data for the years 1994 to 2003, as provided by the Centers for Disease Control and Prevention's National Center for Health Statistics.

`US_births_2000-2014_SSA.csv` contains U.S. births data for the years 2000 to 2014, as provided by the Social Security Administration.

Both files have the following structure:

Header | Definition
---|---------
`year` | Year
`month` | Month
`date_of_month` | Day number of the month
`day_of_week` | Day of week, where 1 is Monday and 7 is Sunday
`births` | Number of births


- `year` - Year

Instructions

Run all of the existing cells in the notebook.
In a new code cell, add code that returns a dictionary containing the total number of births for each unique day of the week.
The result should be a dictionary where the keys are the unique day_of_week values and the associated values are the total number of births. Here's how the dictionary should be formatted:
days_counts = {
    0: 10000,
    1: 10000,
    2: 10000,
    ...
}
Here are the steps:
Create an empty dictionary,
Select all but the header row and assign to a new list object,
Iterate through this new list,
Split each line on the comma delimiter,
Extract the day_of_week value and the births value for each line,
If the day_of_week value already exists as a key in the dictionary, add the births value to the existing, associated value.
If the day_of_week value doesn't exist as a key, add it to the dictionary and set the associated value to the births value for that line.
Outside the loop, display the dictionary.
If you run into any errors, edit this existing code cell and iterate on the code until your code works properly. In the last step of this guided project, we've added a link to the solutions.
