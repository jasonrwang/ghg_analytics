# ghg_analytics

Insights into trends with global greenhouse gases and climate change action.
Final project for EPA1333 Computer Engineering for Scientific Computing at TU Delft.

![SDG 13 Banner](https://i.imgur.com/mHjPRPo.png)

## How To

Download or clone the directory and run `ghg_analytics.ipynb` using Jupyter Notebook, or access the static web version in `index.html`, which is also [hosted here](http://jasonrwang.github.io/ghg_analytics/).

The file comes with outputs cleared. Make sure to run it (Jupyter Notebook lets you run all)!

### Authors

* Aashna Mittal
* Gamze Ünlü
* Jason R Wang

## Executive Summary

In this analysis, we analyzed the implications of United Nations Framework Convention on Climate Change (UNFCCC) on member states' Nationally Determined Contributions (NDCs).

In Section 1, we combine and clean differnet data sets to get the data in useful form for the later analysis. Later we provide an overview of the world and the current situation comparing the NDCs submitted and temperature targets.

In Section 2, we start focusing on the countries and the question "Which countries are polluting more?". We narrow down the analysis to top 10 most polluting countries in 2015 (the top three are China, the United States, and India) and visualize their 2030 projected emissions in no policy case and their submitted NDCs. We compute their target reduction of emissions. We find that submitted NDCs are able to meet the 2ºC Paris target but not the 1.5ºC.

In Section 3, we broaden our analysis with the notion of "Historical Debt" which is one of the important discussion points within Paris Agreement. We see the historical emissions of the top 10 emittors. Later we find the relation between their percent reduction target (from forecasts), GDP per capita, and cumualative emissions. With this analysis countries are grouped into four different categories in order to compare their contributions to global warming and their targets. We found that only Mexico has low Historical Debt and has a good ambition. All nine other countries had insufficient ambition and ranged in their level of Historical Debt.

In Section 4, we introduce the Green Climate Fund pledges and visualize how much each country pledged to contribute. We later compare this amount with the number they should contribute which is found within the analysis in this section, finding that the United States should contribute more than 50%, rather than only 3% (its current pledge). Following up from Section 3, a "Guilt factor" is proposed to make recommendations on how much top 10 emitters _should_ contribute to the Green Climate Fund and how much their NDCs targets should be.

Section 5 discusses the reccomendations and conclusions of the analysis. We found that the United States holds the almost as much carbon debt as the rest of the other top 10 polluters combined (apart from China). Since its GDP per capita is 7x larger than China's, its guilt index is accordingly larger too. Compared to similarly wealthy and industrialized nations, its cumulative emissions were around 10x greater. Overall, the United States' Guilt factor was an order of magnitude higher than every other country in the world.

Under this analysis approach, the United States should be highlighted as _the_ major actor to combat global climate change. Given the US's current stated intention to exit the Paris Agreement, its absence could be detrimental to the Paris ambitions. Luckily, American states, cities, companies, and other organizations [have pledged their own NDC-equivalents too](https://www.globalclimateactionsummit.org/americas-pledge-outlines-bottom-up-opportunity-agenda-for-u-s-state-city-and-business-action-on-climate/) and are largely helping the United States' climate action..

Obviously, further analysis needs to be conducted to consider other factors like other indicators for technological ability, level of development, or level of carbon lock-in. The Guilt factor defined in this analysis should not be applied in any other context without understanding the limitations of its assumptions; the Guilt factor here is by no means exhaustive.
