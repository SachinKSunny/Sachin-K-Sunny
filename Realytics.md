# Part I- The Idea

## Project Outline
![](https://user-images.githubusercontent.com/56980097/74110944-a8400b80-4b5e-11ea-9ec5-366b286eb317.jpg) 

A brief summary of the Realytics project, what it provides and the rough structure of the story being told is explained in the following sections.

#### Summary

The Realytics project aims at bridging the gaps in the Real Estate Market. Whether you're a potential home owner looking to find the right house, a real estate developer who's looking to invest in the city or a restaurant/small business owner trying to set up shop, we help you find the perfect spot in the town of Pittsburgh. Do not worry, we are not trying to sell you land or a house. We're just trying to help you make an informed decision when you decide to go ahead.

#### Structure

1- Start with how much data is available(Happy user- initial spike in the story arc) out there yet we're never able to find what we're looking for when we're looking for it. Maybe the granularity of information isn't to our liking. Or we've to pay for the data. Or we've to spend a lot of time searching and combining data to make a decision. Fatigue from information search leading to something analogus to the Law of Instrument(When all you have is a hammer, everythign looks like a nail). (Starting down the hill of fatigue and sadness in the story arc)

2- Talk about added risk of large investments and risks coming from various sources. As a home buyer, you'd be concerned with the median house prices and crime in the neighbourhood. As a commercial developer you might be concerned about building permits. As a small business owner you might be concerned about overall economic health of the region and it's people, house prices and permits. But you end up having to spend a lot of time/money as mentioned in Step 1(Low point in the story arc).

3- This is where Realytics comes in(A new hope in the story arc). Talk about the zipcode wise data we've collected so far and how we've catered the data to fit your investment needs. More weightage to home prices for home owners; more weightage to permits for commercial developers.

4- Show the visualizations superimposed over a map of Pittsburgh in a diverging colour scheme to draw user Attention. Also show the top priorities for each user visualized for the user's top 3 Zipcodes. A succint summary of the values of the attributes may also be provided.
(Ascending further up on the peak of happiness in the story arc for the user because of the solution to an important problem). A much more detailed explanation on how the ranking was computed can be added in this section too.

5- Call to action would be access to the whole compiled and cleaned dataset so that the user can get more information that's catered to his exact needs. Also further links to major real estate sites like Zillow, Trulia, Redfin, Neighbourhood Scout, Realtor, etc. will be provided for a one stop solution for all the User's needs. (A one stop solution would be the peak that the story ends in).

## Initial sketches

The initial sketches for the final site design, the visualizations included within the site are briefly discussed below:<br/>
![Site Layout and Flow](https://user-images.githubusercontent.com/56980097/74110407-51383780-4b5a-11ea-812a-db4df684c75c.jpg)

A crude version of the Pittsburgh Map mentioned in the above sketch is shown below:<br/>
![Pittsburgh Map](https://user-images.githubusercontent.com/56980097/74110414-6dd46f80-4b5a-11ea-8f29-71401faa1af6.JPG)


## The Data

For this project I download data from 4 main sources:

1- Median House Prices from Zillow:
Zillow provides the median house prices for a city broken down by zipcode for the current month. This data is available as an API in the following link. I've written a Python script that pulls this data into an easy to use Excel sheet that we'll be using.<br/>
[Zillow Data](https://www.zillow.com/webservice/GetRegionChildren.htm?zws-id=X1-ZWz18xjv6xav4b_3bebs&state=pa&city=pittsburgh&childtype=zipcode)

2- Employment Statistics:
The employment statistics for each county in Pittsburgh is pulled from the US Bureau of Labor Statistics. This is a good indicator of the economic development of the region and indirectly determines the rise/fall in housing prices over time. The data is directly available as a CSV download in the link below.<br/>
[Employment Statistics](https://www.bls.gov/regions/mid-atlantic/news-release/unemployment_pittsburgh.htm)

3- Building Permits:
Ease of getting permits in a Zipcode might incentivise certain developers and commerical users to weight this data more in their ranking. It also acts as a good proxy for the economic growth of a region and is an indirect indicator of the GRP of the city. The data is publicly available at the below link.<br/>
[Building Permit Data](https://data.wprdc.org/dataset/city-of-pittsburgh-building-permit-summary)

4- Crime Data:
Most home owners would like to invest in a low crime neighbourhood. This data will have a high weightage for residential users and small business owners as it determines the potential for further investment and growth of existing investment. The last 30 days data of the crime blotter that's provided by the Police is available publicly at the following link.<br/>
[Crime Data](https://data.wprdc.org/dataset/police-incident-blotter/resource/1797ead8-8262-41cc-9099-cbc8a161924b)


An Excel sheet that has combined all the data available from these sources is available below:<br/>
[Realytics Data Combined.xlsx](https://github.com/SachinKSunny/Sachin-K-Sunny/files/4242512/Realytics.Final.Model.xlsx)


## Method and Medium
The final project will be delivered on Shorthand, an easy to use Website creator. Shorthands scrollable interface and ease of incorporation of images will be an asset when trying to help nudge users a little bit toards their investement region.Shorthand's interface will also help strike a clear balance between the data and the story I'm trying to tell. 

I will be using Tableau to generate the visualizations required for the various user types. Excel will be used to combine and clean the data. Once the wireframes have been critiqued by multiple users- hopefully by home owners, developers and small business owners, I will be incorporating their feedback into my final project and catering to the user base by creating visualizations that create the most impact for each type of user. Shorthand will also be used to generate the final presentation outline using certain picutres from the final site.

[PART II- Design & User Research](/Wireframe&Feedback.md)
[PART III- Final Data Story](/FinalDataStory.md)

[<-Go back to Main Page](https://sachinksunny.github.io/Sachin-K-Sunny/)
