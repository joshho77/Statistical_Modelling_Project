# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
1. Access and collect web API's containing data related to SoBi bike stations across Hamilton, Ontario. As well as collect data regarding POI's (restaurants, bars, bakeries, etc.) near the associated bike stations
2. Parse, clean, and transform .JSON responses to create relevant and concise DataFrames
3. Create a database, and load DataFames as tables for data validation and storage
5. Undergo EDA, using a data visualization to help describe and interpret the dataset
6. Create a simple linear regression model to outline trends and insights regarding soured data
7. Push results to GitHub to save project and allow for version control

## Process
1. Load CityBikes API for my chosen location (Hamilton, ON), parse .json responses for bike network locations, street names, and total free bikes of the day
2. Load FourSquare and Yelp API's, create function to parse responses for relevant information like restaurant names, addresses, and ratings, then store in respective DataFrames
3. Join DataFrames created from part 1 and part 2, then create a data visualization to plot out points related to the data discovered
4. Create a local database using SQLite to store DataFrames as tables for querying and validation
5. Create a regression model and layout statistical description of the data to understand statistical relationship between variables

## Results
Developed several user defined functions to create DataFrames containing information relevant to the project goal. Resulted in the compiling of hundreds of different places of interests within the Hamilton area, leading to analysis between potential relationships between data points. All in all, was able to effectively identify necessary methods to scrape web API's, and transform, organize and analyze data.

## Challenges 
The greatest challenge I faced was, after creating loops to collect all the URLs with their coordinates as well as accessing their contents in .JSON format, was organizing the information. This was difficult as I wanted to funnel all the relevant information pertaining to the POI's into separate lists, then load those completed lists into a DataFrame. However, this proved difficult as I was trying to create one concise and compact function to do this, and skipped steps that ultimately resulted in errors. In the end, with the knowledge and support of my peers, and many more hours of testing, I was able to come up with a clean and effective solution for exactly what I was searching for!

## Future Goals
To preface, this project was a very versatile assignment, involving everything from data collection and transformation, writing user defined functions, to importing a variety of different libraries (ex. pandas, matplotlib, json). This was all done to perform the exploratory data analysis process via statistics and visuals, which though time consuming, and filled with a great amount of data, was an enjoyable experience that I learned much from. I was able to practice and improve my python skills, think with a data framed mindset, and combine knowledge from the previous weeks (ETL, API's, databases). 

I am curious as to what other ways I could potentially interpret the data. This could involve seeing what other variables I could compare against each other, outlining the statistical measures between them, and also seeing the relationships they may create. Additionally, I would explore further by conducting multiple visualizations during the EDA process. To elaborate, instead of simply using just 1 type of graph (ex. 3d scatter), I would other see if I could incorporate other graphs like a heatmap, bar chart, violin plot or other exciting variations. 
