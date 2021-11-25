# Data Biography

### Declaration of Authorship

I, Junqi Hu, confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

Junqi Hu 

Date of signature: 17/11/2021
Assessment due date: 26/11/2021
Student Number:21052137

---

### 1. Who collected the data?

The data was extracted and compiled by independent researcher Murray Cox [1], who explores the information available at the Airbnb site using python scripts [2].

### 2. Why did they collect it?

Information was collected to quantify the impact of short-term rentals on housing and residential communities. In addition, provide excellent numerical mediations for researchers to produce spacetimes and sociospatial relationships [3].

As a result, the content of the data is very relevant for the residential market and the local economic structure.


### 3. How was it collected?

The data was collected by python 3. It scraped data from the Airbnb website for a city and stored the result in a database [12].

Each collection of a single city is called a survey, which is an automated collection of data from the Airbnb website for a specified city on or around a specific date [12], including host, price, reviews, URL, and other geocode index.


### 4. What useful information does it contain?

The dataset contains 74 fields, of which the following are the most useful information[4]:
	host_id: The host is unambiguously identified by a unique identifier.
	room_type: All homes are grouped into three types “Entire home/apt”, “Private room”, or “Shared room”.
	location: Each host_id has a latitude and longitude, which could analyze the distribution feature and visualize the thematic map
	price: Price is the most important indicator, which is the foundation of all the analysis.
	review：In the absences of internal Airbnb data, the number of reviews can indicate the rooms’ popularity.


### 5. To what extent is the data 'complete'?

The data are qualitative and quantitative[5], data fields are up to 74, very detailed. However, websites that are not friendly to scrapers often implement methods to prevent or deceive the scripts[2], which causes that a lot of information is misplaced. We have to clean this part data, so the incomplete data raises concerns of the quality of the data.

In Airbnb, while it is not possible for two places to have the same listing ID, it is possible to have a “place” and an “experience” with the same listing id[2]. Therefore, it’s a kind of structure missing data that cause the repetition and could not classify the two types.

The dataset is lack of geocode[6], which is not enough to do spatial analysis. The field ‘postcode’ should be added to distinguish it from others in a finite set of geographic entities. In addition, the key attribute of property size information is not in listing. A profile picture and a detailed description of the listing can increase trust for the guest and decrease the importance of the name of the host.

While we need to watch out for zombie data [5]: datasets have no clear purpose or use cases in mind. The fields (like host_listing_count, review_scores_accurancy and others) are redundant.


### 6. What kinds of analysis would this support?

Firstly, it’s so useful to analyze the uneven spatial housing market caused by social human interaction. There is a significant number of housing units and a high number of points of interest [7], making it possible to reveal the factors that may affect the spatial distribution in the city London.

Secondly, the analysis conducted by Kristof Gyodi confirms that Airbnb's prices are space-dependent [8]. Following data collection, we conducted a statistical analysis (correlation, regression analysis) to determine the socio-economic conditions of the areas using the price of the fields and their location. I believe that it is one of the most important functions for the private user, the organization and the government to analyze the housing crisis and shape the city's economy.

Finally, it offers a multiple dimension to the urban builder to promote urbanization and rationalize urban planning, pushing the development of tourism and tertiary industry. In this way, socialists and economists could build learning models to revitalize the economy through the analysis of socio-spatial data on housing.

In brief, the ‘sharing economy’ has become a new buzzword in urban life to link together people and un- or underutilized assets with those seeking to rent them for short periods of time [9].


### 7. Which of the uses presented in Q.6 are _ethical_?

According to the process of data collection from open resource, it can be seen that hosts published personal and housing information on public platforms. DRJ Verkaik points out in his study that the race of host has a negative impact on the number of bookings and price [10]. Therefore, as researchers in the analysis, their behavior should be ethical to maintain public opinion and public trust, and ethical behavior ensures that the rights of individuals or communities affected by the research are protected [11].

There are geocoded data, which can be used to explore spatial analysis features. The use of geocoding has the potential to expose the ethical aspects of geographic research, particularly because of their privacy sensitivities[11]. While Location information for listings are anonymized by Airbnb. In practice, this means the location for a listing on the map, or in the data will be from 0-450 feet (150 meters) of the actual address. Listings in the same building are anonymized by Airbnb individually, and therefore may appear "scattered" in the area surrounding the actual address [13]. Therefore, spatial data analysis is ethnical.

The social power associated with data setting influences the role of data in economic aspects. The power imbalances lead to silence or complete loss of data in the dataset, which in turn leads to data opacity [5]. There is no power-related data content in the collected data. The authenticity and reliability of the data can support the exploration of socio-economic structure, which is ethical, and can even strengthen the interpretation of the data to the practical significance, so as to better remove any functional limitations and related moral obligations of the data [5].

When it comes to urbanization or urban governance, race is an unavoidable part of the discussion. With the collect data reflecting the socio-economic layout, it obviously Clearly linked to race, ethnicity and even religion. So, when we do analysis, we should keep an objective and neutral attitude, not tendentious. Otherwise, it will fall into an amoral vortex.


## Bibliography

[1]	N. Gurran and P. Phibbs, “When Tourists Move In: How Should Urban Planners Respond to Airbnb?,” Journal of the American Planning Association, vol. 83, no. 1, pp. 80–92, Jan. 2017, doi: 10.1080/01944363.2016.1249011.

[2]	A. Alsudais, “Incorrect data in the widely used Inside Airbnb dataset,” Decision Support Systems, vol. 141, Feb. 2021, doi: 10.1016/j.dss.2020.113453.

[3]	S. Elwood and A. Leszczynski, “Feminist digital geographies,” Gender, Place and Culture, vol. 25, no. 5, pp. 629–644, May 2018, doi: 10.1080/0966369X.2018.1465396.

[4]	M. Cox and T. Slee, “How Airbnb’s data hid the facts in New York City,” 2016. [Online]. Available: http://www.nytimes.com/2015/12/02/technology/airbnb-releases-trove-of-new-york-city-home-sharing-data.html

[5]	“Data Feminism • Data Feminism 6. The Numbers Don’t Speak for Themselves License: Creative Commons Attribution 4.0 International License (CC-BY 4.0),” 2020.

[6]	B. Chi, A. Dennett, T. Oléron-Evans, and R. Morphet, “WORKING PAPERS SERIES Creating a new dataset to analyse house prices in England Creating a new dataset to analyse house prices in England”, [Online]. Available: https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads

[7]	G. Dudás, G. Vida, T. Kovalcsik, and L. Boros, “A socio-economic analysis of Airbnb in New York City,” Regional Statistics, vol. 7, no. 1, pp. 135–151, 2017, doi: 10.15196/RS07108.

[8]	K. Gyódi and Ł. Nawaro, “Determinants of Airbnb prices in European cities: A spatial econometrics approach,” Tourism Management, vol. 86, Oct. 2021, doi: 10.1016/j.tourman.2021.104319.

[9]	M. Ferreri and R. Sanyal, “Platform economies and urban planning: Airbnb and regulated deregulation in London,” Urban Studies, vol. 55, no. 15, pp. 3353–3368, Nov. 2018, doi: 10.1177/0042098017751982.

[10]	“Digital discrimination: Airbnb Amsterdam.”

[11]	V. van den Bemt, J. Doornbos, L. Meijering, M. Plegt, and N. Theunissen, “Teaching ethics when working with geocoded data: a novel experiential learning approach,” Journal of Geography in Higher Education, vol. 42, no. 2, pp. 293–310, Apr. 2018, doi: 10.1080/03098265.2018.1436534.

[12] 	 Tom Slee, (2013). Airbnb Data Collection: Methodology and Accuracy [online]. Available: https://tomslee.net/airbnb-data-collection-methodology-and-accuracy

[13] 	Inside Airbnb. (2013). Disclaimers [online]. Available: http://insideairbnb.com/about.html


## Appendix 


```python

```
