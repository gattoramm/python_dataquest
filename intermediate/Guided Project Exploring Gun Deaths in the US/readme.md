In this project, you'll be working with Jupyter notebook, and analyzing data on gun deaths in the US. By the end, you'll have a notebook that you can add to your portfolio or build on top of on your own. If you need help at any point, you can consult our solution notebook [here](https://github.com/dataquestio/solutions/blob/master/Mission218Solution.ipynb).

The dataset came from [FiveThirtyEight](https://www.fivethirtyeight.com/), and can be found [here](https://github.com/fivethirtyeight/guns-data). The dataset is stored in the guns.csv file. It contains information on gun deaths in the US from 2012 to 2014. Each row in the dataset represents a single fatality. The columns contain demographic and other information about the victim. Here are the first few rows of the dataset:

№ | year | month | intent | police | sex | age | race | hispanic | place | education
---|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------
`1` | 2012 | 1 | Suicide | 0 | M | 34.0 | Asian/Pacific Islander | 100 | Home | 4.0
`2` | 2012 | 1 | Suicide | 0 | F | 21.0 | White | 100 | Street | 3.0
`3` | 2012 | 1 | Suicide | 0 | M | 60.0 | White | 100 | Other specified | 4.0
`4` | 2012 | 1 | Suicide | 0 | M | 64.0 | White | 100 | Home | 4.0
`5` | 2012 | 1 | Suicide | 0 | M | 31.0 | White | 100 | Other specified | 2.0

As you can see above, the first row of the data is a header row, which tells you what kind of data is in each column of the CSV file. Each row contains information about the fatality, and the victim. Here's an explanation of each column:

- `№` -- this is an identifier column, which contains the row number. It's common in CSV files to include a unique identifier for each row, but we can ignore it in this analysis.
