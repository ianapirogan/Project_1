# Project_1

# PROJECT TITLE: : Factors affecting Airbnb prices in London
---
By Natalie, Zayan, Iana

## Purpose of the Project
 conduct a comprehensive analysis of Airbnb listings in London, with the aim of gaining deep insights into the factors that influence pricing and accommodation availability within this vibrant and diverse city. By examining location dynamics, property characteristics, neighborhood disparities, and the impact of guest reviews, this analysis seeks to provide valuable information to both prospective travelers and hosts

---

### Factor 1: Location : How is the location of the property affecting the Airbnb prices in London?

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Airbnbs.png)

The map visually illustrates that as one moves further away from the central point, the density of Airbnb listings gradually decreases. This observation indicates a higher concentration of Airbnb listings in the central areas of the city. In other words, the central regions exhibit a more significant presence of Airbnb accommodations, while the number of listings diminishes as we venture towards the city's outskirts. This spatial distribution highlights the popularity and demand for Airbnb rentals in the city's central zones, possibly due to proximity to attractions, amenities, or transportation hubs.

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Top50.png)

From this data we can see that these a stong pull to the center of the london

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Bottom50.png)

From this dataset, it becomes evident that the data points are more widely scattered.

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Top%2050%20vs%20Bottom%2050%20less%20then%2010%20km%20airbnbs.png)

The impact of location on Airbnb prices in London is strikingly evident in our analysis. Out of the top 50 Airbnb listings, an overwhelming 46 of them are located within a 10-kilometer radius from the central point of London. This concentration of high-priced listings near the city center suggests that proximity to central attractions, amenities, and transportation hubs significantly influences pricing in the upper tier.

Conversely, among the bottom 50 listings, only 23 of them are found within the same 10-kilometer radius from the center of London. This disparity indicates that listings located farther from the city center tend to have lower prices. It's plausible that these listings cater to budget-conscious travelers or offer accommodations in areas with less demand, leading to more competitive pricing.

Overall, the data underscores the strong correlation between proximity to central London and Airbnb pricing, with listings closer to the center generally commanding higher rates. This insight can be invaluable for both hosts and travelers seeking to understand the pricing dynamics within London's Airbnb market.

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/neighborhood_stats.png)

The insights derived from the bar chart portraying the average price of Airbnb listings across various neighborhoods are striking. The data unequivocally reveals that Kensington and Chelsea stand out with the highest average listing prices, while Croydon emerges as the neighborhood offering the most budget-friendly options. This stark contrast in pricing among neighborhoods underscores the profound influence of location on determining the average price of Airbnb accommodations in London.

Kensington and Chelsea, known for its upscale appeal and proximity to prestigious landmarks, commands a premium in the Airbnb market. Travelers seeking luxurious and well-situated lodgings can expect to pay a premium in this affluent neighborhood. Conversely, Croydon, situated further from the city center and characterized by a more cost-effective housing landscape, offers more budget-friendly alternatives.

This analysis underscores the significance of neighborhood choice as a pivotal factor impacting the average price of Airbnb listings. It highlights the importance of aligning one's accommodation preferences with their budget and desired location, as London's diverse neighborhoods offer a wide spectrum of pricing options to cater to various traveler preferences.

---

### Factor 2: Room Type : Is there any correlation between the room type and Airbnb prices?

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Average%20Airbnb%20Price%20by%20Room%20Type%20in%20London.png)

Our analysis reveals a distinct correlation between room types and the average prices of Airbnb listings in London. By examining the data, we observe a clear pattern: Hotel rooms command the highest average prices, followed by Entire homes, Private rooms, and Shared rooms, in that order.

This trend suggests that the type of accommodation significantly impacts the pricing structure in the Airbnb market. Hotel rooms, known for their premium amenities and services, tend to come with the highest price tags. Entire homes, which offer guests a private and complete living space, come in as the second most expensive option. Private rooms, which offer privacy within a shared home or apartment, are generally more affordable than entire homes but still more expensive than shared rooms. Shared rooms, often characterized by shared spaces and bunk beds, are the most budget-friendly choice, resulting in the lowest average prices.

This insight can be valuable for both Airbnb hosts and travelers, as it provides a better understanding of the pricing dynamics within different room types. Hosts may adjust their pricing strategies based on room type, while travelers can make more informed decisions when selecting accommodations that align with their budget and preferences.

---

### Factor 3: Reviews : Is there any correlation between the number of reviews and Airbnb prices?

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Average%20Price%20vs.%20Number%20of%20Reviews%20with%20Linear%20Regression%20Line.png)

Upon visual examination of the scatter plot, it becomes evident that there is no significant correlation between the average price and the number of reviews. The data points on the graph are widely dispersed and do not exhibit any discernible pattern. They are scattered across the plot without any clear trend.
The slope of the regression line, which is approximately -0.02, indicates a very slight negative relationship. However, this slope is close to zero, suggesting that changes in the number of reviews have an almost negligible impact on the average price.
It's worth noting that while this analysis focuses on the number of reviews, the content and sentiment of those reviews could potentially reveal a different story. If data were available to analyse the content of reviews and determine sentiment (e.g., positive, negative, or neutral), it might show a more meaningful correlation between the sentiment of reviews and the average price. Positive reviews, for instance, could be associated with higher prices, while negative reviews might correlate with lower prices.
In summary, the scatter plot and regression line for average price vs. the number of reviews do not provide strong evidence of a meaningful correlation. The data points' wide dispersion and the regression line's nearly flat slope suggest that factors beyond the number of reviews are influencing the average price of Airbnb listings. Additional variables, such as the content and sentiment of reviews, location, property type, and amenities, may have a more substantial impact on pricing decisions.

---

### Factor 4: Availability: Reviews : Is there any correlation between the availability of the property and Airbnb prices?

![Alt text](https://github.com/ianapirogan/Project_1/blob/main/Output/Price%20vs.%20Availability%20with%20Linear%20Regression%20Line.png)

The scatter plot exhibits a moderately positive correlation between price and availability. As the number of available days increases, there is a tendency for prices to rise. Despite the overall positive correlation, the data points on the scatter plot are still somewhat scattered. This means that while there is a general trend of increasing prices with more availability, there are exceptions, and other factors can influence pricing decisions.
It's important to note that there is a wide range of prices for any given level of availability. In other words, availability alone does not account for all variations in price. Other factors, such as location, property type, and amenities, likely play a substantial role in determining pricing.
In conclusion, the scatter plot and the regression line equation provide evidence of a moderately positive correlation between the price of Airbnb listings and their availability. While the regression line suggests that increased availability tends to be associated with slightly higher prices, there is still a degree of variability, and other factors are also influential.

---

## Conclusion

In conclusion, our in-depth analysis of Airbnb listings in London has shed light on several critical factors that play a pivotal role in shaping the pricing and availability of accommodations within this vibrant city. Through an exploration of location dynamics, we've uncovered how proximity to central areas significantly influences pricing decisions, with high-priced listings concentrated in the city's heart.

Additionally, our examination of the number of reviews revealed an interesting finding – there is no substantial correlation between the quantity of reviews and average pricing. This insight emphasizes the importance of considering additional factors beyond review counts when evaluating accommodation choices.

Our neighborhood analysis underscored the vast disparities in average prices across London's diverse neighborhoods, from the upscale appeal of Kensington and Chelsea to the more budget-friendly options found in Croydon.

Ultimately, this project's purpose was to empower both hosts and travelers by providing them with valuable insights into the intricacies of the London Airbnb market. By considering factors such as location, property type, neighborhood, and guest reviews, stakeholders can make more informed decisions regarding accommodations, pricing strategies, and location preferences.

As the project comes to a close, it is evident that the Airbnb experience in London is intricately intertwined with the city's diverse landscape and the choices made by both hosts and guests. By leveraging the insights gained from this analysis, stakeholders can enhance their Airbnb journey, whether they are hosts seeking optimal pricing strategies or travelers in search of their ideal London stay.

