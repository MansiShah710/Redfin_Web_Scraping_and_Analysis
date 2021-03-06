# Problem Description
This project was aimed at collecting real estate data from the Redfin website by web scraping and doing visualization and analysis on this data. Further, I had to build a linear regression model to predict the sale price of a property.

# Python Libraries used
- BeautifulSoup (for scraping)
- Seaborn
- matplotlib
- RE
- Sklearn (Linear Regression)

# Web scraping
Data was collected for various California counties by scraping the Redfin website for sold houses and new listings. The type of data collected includes the basic data of the house (beds, baths, area, price, etc) and some advanced data as well like type of property, schools in the area, walking and biking convenience, etc.

Thia data was then cleaned to make it ready for analysis. There are more then 200 property types available of Redfin and those were put into 8 distinct classes (Single family home, Townhouse, etc). Redundant data was removed. Missing data was treated properly.

# Analysis
Seaborn and Matplotlib were used to do visualization of the data. The visualization gave some very good information about the trends we see with respect to the type of property. For instance, we see that Townhouses are very famous in the bay area, especially San Francisco. This is because there is not enough land available there to build new houses.

There was other analysis done as well using property type and other fields.

# Linear Regression
A multi linear regression model was built to predict the price of houses in Solano county. This was then compared with the actual sale price of the house. The model was able to explain 85% of variation in the sale price of the house.
