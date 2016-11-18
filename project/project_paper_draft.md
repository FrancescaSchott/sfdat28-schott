##SFDat28_Course Project

###Three Potential Questions

###1. Rail, Bus and Auto Transportation

#####What
Examine and predict auto traffic patterns on any given day based on rail and bus transportation data from the Denver Regional Transportation District's [University of Colorado A Line Commuter Rail](http://www.rtd-denver.com/a-line.shtml)

#####How
Compare commute data from the Denver Regional Transportation District (bus and rail data) and the Colorado Department of Transportation (auto traffic data) to try and predict auto traffic patterns. Using inputs such as day of the week, time of day, number of commuters on either the rail line or bus, and weather patterns, I want to try and predict what the auto traffic may be given certain conditions.

To begin with, data sources should be accessible at the following locations:

  * [Denver Regional Transportation District](http://www.rtd-denver.com/Developer.shtml) *(Ridership counts may not be available, but I will email RTD if needed to determine what data is available.)*
  * [Colorado Department of Transportation](http://dtdapps.coloradodot.info/otis)
  * [Historical Weather](http://apidev.accuweather.com/developers/) *(I think I can get free access to this API. If not, I will do more research to identify a free historical weather API.)*

#####Why
Initially I wanted to build a model specifically for the Sonoma-Marin Area Rail Transit (SMART) system being implemented in the North Bay Area. In the past few weeks, SMART has announced a delay in its scheduled launch date due to technical difficulties ([Press Democrat - 10/13/16](http://www.pressdemocrat.com/news/6189496-181/sonoma-marin-area-rail-transit-struggling)).

With this SMART development and several references in recent articles to a newly opened commuter line between downtown Denver and the Denver International Airport, I am choosing to use the Denver region as a study area instead. If this project is chosen, and successful, I hope it is replicable for SMART in the future.


###2. Ulia's Delicatessen Sales

#####What
Ulia's Delicatessen is owned by my boyfriend's family and has two locations, one in Santa Rosa, CA and one in Petaluma, CA. They use the Square POS system and I am able to access their Square account for daily sales data. I would like to export historical daily sales data to try and predict customer purchases based on day, time, location, weather, and new versus returning customer. 

#####How 
Using the login information, I should easily be able to pull historical sales data. Beyond that, I may need to find historical weather data, likely from the same source listed in the third bullet point above.


#####Why
The Ulia's Delicatessen owner is interested in using the Square POS system more effectively and robustly to help increase sales. This project is a potential starting point to determine who buys what and when. In the future, this project could be expanded to guide the methodology for offering promotional deals through email, implementing instant rewards for frequent customers, or monitoring sales based on employee. 

**Oh**, I also eat there for free most days, and it's an opportunity to stay in the good graces of my future in-laws **:)**


###3. New Business Success

#####What
Predict if a new business will still be running five years after starting in Santa Rosa, CA.

#####How
Extensively clean business data from the City of Santa Rosa, the County of Sonoma, and other possible sources to try and predict if a new business will still. Possible testing parameters will be location (geographical and/or zoning), industry, number of employees at start up (if data exists), and whether the owner is brand new business or expanding their company.

The following data sources and/or resources will likely be used or accessed:

  * [County of Sonoma Fictitious Business Names](https://crarecords.sonomacounty.ca.gov/recorder/eagleweb/customSearch.jsp?pageId=OR) *(Working with the Sonoma County Clerks department, I can get complete data on fictitious business name licenses issued. Fictitious business name licenses need to be renewed every five years, so this data set may provide a test set as well.)*
  * [City of Santa Rosa Open Data Portal](https://data.srcity.org/) *(Currently, there does not appear to be any data about businesses posted, but it could be in the pipeline and not yet released. I will reach out to our city contacts to inquire about the data I might need and see if it is available.)*
  * [City of Santa Rosa Business Tax Certificate](http://srcity.org/departments/finance/revenue/businesstax/Pages/default.aspx) *(Unsure if this data is accessible online, but I will email to see if they will provide me with a set of historical data.)*
  * [ESRI]() *(Our office subscribes to ESRI and it may be helpful for visualization of business locations, and potentially a part of the final project as a way to geographically represent areas of business success and failure.)*
  * [EDA with Example Data Set](http://www.city-data.com/business/econ-Santa-Rosa-California.html) *(This data is from 2002, but this is a good starting point to find or generate a more current data set.)* 

#####Why
I work for the Sonoma County Economic Development Board and one function of our department is to assist businesses with their questions and challenges, ultimately allowing them to prosper and grow. This in turn helps support the overall economy of the county.

It would be a unique and valuable tool if our office could confidently predict which businesses succeed and which fail within five years of starting up based on certain parameters.