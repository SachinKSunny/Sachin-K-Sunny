# Part III- Final Data Story

## Intended Audience
This project came about because of the tunnel vision most people employ when it comes to making an investment decision. People often zero in on a Zip Code or a region and start scouting potential modes of investment before looking at the investment opportunities available across all the Regions. A generalised tool like Realytics that caters to a wide variety of audiences was challenging to come up with because of the difference in parameters that different users have while trying to find an investment option.

But after extensive User research and scraping the internet for zip code wise data, I was able to create a customized visualization that caters to different kinds of users. This was achieved by identifying common themes across the intended audience and identifying variables that indirectly determine the return on Investment. By offering the user the flexibility to change the weights for all the parameters identified, they are able to look at and interpret a heat map of Pittsburgh based on their investment needs. Additional parameters like School Rating of a zip code was added in later as a response to the feedback received from an initial wireframe model of the Realytics tool. This tool could be used by residential users(home buyers/owners) who are looking for houses in Zipcodes where there are good schools and low crime rates or commercial developers who're looking to build an apartment complex in a zipcode that's doing good economically(Building Permits granted to a region are a good indicator of the economic health of a region). This tool could even be used by Restaurant/Small Business Owners who're looking to find investment opportunities to expand their business by a simple tweak of the 4 parameters according to their needs.

## The work so far- A Brief Summary
A few paragraphs that summarize the work you've done so far.  Talk about the design decisions you had to make along the way, and reflect on anything in particular that stands out to you that you learned working through the process. (Part III)

The work on the tool initially focused on predefined weights for different kinds of users to figure out what the best regions for investment according to their criteria were. This idea was easily discounted as the flexibility of the tool lied in the flexibility provided to the user to change the criteria according to their needs. Once that flexibility was achieved and the parameters that indirectly determined the Return on Investment was identified, all that was left to do was create compelling and easy to interpret visualizations that people could use without much training.

Initially a crude map of Pittsburgh with circles of different sizes placed all over to indicate the Rank of a Zipcode was conceived. Since this was hard to interpret, it was replaced by a Heat Map of Pittsburgh with each ZipCode given a different shade of colour based on it's rank. From the initial diverging Red colour which was probably not suited for the color blind among us, I moved to a Blue-Orange diverging colour scheme that highlighted the most suitable zip codes with a dark orange/red that directly captures user attention.

Other plots for the top 5 zip codes had to be kept basic so as to cater to a larger audience who might not be acquainted with stacked bar charts or alluvial diagrams or other not so common visualizations. Hence a simple and clear bar chart of the paramater values like House Prices and Building Permits was presented. A 1-D scatter plot of School Ratings and Crime Rates in each zip code also came about due to their simplicity and ease of understanding.

Tableau was used to create all the visualizations and present a user-friendly interface where all the charts would be updated when the user changes the slider on any one of the parameters chosen. Tableau's embedded code also offers additional information about each zip code like it's rank and Realytics Index when you hover the mouse over it giving the user more power over the visualization. By giving the flexibility of changing the graph to the user and citing the data sources, I was thus able to create a very generalized tool. 

## Link to Final Data Story

[The REALYTICS Project](https://carnegiemellon.shorthandstories.com/realytics/)

## References and Citations

1- Tableau Public [Unemployment Rate Visualization](https://public.tableau.com/views/UnemploymentRate_15818041056040/UnemploymentRate?:display_count=y&:origin=viz_share_link)

2- Tableau Public [Residential User Dashboard](https://public.tableau.com/views/RealyticsInvestmentBuddy2_0Residential/Dashboard1?:display_count=y&:origin=viz_share_link)

3- Tableau Public [Commercial Developer Dashboard](https://public.tableau.com/views/RealyticsInvestmentBuddy2_0Commercial/Dashboard1?:display_count=y&:origin=viz_share_link)

4- Tableau Public [Small Business Owner Dashboard](https://public.tableau.com/views/RealyticsInvestmentBuddy2_0Restaurant/Dashboard1?:display_count=y&:origin=viz_share_link)

5- Tableau Public [All in One Dashboard](https://public.tableau.com/views/RealyticsInvestmentBuddy2_0/AllinOne?:display_count=y&:origin=viz_share_link)

6- Median House Prices from Zillow:
Zillow provides the median house prices for a city broken down by zipcode for the current month. This data is available as an API in the following link. I've written a Python script that pulls this data into an easy to use Excel sheet that we'll be using.<br/>
[Zillow Data](https://www.zillow.com/webservice/GetRegionChildren.htm?zws-id=X1-ZWz18xjv6xav4b_3bebs&state=pa&city=pittsburgh&childtype=zipcode)

7- Employment Statistics:
The employment statistics for each county in Pittsburgh is pulled from the US Bureau of Labor Statistics. This is a good indicator of the economic development of the region and indirectly determines the rise/fall in housing prices over time. The data is directly available as a CSV download in the link below.<br/>
[Employment Statistics](https://www.bls.gov/regions/mid-atlantic/news-release/unemployment_pittsburgh.htm)

8- Building Permits:
Ease of getting permits in a Zipcode might incentivise certain developers and commerical users to weight this data more in their ranking. It also acts as a good proxy for the economic growth of a region and is an indirect indicator of the GRP of the city. The data is publicly available at the below link.<br/>
[Building Permit Data](https://data.wprdc.org/dataset/city-of-pittsburgh-building-permit-summary)

9- Crime Data:
Most home owners would like to invest in a low crime neighbourhood. This data will have a high weightage for residential users and small business owners as it determines the potential for further investment and growth of existing investment. The last 30 days data of the crime blotter that's provided by the Police is available publicly at the following link.<br/>
[Crime Data](https://data.wprdc.org/dataset/police-incident-blotter/resource/1797ead8-8262-41cc-9099-cbc8a161924b)

10- School Ratings:
The 2019 School Rankings published by Niche is used to compute the school ratings. Most residential users value this attribute highly while trying to narrow downt their search to a zipcode. The rankings are extracted from the following link:<br/>
[School Ratings](https://www.niche.com/places-to-live/search/zip-codes-with-the-best-public-schools/m/pittsburgh-metro-area/)

11- An Excel sheet that has combined all the data available from these sources is available below:<br/>
[Realytics Final Model.xlsx](https://github.com/SachinKSunny/Sachin-K-Sunny/files/4242512/Realytics.Final.Model.xlsx)

12- Photo by [Vidar Nordli-Mathisen](https://unsplash.com/@vidarnm?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/pittsburgh-night-view?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) under an [Unsplash licence](https://unsplash.com/license)

13- Wordcloud created using [WordArt](https://wordart.com/create)

14- Photo by [Tierra Mallorca](https://unsplash.com/@tierramallorca?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/@tierramallorca?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) under an [Unsplash licence](https://unsplash.com/license)

15- Photo by [Vidar Nordli-Mathisen](https://unsplash.com/@vidarnm?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/pittsburgh-view?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) under an [Unsplash licence](https://unsplash.com/license)  

[PART I- The Idea](/Realytics.md)<br>
[PART II- Design & User Research](/Wireframe&Feedback.md)
<br><br>
[<-Go back to Main Page](https://sachinksunny.github.io/Sachin-K-Sunny/)
