**Summary:**
Used Python and SQLAlchemy to do basic climate analysis and data exploration of climate database. 

**Climate Analysis and Exploration:**
- Performed percipitation analysis by finding the most recent date in the data set. Using this date,  I retrieved the last 12 months 
of precipitation data by querying the 12 preceding months of data. I selected only the date and prcp values, and loaded the query 
results into a Pandas DataFrame and set the index to the date column. I sorted the DataFrame values by date and plotted the results 
using the DataFrame plot method.
- Performed a station analysis by designing a query to calculate the total number of stations in the dataset. Designed a query to 
find the most active stations and proceeded to list the stations and observation counts in descending order, finding the station id 
that has the highest number of observations, and calculated the lowest, highest, and average temperature using the most active station
id. Designed a query to retrieve the last 12 months of temperature observation data (TOBS) by filtering by the station with the 
highest number of observations, queried the last 12 months of temperature observation data for this station, and plotted the results 
as a histogram (with bins=12).

**Climate App:**
- Designed a FLASK API based in the above queries
