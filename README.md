# DAI-Midterm

Below is the description and outline of my Midterm Project for the DAI Cohort 10


Background

With the world economy being more interconnected than ever, shifts in economic metrics reverberate in different ways throughout the world economies. While each ripple is its own tune, the ebbs and flows of a country's economy impact more than just the country itself. With that said, I wanted to look at high-level economic metrics derived from the World Bank and see any correlations between shifts in specific metrics and what impact, if any, occurs on economics. Over the last couple of decades, populations have shifted immensely due to wars, poverty, famine, etc., and moved into neighboring countries or countries that are continents away. The data sets I chose to use reflect numbers in GDP by country, total population by country, and net migration by country.

Hypothesis

Statement: Shifts in population are highly correlated with a country's future economic outcomes, including GDP. 

Population shifts significantly impact a country's GDP output. I believe that there are two correlations to be seen:
1. A country's GDP is highly correlated to its population; therefore, a significant shift in population will show a sizable change in GDP.
2. Shifts in a country's GDP will impact its neighboring countries.

Further background for future analysis:

Future statement: Understanding the population shifts can be used to predict future shortfalls in society and better prepare a government for possible destabilizing influences in their country's culture.

If it is possible to dig into the demographics of the migrants in and out of countries, a better understanding can be had concerning what policy shifts a government can make to prevent them. For example, if there are college students in engineering leaving the country for another country because there are no jobs, a government could find a means of incentivizing those graduates to stay in the country. On a more predictive note, understanding what shifts are occurring within the country's demographics makes it possible to predict future events that a government needs to prepare for. For example, if a large cohort of doctors decide to move, what impact does that have on the healthcare system? If the negative shifts occur, what demographics are leaving, and how does that impact those left behind? Is there an increase in the crime rate? What does the tax situation look like, and how can the government continue to provide essential services to the remaining citizens?

Data

The data was sourced from the World Bank, which conducted a general search for GDP, migration, and population. Within the data sets, all countries in the world are present, including territories. Additionally, the World Bank grouped countries by regions (i.e., countries in the Middle East were grouped together, as were countries in the European Union) to reflect regionality and/or shared governance/economic factors. However, those groupings have been dropped from within the code to prevent skewing of results due to the groupings dwarfing individual countries on charts. The timeframe in the data is from 1960 until 2023. However, several countries don't have data reported. For example, Lebanon didn't have GDP data until 1988, and Russia did not until 1988 too. The lack of data could be due to the underdevelopment of a country's governance capacity or political decisions. 

To allow a number of graphs to be performed within the code, the data was "melted." Doing so didn't alter the data; it merely adjusted how the data is represented within the dataset, allowing the computer to process the dataset into the used analysis tool. 
