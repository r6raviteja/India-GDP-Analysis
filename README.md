# India-GDP-Analysis

The data is sourced from https://data.gov.in/ - an Open Government Data (OGD) platform of India. The download instructions are provided in the next segment. The data for GDP Analysis of Indian States is divided into two parts:

Data I-A: This dataset contains the GSDP (Gross State Domestic Product) data for the states and union territories.

Data I-B: This dataset contains the distribution of GSDP among three sectors: the primary sector (agriculture), the secondary sector (industry), and the tertiary sector (services) along with taxes and subsidies. There is separate dataset for each of the states. You are expected to read the dataset for the available states and join these (in Python) if needed.

There are two parts to this project. In the first part, you will analyse and compare the GDPs of various Indian states (both total and per capita). The GDP of a state is referred to as the GSDP (Gross State Domestic Product). Then, you will categorise the states into four categories based on GDP per capita and, for each of these four categories, you will analyse the sectors which contribute most to the GDP (such as agriculture, real estate, manufacturing, etc.).

In the second part, you will analyse whether GDP per capita is related to drop out rates in schools and colleges.

Part-I: GDP Analysis of Indian States For each of the following steps of analysis, choose an appropriate type of plot for comparing the data. Also, ensure that the plots are in increasing or decreasing order for better comparison. For e.g., if you make a bar plot to compare the GDPs of various states, ensure that the bars are in either increasing or decreasing order of GDP.

Part I-A:

For the analysis below, use the Data I-A.

Remove the rows: '(% Growth over the previous year)' and 'GSDP - CURRENT PRICES (` in Crore)' for the year 2016-17.

Calculate the average growth of states over the duration 2013-14, 2014-15 and 2015-16 by taking the mean of the row '(% Growth over previous year)'. Compare the calculated value and plot it for the states. Make appropriate transformations if necessary to plot the data. Report the average growth rates of the various states:

Which states have been growing consistently fast, and which ones have been struggling?

Curiosity exercise - what has been the average growth rate of your home state, and how does it compare to the national average over this duration?

Plot the total GDP of the states for the year 2015-16:

Identify the top-5 and the bottom-5 states based on total GDP

Part I-B:

For the analysis below, use Data I-B. You can also use Data I-B along with Data I-A if required. Also, perform the analysis only for the duration : 2014-15. Filter out the Union Territories (Delhi, Chandigarh, Andaman and Nicobar Islands etc.) for further analysis since they are governed directly by the centre, not state governments. Plot the GDP per capita for all the states. Identify the top-5 and the bottom-5 states based on GDP per capita. Find the ratio of highest per capita GDP to the lowest per capita GDP. Plot the percentage contribution of primary, secondary and tertiary sectors as a percentage of total GDP for all the states. Categorise the states into four categories based on GDP per capita (C1, C2, C3, C4 - C1 would have the highest per capita GDP, C4 the lowest). The quantile values are (0.20,0.5, 0.85, 1), i.e. the states lying between the 85th and the 100th percentile are in C1, those between 50th and 85th percentile are in C2 and so on. Note: Categorisation into four categories will simplify the subsequent analysis, since comparing data of all the states would become quite exhaustive For each category C1, C2, C3, C4: Find the top 3/4/5 sub-sectors (such as agriculture, forestry and fishing, crops, manufacturing etc.) [not primary, secondary and tertiary] which contribute to approx. 80% of the GSDP of each category

Note-I: The nomenclature for this project is as follows: primary, secondary and tertiary are named 'sectors', while agriculture, manufacturing etc. are named 'sub-sectors'

Note-II: If the top-3 sub-sectors contribute to say 79% of the GDP of some category, you can report 'these top-3 sub-sectors contribute to approx. 80% of the GDP'. This is to simplify the analysis and make the results consumable (remember, the CEO has to present the report to the CMs, and CMs have limited time, so the analysis needs to be very sharp and concise)

Plot the contribution of the sub-sectors as a percentage of the GSDP of each category.

Now that you have summarised the data in the form of plots, tables etc., try to observe non-obvious insights from it. Think about questions such as:

How does the GDP distribution of the top states (C1) differ from the others? Which sub-sectors seem to be correlated with high GDP? Which sub-sectors do the various categories need to focus on? Etc.

Ask other such relevant questions which you think are important and write your insights for category separately.

Finally, provide at least two recommendations for each category to improve the per capita GDP.

Part-II: GDP and Education Drop-out Rates In Part-I, you would have noticed that (one) way to increase per capita GDP is by shifting the distribution of GDP towards the secondary and tertiary sectors, i.e. the manufacturing and services industries. But these industries can thrive only when there is availability of educated, skilled labour.

In this part of the analysis, you will investigate whether there is any relationship between per capita GDP with drop-out rates in education.

Data Data II: This section will require the drop-out rate dataset apart from the dataset that you have used in Part-1 of the case study. Download instructions are given in the next segment.

Part-II: GDP and Education

Analyse if there is any correlation of GDP per capita with dropout rates in education (primary, upper primary and secondary) for the year 2014-2015 for the states. Choose an appropriate plot to conduct this analysis.

