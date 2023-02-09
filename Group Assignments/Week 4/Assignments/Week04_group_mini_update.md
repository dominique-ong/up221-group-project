# Group Assignment 2 - mini update
### Group: LA Chinatown
### Project Title:  A Look at Gentrification & Development in Chinatown, LA | [proposal](https://github.com/dominique-ong/up221-group-project/blob/main/Group%20Assignments/readme.md)
## Roles
#### Jiaqi
- track the changes of units of residential type and commercial type over 2006-2021. 
- For this week, I have made 5 maps for each type to demonstrate such changes. 
- For next steps, I will take the ‘year built’ into consideration and try mapping these layers altogether.
#### Brian
- Brian is doing a value count of the type of land use within Chinatown. 

He will first see the description provided by the Assessor’s Office and then create a granular map using the subdescription. 
His goal is to look over the data from 2006-2022 with 4-year intervals (2006, 2010, 2014, 2018, 2022). 
Granted there is significant changes in the value counts, he will make a map for each of the 5 years. 
If there is not a significant change, then he will just make 1 or 2 maps that demonstrate the distribution of land use within Chinatown. 
#### Dom
- **Context Research**: Researched key events in Chinatown development timeline

- **RData Hunter-Gatherer**: Gathered ACS data from USC Neighborhood Data for Social Change from 2010-2021; 
Downloaded parcel boundaries, 2006-2022 attribute CSV, and data dictionary from LA GeoHub;
Downloaded 2016-2022 Rent Stabilization Ordinance (RSO) units CSV from LAHD;
Downloaded Ellis Act evictions from LAHD;

- **Data Processing**: Clipped parcel boundaries to Chinatown neighborhood boundary on ArcPro;
Joined the clipped parcel boundaries to 2006-2022 CSV by AIN;
Saved and uploaded the joined parcel geoJSON for each year to GitHub;
Joined 2016-2022 RSO units CSVs to parcel boundaries by AIN, clipped to Chinatown neighborhood boundary;
Saved and uploaded the joined RSO geoJSON for each year to GitHub;

#### Alyssa
Fix geographies and develop a methodology to more efficiently extract census data only from census block groups of interest applied to a temporal analysis from multiple census datasets from different years. 
Using this new methodology, recreate (or fix) maps generated in last week's census exploration assignments.

#### Clara
This week my role was looking at total parcel value and land value in Chinatown over the years 2006-2021. 
I created granular maps showing the price changes over this time period for both total parcel value and land value, and in general it shows that prices have gone up. 
For the data, it may be necessary to adjust prices to 2022 dollars, if it has not been done already. 
I also concatenated all the data together into a large dataframe, in order to create a makeshift histogram for total parcel value. 
I then sorted the data so that each measurement for all fifteen years was put into different buckets. 
From this, I created a stratified bar graph showing how prices have changed in Chinatown during this time period, showing that parcels in general have gotten more expensive over time. 

## Status Update
The team is feeling good at the moment. Craig Wong, member of CCED, provided our team with development data from the LA County/City Assessor’s Office. Having access to the data as well as our general knowledge of accessing publicly accessible data has us feeling like we are in a good position. Our team is excited by the possibilities of our data and hopes that we can create maps that are of use to CCED and other community organizations. 
## Data Update
[UP221 Group Project Data Sources](https://docs.google.com/document/u/0/d/1psbsboagCBajoTB7AinuAQsFTa8C7r6tlgvT4DVSicE/edit)
Our team has found parcel data for Los Angeles from 2006-2021. Each group member is working on a portion of the data and will discuss further investigation in the following weeks.
The ultimate goal is to use this data alone with demographics to show housing/gentrification/displacement of LA Chinatown.

### Major Concerns
Our most pressing concern is that we may be biting more than we can chew. Our team is made up of ambitious community organizers who want to see the best for the ethnic enclaves of Los Angeles. We also plan on continue work similar to this long after this class concludes. That being said, we also recognize that it is already week 5 of the quarter so the final produce we have for this class must fit within the confines of 5 weeks. We recognize that our goals may be more suited for our long-term goals in working with CCED and other community organizations that extend much further than a 10-week course can provide. 
### Minor Concerns
Our minor concern is making sure that we have enough data to complete maps. There is a lot of missing data in some of our data sets, especially as it relates to a temporal analysis. We are cognizant of the fact we may need to pivot over the next few weeks if we see that our research questions do not fit under the confines of the limited data we have. 
