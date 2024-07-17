
**Police Caused Deaths In The United States**

**Description**

The aim of this project was to analyze police caused deaths in the United States. The dataset chosen was police_deaths_538.csv. This dataset had 15,813 rows and 10 columns.

There were no duplicates. There was a NaN value in the state column on row 15812.
The data starts from year 1791. Since the data from the 18th century, and 19th century is not very relevant, as also data from early to mid-twentieth century, all rows where the year was before 1974 were dropped. This modified dataset has 891 rows and 10 columns.

For the number of deaths per state the df['state'] column with value_counts() is considered. The Bar chart using this modified dataframe shows that the three states with the maximum number of deaths were California, Texas and New York.

For the number of deaths per cause the df['cause_short'] with value_counts() is considered. The Bar chart using this modified dataframe shows that the three main causes of death due to the police are gunfire, automobile accident, and vehicular assault.

For the number of deaths due to canines the df['canine'] column with value_counts() is considered. The Bar chart using this modified dataframe shows that very few deaths were caused by canines. In fact, from the dataframe df_canine there are only 5 True values.

The df['weekday'] column is obtained by applying lambda to the df['eow'] column and then applying two splits.
For the number of deaths per weekday, the df['weekday'] column with value_counts() is considered. The Bar chart using this modified dataframe shows that most deaths were on 
Saturday, Friday, Sunday. The least number of deaths were on Tuesday.

The df['month'] column is obtained by applying lambda to the df['eow'] column and then applying two splits.
For the number of deaths per month, the df['month'] column with value_counts() is considered. The Bar chart using this modified dataframe shows that most deaths were in the months of August, January, July, and the least number of deaths were in November.

year_deaths is df['year'] with value_counts(). From the Bar chart, the maximum number of deaths were in 1974

**Usage:**

An .ipynb file called Police Deaths In USA was created in Google Drive and Google Colaboratory. The dataset used is police_deaths_538.csv.
When complete, the .ipynb file can be uploaded to Github by going to File, then Save a copy in Github, name the repository to be uploaded to on Github.
