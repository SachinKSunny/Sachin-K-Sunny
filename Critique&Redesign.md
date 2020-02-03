## Fixing the Bad Bar Chart on Petrol Prices in India

The Bharatiya Janata Party aka the BJP, which has come into power in India in May 2014 published the following graph on their official Twitter handle:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Truth of hike in petrol prices! <a href="https://t.co/hES7murfIL">pic.twitter.com/hES7murfIL</a></p>&mdash; BJP (@BJP4India) <a href="https://twitter.com/BJP4India/status/1039110521549512707?ref_src=twsrc%5Etfw">September 10, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Apart from the glaringly obvious smaller bar for 80 than for 70, this chart fails to deliver a convincing argument of the effectiveness of BJP Rule. So the opposition- the Indian National Congress(INC) Party- came up with the following graph as a rebuttal:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">There! Fixed it for you <a href="https://twitter.com/BJP4India?ref_src=twsrc%5Etfw">@BJP4India</a><a href="https://twitter.com/hashtag/MehangiPadiModiSarkar?src=hash&amp;ref_src=twsrc%5Etfw">#MehangiPadiModiSarkar</a> <a href="https://t.co/kbKBjUi0M7">pic.twitter.com/kbKBjUi0M7</a></p>&mdash; Congress (@INCIndia) <a href="https://twitter.com/INCIndia/status/1039134643922984962?ref_src=twsrc%5Etfw">September 10, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Although this is a step in the right direction, this chart also has a lot of problems in the sense that it is overloaded with numbers and useless pictures, possibly to sway public opinion. It also tries to compare dollars to Rupees without actually adjusting for the changing USD-INR rate which has taken a worse turn ever since BJP came to power.

## Critique on the Indian National Congress Rebuttal Graph

The observations on the data, it's positive and negative aspects have been summarized below categorized on each metric:

Usefulness- Petrol is the primary fuel used in Transportation in India and almost every sector's and/or family's budget is affected by its price.

Completeness- There is a lot of incomplete information in this visualization viz., What's the unit of crude oil? What's the dollar to INR currency exchange rate? Why are only 4 discrete points considered?

Perceptibility- Inorder to avoid guessing the size of bars, Values are shown and the percentage changes too. Also, there's no legend, colors aren't chosen wisely and the information on this page is cluttered.

Truthfulness- The values shown are correct and the size of bars looks accurate which is a major improvement on the graph it's trying to provide a rebuttal for.

Intuitiveness- Why use a bar graph to show percentage changes over time? The intended message that the difference in the price of crude oil and petrol is worse after 2014 is not highlighted here.

Aesthetics- Why is the color of the bars changing over time? The visualization is trying too hard to force the idea on the viewer with too many numbers and as a result, the graph doesn’t look aesthetically pleasing.

Engagement- Unnecessary titles and pictures around the graph space take the engagement away from the graph. The makers of the graph stuck with the same design they were trying to critique and failed to deliver a strong message.

The graph takes a step in the right direction by including the international crude oil price and fixing the skewed 4th bar in the original graph. But it uses the same bad design to critique the visualization by Bharatiya Janata Party. It also doesn't consider the changing USD-INR Rate and tries to compare dollars with rupees as a constant across time. Additionally, it also doesn't specify the units of comparison. I would redesign the graph by showing a continuous trend line of international crude oil prices, petrol prices in India and the difference in prices between the two, highlighting the increase in differences post 2014 when the Bharatiya Janata Party came to power.

The primary audience for this tool are the citizens of India. The visualization wasn't effective in reaching out to the audience because they redesigned the original bad visualization by sticking to the same design and adding the International Crude Oil price variable. Although this moves in the right direction, it fails to convincingly deliver the argument that the % increase of prices under the Bharatiya Janata Party's rule has been drastic compared to the crude oil prices in the international marketplace.

I would let the data speak for itself and create a visualization that lets people come to their own conclusion. An effective public swaying of opinion requires education of the masses and that comes from their own understanding. The visualization should tell the convincing story, not the text in and around the visualization. Also, the visualization can be split into two eras(before and after 2014) to show the stark contrast in numbers under two different regimes.

## Wireframe Solution
I envisioned a wireframe solution as shown below to fix the graph posted by the Indian National Congress Party:
<img src="https://user-images.githubusercontent.com/56980097/73618194-e59f1900-45f3-11ea-99a1-a76ab7df90c7.PNG" alt="drawing"/>

## Insights from Feedback
From showing the wireframe to ~4 people and gathering feedback I recognized that I had to remove the horizontal dotted lines that were trying to highlight the increase under BJP Rule. I also got the feedback to reduce the different variations of colour use so as to be colour blind firendly. I was also asked to specify Congress party as the Indian National Congress Party(INC) to avoid any confusions about other Congress parties across the world. A short description of what the chart was trying to convey was also suggested to be added at the end to enhance interpretability. One positive aspect across all the feedback received was that they all understood that the rise in Prices of Petrol was higher under the BJP Rule than under the INC Rule.

## Redesigned graph of Petrol Price in India

<div class='tableauPlaceholder' id='viz1580687305841' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pe&#47;PetrolPricesinIndia&#47;PetrolinIndia&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PetrolPricesinIndia&#47;PetrolinIndia' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pe&#47;PetrolPricesinIndia&#47;PetrolinIndia&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1580687305841');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

*The international Crude Oil prices have been converted into Price per litre in Rupees using USD-INR spot prices 

|          | Avg Difference | Range of Difference | Range of USD-INR Rate |
|----------|----------------|---------------------|-----------------------|
| Congress | 26.26          | 23.23-28.05         | 40.24-61.14           |
| BJP      | 38.81          | 28.07-41.88         | 61.14-69.92           |

From the above table and visualization, you can see that the petrol prices have drastically been increasing under the BJP Rule even though international Crude Oil prices(converted into Price in Rupees per litre using USD-INR spot prices) have been declining. This is due to the increased taxes being imposed on the sale of petrol- a government decision- and gradual weakening of the INR as compared to USD which can be directly attributed to the government's economic policies. So even though the percentage change has been decreasing like in the initial graph provided by the BJP and the INC, the absolute value of change has been increasing drastically, putting a lot of Indian lives under greater financial burden.

Data Sources:
1. [EIA](https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=RBRTE&f=D)
2. [IOCL](https://iocl.com/Products/PetrolDomesticPrices.aspx)
3. [DNA India](https://www.dnaindia.com/business/report-from-may-2014-to-april-2018-chart-of-petrol-and-diesel-prices-under-modi-govt-2606993)
4. [IOCL Latest](https://www.iocl.com/Product_PreviousPrice/PetrolPreviousPriceDynamic.aspx)

[<-Go back to Main Page](https://sachinksunny.github.io/Sachin-K-Sunny/)
