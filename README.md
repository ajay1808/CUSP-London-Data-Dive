# CUSP-London-Data-Dive

## Walking the City: Analysis of the Built Environment on Mental Health in NYC

### Team Members:
- Akshay Shetty - as16477@nyu.edu
- Shantanu Anikhindi - saa9213@nyu.edu
- Ajayrangan Kasturirangan - ak10196@nyu.edu
- Maria Lucia Cornejo Quenaya - mlc9958@nyu.edu
- Vickram Peter - vp2379@nyu.edu
- Sharvari Deshpande - sd5270@nyu.edu
- Anshika Gupta - anshika.gupta@nyu.edu

## Abstract
The relationship between the built environment and mental health has been a topic of growing interest in urban research. In this study, the impact of six different metrics of the built environment on walkability and mental health in New York City (NYC) is investigated. Specifically, the presence of trees on the streets, restaurants in the areas, street lights, building height, smoke shops, and liquor shops in the streets are examined. The hypothesis is that a more walkable city improves mental health, and the aim is to identify which metrics have the most significant influence. The results provide insights into how specific metrics of the built environment can impact mental health and walkability in urban settings. These findings could inform policies aimed at promoting a more walkable and mentally healthy city in NYC and beyond.
Background and Motivation
Urbanization has led to a rise in the number of people living in cities. The built environment of cities, which includes the physical structures, streets, parks, and other public spaces, plays a critical role in the health and well-being of city residents. The relationship between the built environment and mental health has been a topic of growing interest in urban research. Previous studies have suggested that the built environment can influence mental health outcomes through various mechanisms, including social interaction, physical activity, and exposure to nature.
Walkability, which refers to the extent to which a city or neighborhood is designed to facilitate walking, has emerged as an important aspect of the built environment that can influence mental health. A walkable city or neighborhood is one that is designed with features such as well-maintained sidewalks, street lighting, and easy access to shops and services. Research has shown that walkable neighborhoods can increase physical activity, social interaction, and access to nature, all of which are associated with better mental health outcomes.
New York City is a highly urbanized city with a diverse population. Walking is a common mode of transportation in NYC, and many residents explore the city on foot. However, the city's built environment varies widely across neighborhoods, with some areas having more walkable features than others. Therefore, understanding the impact of specific built environment metrics on walkability and mental health in NYC can inform policies aimed at promoting a more walkable and mentally healthy city.

## Data Collection And Datasets
*Trees* - Street-Tree-Census-Tree-Data 
The dataset available at the given link contains information on the trees in New York City collected during the 2015 Street Tree Census conducted by the Department of Parks and Recreation. It includes data on the species, diameter, condition, and location of trees on the streets, sidewalks, and other public areas throughout the city. 

*Restaurants* - DOHMH-New-York-City-Restaurant-Inspection-Results 
The DOHMH New York City Restaurant Inspection Results dataset provides restaurant inspection scores and violation details for over 25,000 food establishments in New York City. The dataset includes the restaurant name, address, cuisine type, inspection date, score, grade, and violations found during the inspection.

*Sunlight* - Project Sunroof: Estimated Rooftop Solar Potential
The map displays the amount of sunlight that hits rooftops in the selected area, as well as the estimated energy output of installing solar panels on those rooftops. The data is based on a number of factors, such as weather patterns, roof orientation and shading, and the amount of available space for solar panels.

*Building height* - Building Footprints Data 
Shapefile of footprint outlines of buildings in New York City. The data includes information on over one million buildings across the five boroughs of New York City. 

*Smoke Shops* - Active Tobacco Retailer Map
This map is a listing of active retail tobacco vendors.This data includes the name, subcategory, and location of active retail tobacco vendors operating in New York State. Subcategory includes the type of retail tobacco vendor, such as a convenience store or a grocery supermarket. Address includes the street address, city, state, zip code, municipality, and county where the vendor is located. 

*Liquor Shops* - Liquor-Authority-Current-List-of-Active-Licenses 
This dataset contains information on all active liquor licenses in the state of New York. The data includes the license type (e.g. on-premises, off-premises, manufacturing), the name and address of the licensed business, the license number, and the date of the license issue. 

*Sidewalk Width* - Sidewalk | NYC Open Data
This dataset contains information on sidewalks throughout the five boroughs of New York City. The data includes the location and condition of sidewalks, as well as any associated defects or violations. The dataset also includes information on permits for sidewalk construction or maintenance, as well as inspections and complaints related to sidewalks.
NYC-Street-Centerline
This dataset contains the geographic locations and attributes of streets, highways, and alleys in New York City. The data includes information on street names, addresses, traffic directions, and block numbers. It also includes geographic coordinates for each street segment and associated information such as the number of lanes, speed limits, and bus routes.

*Sidewalk and Street Lights Complaints* - 311 Service Requests | NYC Open Data 
The dataset contains service requests that are categorized into street light issues, and other non-emergency problems that require the attention of a city agency.   The dataset is updated daily and provides detailed information about the service requests, including the date and time of the request, the location of the request, the type of service requested, and the agency responsible for fulfilling the request. 


## Current state of NYC

Walking 
- According to the New York City Department of Transportation, over 1 million New Yorkers walk to work every day.
- The average New Yorker walks for about 22 minutes a day
- The most walkable neighborhoods in NYC, according to Walk Score, are Chinatown, Little Italy, and Soho.
- Walk Score, a website that rates and ranks the walkability of cities, reports that 141 cities in the United States have an average score of 48 out of 100.
- NYC has a walkability score of 88.

Mental health
- One in five New Yorkers are likely to experience a mental health disorder in any given year
- According to a NYC Health Opinion Poll, 25% of NYC adults reported symptoms of anxiety and 18% reported symptoms of depression in August 2021.
- Approximately 8% of adult New Yorkers experience symptoms of depression each year.
- 25.6% of all healthcare expenditures involve patients with mental illness.
- Alcohol misuse is estimated to cost NYC nearly $6 billion in citywide economic productivity losses every year, while depression accounts for $2.4 billion
- 27% public high school students reported feeling sad or hopeless
- An estimated 7,000 emergency room visits each year in NYC involve alcohol use among individuals under 21 years of age.


Maps and Charts
Source: https://thrivenyc.cityofnewyork.us/wp-content/uploads/2019/08/Thrive-Roadmap.pdf
Kepler: https://kepler.gl/demo/map?mapUrl=https://dl.dropboxusercontent.com/s/fpxmxqxjujxrafy/keplergl_4ciz9e.json

When we were first approached with the question of mental health, especially in our city of New York, our team unanimously pondered upon the belief that the experience of walking in the city impacted all of us in varying amounts. We wanted to find out how walking (in a world where walkable cities is a buzz-word) affects the mental health of a citizen?

But what is walking in the city? We decided to explore a couple of proxy factors to numerically depict our experiences. 

We chose these crucial factors because we believe these affect the experience of a pedestrian walking through the city.


How much does the built environment affect the mental health of the citizens in the neighborhood? 

And now, what is Mental Health? Akshay will now answer this along with the data processing pipeline


- DATA PROCESS CYCLE EXPLANATION AND LIMITATIONS:
Start.

While we lacked sufficient volume of Mental Health data in NYC, we decided to source our info straight from a government health survey to figure out the sampling. (Speak about it).
Explain what Emotionally Distressed People
To confirm the belief, we run the correlation against a factor called EDP.

As they say, 90% of the data science project is just data engineering.
The data comes from a huge range of sources. We needed to standardize all of it effectively such that our regression and clustering models would be easy to apply. Here are the 4 steps of the entire data engineering process.

Data Collection ->  From Open NYC predominantly.
Normalization -> Per-Capita level for normalization. Average for variables such as height.
We then normalized across the entire column with mean set 0 and variance set to 1.
Now that we have this one massive merged dataset, we could run two of the processes -> REGRESSION and CLUSTERING.

We’ve ensured that the data is now spatially weighted by  (based upon population).

-> [DISCUSS the additional datasets (the plotting of the individual regressor if needed).

We must take a moment here to mention that while this is the best source we could find openly and in the given time for this data project, we understand that there may be bias that slips into the data based on reporting. An example is the 311 (an equivalent of 101) database where socio-spatial and racial disparities can creep into decision-making. (Give an example if you want!).

Now that we’ve showcased the data processing to ensure our data is as accurate as possible, we decided to run two programs: 
Regression of the built environment as variables and the EDP call numbers as output (as a proxy for mental health).
Clustering of the built environment variables and seeing what it tells us in an unsupervised perspective.

- REGRESSION AND CLUSTERING
Here are the results that we’d like to discuss.

Regression: Upon regressing the built environment factors, here were our results:

Those which correlated with increased calls in the area: Smoke Shops, Restaurants, Higher Sidewalk Width and Trees, seem to indicate places with higher activity or mobility.

Those which correlated with decreased calls in the area: Street Light condition Complaints, Sidewalk Condition Complaints and Average Height of building. These indicate areas where most complaints are registered and hence more likely to have repair work. Higher height of buildings tend to be associated with lesser 911 calls.

When we thought about it, we realized that those which increased calls are related to higher activity and it was the opposite for those which reduced calls.

It seemed to us that areas of high activity were contributing to an increased number of 911 calls.

Clustering: 

We clustered the zip codes based on the built environment variables and here are the three clusters we observed.
Cluster 0: Seems to be outliers and away from the city centers.
Cluster 1: Seems to be the suburbs and non-manhattan area.
Cluster 2: Seems to be downtown and high income areas and includes Manhattan (considered the city center).

While this did not have any strong correlation with the EDP call distribution, we made an additional inference that the build environment cluster seemed to resemble the income-based clustering of NYC. This shows that the built environment is a function of the income-level of a zip code.

- Additional Inferences and Future Work:

Here are the additional steps we recommend:

Regression: We realized that the variables which contributed to an increase in 911 calls of EDP scenarios seemed to be those which are related to high activity. As a potential next step we suggest going deeper into the subject.

Clustering: If more socio-spatially accurate and granular mental health data was available, we would investigate to see how the clustered areas of different built environments (which are also a function of the income and socioeconomic factors) affect the cases and prevalence. This data could help us make civic decisions as per the allocation of resources which may both directly and indirectly affect the improvement of mental health in the city.

Time Series Analysis: We can further explore how the advances in the built urban environment over the years impacted the mental health cases. Whether there was a significant impact from specific events like new built environment construction or the pandemic for example.

## Conclusion
In conclusion, the built environment has a significant impact on the mental health of individuals in New York City. Our analysis of the different aspects of the built environment such as the presence of trees, restaurants, street lights, sunlight, building height, smoke shops, liquor shops, sidewalk width, and sidewalk complaints show that these factors play an important role in the walkability of the city, which is a key determinant of mental health outcomes. Our study reveals that a more walkable city, characterized by well-maintained and spacious sidewalks, street cafes, greenery, adequate lighting, and points of interest, can lead to improved mental health outcomes. Overall, our study highlights the need for city planners and policymakers to prioritize the creation of a more walkable city, with a focus on improving the built environment and enhancing the conditions that contribute to positive mental health outcomes. By taking these steps, we can create a healthier and more vibrant city for all New Yorkers.

Hence, we have showcased the possible links, their contribution, and the direction for the future of resources towards building environments so that we can ensure the city is developed in a way that walking in it benefits the mental health of all of its citizens.
