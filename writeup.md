# MyProject- 
In this project the task is to use the MTA turnstile Data to help a non-profit organization
called ‘The kids are the future’, hand out an event flyer to the summer charity event that they 
are throwing for children with cancer. The organization expect to achieve these goals:

- Getting enough exposure to advertise for the event and the organization work. 
- Target the high-to-medium-income commuters of the subway in New York city.

# The plan in the project is to find:
- What the stations that have a lot of commuters during the morning/noon
period. To determine what are the best places that volunteers can be assigned 
at to distribute the event flyer and advertise for the charity work.
- The stations where people are more likely to donate or attend the event due to economic status.

# The primary data I am going to use in this model is the MTA Turnstile data obtained from the official website:
-  http://web.mta.info/developers/turnstile.html
- Also, I used census data to determine what are the wealthiest neighbourhoods (high household income), in New York city.
-  https://data.cccnewyork.org/data/table/66/median-incomes#66/107/62/a/a
-  The data analyzed are from summer 2019 which is the months from late May through early-mid October, so the months I will collect data from are:
- June, July, August, September of the year 2019.
 
# The approach:
- First, the data was collected and concat it into one CSV file, and then added to the SQL database using SQL3.
- Then, the data was cleaned by searching for null values, in which I found none.
- After that, getting rid of duplicated rows and dropped unnecessary columns. 
- Fixing the counter for cumulative entries and exists was next, after, plotting the data to get a better understanding of the data. 
- Finally, the new set of data loaded for the wealthiest neighbourhoods and connected it to MTA data by matching the stations names.
- Top Ten stations plot:

![Top 10 Busiest Stations in wealthiest NeighborhoodsBarplot](https://user-images.githubusercontent.com/90554959/136706471-b8a5444d-cbc5-4751-aed3-034a6171ae52.PNG)

# My Recommendation:
- Placement of volunteers near the top ten stations during the morning-afternoon period, in these stations:
- GRD CNTRL-42 ST : high income regions around the stations and the 
- 14 ST-UNION SQ: High income and high traffic because of shops, restaurants, cafes and a park
- 59th Street–Columbus Circle is a New York City Subway station complex shared by the IRT Broadway–Seventh Avenue Line and the IND Eighth Avenue Line.
- Chambers St which is located at the Lower Manhattan is full of hotels and the 9/11 memorial site.

# Tools:
- Jupyter
- Git
- Matplotlib
- Seaborn
- Sql
- SQLite
