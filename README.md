# World Development Analysis Project
## Data Source
### Main Dataset: World Development Indicators
#### Summary:
This dataset summarizes 100 different indicators that impact global development, health and poverty. It consolidates information from official sources across the world from 1960 - 2023 and summarizes at the national and regional levels.
#### Reason for choosing:
I'm interested in the differential development of countries over time and particularly how social, environment and economic factors contribute to global and national quality of life. Further, this data is robust and has a multitude of factors with which to practice analysis and many potential hypotheses to explore.
### Secondary Datasets: World Bank Income & National Religions - Correlates of War
#### Summary:
The world bank income dataset classifies countries per year from 1987 to 2022 as having Low, Lower middle, Upper middle or High income based on GNI per capita. 
The National Religions dataset contains the population of followers of 35 world religions (include subsects ie Catholicism, Protestantism) by country by year in 5 year increments from 1945 to 2015.
#### Reason for choosing:
I've chosen these datasets to merge (on key = Code-Year) with the original WDI dataset to include 2 categorical variables (Income Grouping & Top Religion) and potentially draw insights into how religion or income grouping may interact with region, time and/or any WDI figures.
## Data Tableau Dashboard
[Tableau Dashboard](https://public.tableau.com/views/WorldDevelopmentIndicatorAnalysis/Story?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)
## Data Profile
[Data Profile](https://docs.google.com/document/d/1Q6NKOSRb4bZQ5gbz57sMWshCltmzBM7q6Xvl1L-35bM/edit?usp=sharing) for wdi_cleaned.csv
## Limitations and Ethical Considerations
### Limitations
#### Data completeness:
Both the original WDI dataset and the final merged ones contain variables that are missing for some years and some countries. This is likely in part due to the fact that the World Bank aggregated data from various global government entities and in some cases certain metrics may have not been adequately tracked. Fortunately, there are enough variables that I will be able to find stretches to accurately compare variables across region and time.
#### Correlation vs Causation:
I'm working with very generalized data – meaning i'm not focused on specific areas of life but potentially looking at correlations across many. Because of this, I need to be careful to not draw causation conclusions. For instance, I may find strong correlations between renewable electricity production and national GNI per capita and while these insights may be important and telling, I should not assume causation. There are likely many confounding variables that my analysis will not consider.
#### Collection bias (varying methods):
The data included covers a long time horizon and comes from many different original sources meaning the ways of measuring and collecting data may differ across time and region. The World Bank has done a thorough job in using uniform units to make figures comparable (ie measuring GDP in current USD) but there still exists a potential for collection bias.
#### Collection bias (politically motivated):
The data collected comes from government entities which have their own political agendas which may result in bias in certain regions and time horizons.
#### Collection bias (self-reporting):
Likely some of the data comes from survey collection and it's possible that surveys were self-selecting for certain types of respondents or that respondents may have felt political, economic or societal pressure to answer in a certain manner.
### Ethical Considerations
#### Privacy & PII:
Privacy and individual information should always be taken seriously. However, I am using reputable data sources which don't include any personally identifiable information so I will not have to worry much about the data and analysis I make public.
#### Cultural Sensitivity:
My data includes religion and other culturally-influenced behavior. As such, the potential for bias is inherently present and any analysis should be an objective take on the data findings and include minimal conjecture about the motivations or reasons behind any figures or insights.
#### Data Usage (discrimination):
Any insights here should not be used to negatively generalize or discriminate against a specific population or culture.
#### Data Usage (health):
Any insights regarding health should not be used as medical advice and should be scrutinized further if used in any authoritative capacity.
## Key Questions
1. How does energy production source correlate with CO2 emissions across income grouping?
2. How does income share held by different portions of the population correlate with overall income grouping? How has this changed over time? Does this interact meaningfully with GDP per capita or literacy rate?
3. Is there a correlation between internet usage and literacy rate? Has the strength of the correlation changed over time?
4. Does suicide rate interact with alcohol consumption across income groups? How does this differ by religion?
5. Does a higher average working hours of children correlate with lower literacy rates and educational attainment?
6. How does military expenditure as a percentage of GDP impact social insurance coverage and health expenditure?
## Appendix
### Considered datasets:
- [Electricity Production Dataset](https://www.kaggle.com/datasets/sazidthe1/global-electricity-production)
- [World Development Indicators](https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators)
- [Renewable Energy](https://www.kaggle.com/datasets/belayethossainds/renewable-energy-world-wide-19652022)
- [Healthy Lifestyle Cities Report 2021](https://www.kaggle.com/datasets/prasertk/healthy-lifestyle-cities-report-2021)
- [Mental Health Data Set](https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset)
- [Young People Survey](https://www.kaggle.com/datasets/miroslavsabo/young-people-survey)
- [World Bank Income](https://datatopics.worldbank.org/world-development-indicators/the-world-by-income-and-region.html)
- [National Religions - Correlates of War](https://correlatesofwar.org/data-sets/world-religion-data/)
 
