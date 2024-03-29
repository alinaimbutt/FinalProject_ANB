# Understanding Religious Clustering in New York City
## ____________________________________________________________________________________
## By Ali Naim Butt (MCRP), Edward J Bloustein School of Planning and Public Policy, Rutgers University 
(Command Line GIS)

### Research Question: Exploring the Socioeconomic Dynamics of Places of Worship in New York City: A Comparative Analysis of Median Age and Median Income across Different Religious Institutions

### Datasets:
a. Where did you find them?

The All Places of Worship dataset was sourced from the IRS master files, which contain the national record of all 501(c)(3) non-profit organizations. The dataset was extracted and geocoded based on the reported addresses of places of worship, resulting in a geospatially enabled dataset. The Homeland Infrastructure Foundation-Level Data (HIFLD) received the dataset and conducted quality control (QC) tasks, including metadata population based on the IRS Exempt Organizations Business Master File Extract (EO BMF).

b. Who prepared them? How recently were they updated?

The dataset preparation involved multiple entities. The IRS master files served as the primary source, and the geocoding and quality control tasks were performed by the HIFLD Support Team (HST). The information was last updated on June 30, 2020, at 12:00 AM.

c. What format were they originally in? Did you have to do anything to make them mappable (table join, spatial join, geocoding, aggregation, etc.)?

The All Places of Worship dataset is in the shapefile point format. It was originally in a non-geospatial format and underwent geocoding to eovided details.

d. Were there any issues with data quality that you had to address?

The dataset underwent quality control tasks by the HIFLD Support Team, ensuring accuracy and reliability. However, it's essential to note that the dataset's information was last updated in June 2020. Users should exercise caution when interpreting or relying on the data, considering any developments or changes that may have occurred since the last update.


## Median Income - NYC 
The average annual household income in New York City is $113,315, while the median household income sits at $70,663 per year. Residents aged 25 to 44 earn $87,626, while those between 45 and 64 years old have a median wage of $76,018. In contrast, people younger than 25 and those older than 65 earn less, at $48,585 and $43,340, respectively.
![MedianIncome](https://github.com/alinaimbutt/FinalProject_ANB/assets/70640124/6e41ac4f-3410-4e86-974b-55e0d6b4498f)


## Diversity Index
New York, NY is home to a population of 8.74M people, from which 84.8% are citizens. As of 2021, 36.3% of New York, NY residents were born outside of the country (3.17M people).
In 2021, there were 1.51 times more White (Non-Hispanic) residents (2.79M people) in New York, NY than any other race or ethnicity. There were 1.84M Black or African American (Non-Hispanic) and 1.23M
Asian (Non-Hispanic) residents, the second and third most common ethnic groups.
![diversity_index_map](https://github.com/alinaimbutt/FinalProject_ANB/assets/70640124/c7b1f61a-6a3b-4b74-9b58-a78fe5bcb446)

## Places of Worship - NYC 
The map below shows that regardless of the borough, religious places are in almost every part of NYC
![Places of Worship map](https://github.com/alinaimbutt/FinalProject_ANB/assets/70640124/49161c0c-9edc-4231-bd2d-012bc9277433)

## Conclusion
In conclusion, the exploration of the socioeconomic dynamics of places of worship in New York City through a comparative analysis of median age and median income across different religious institutions reveals a nuanced relationship between demographic factors and economic standing. The backdrop of New York City's diverse population, comprising 8.74 million people, showcases a rich tapestry of ethnicities and backgrounds, with 36.3% of residents born outside the country.

Examining median income distribution, the city's average annual household income of $113,315 underscores economic diversity. Notably, residents aged 25 to 44 boast a median wage of $87,626, while those aged 45 to 64 have a median income of $76,018. In contrast, younger individuals (under 25) and seniors (over 65) earn less, at $48,585 and $43,340, respectively. These figures illuminate the interplay between age demographics and financial well-being in the city.

Considering the religious landscape, the study does not only provide insights into the socioeconomic characteristics of New York City but also prompts contemplation on the potential correlations between religious affiliations and economic status. As individuals from various racial and ethnic backgrounds contribute to the city's diverse makeup, the places of worship within these communities likely play multifaceted roles in shaping and reflecting the economic experiences of their congregants.

This research contributes to a broader understanding of the complex interconnections between socioeconomic factors and religious institutions, offering a foundation for further investigations into the dynamics of faith communities within the diverse urban context of New York City. As cities continue to evolve, such studies become essential for fostering inclusivity and addressing the unique needs of different demographic groups, enriching our comprehension of the intricate relationship between socioeconomic dynamics and religious practices in contemporary urban environments.
## Interactive map to view different Religious Cities across New York City vs Median Income along with Heat Map
<iframe src='nyc_interactiveMap.html' width = '900' height = '900' ></iframe>
You can also explore [this map as its own web page here](nyc_interactiveMap.html)
