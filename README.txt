Introduction:
In this project we will work with the Human Development Indicator, an indicator that measures the human development of the countries. It is made up of three dimensions: educational level, health level and income level of the population.
In my opinion, this is an insufficient description of human development, so I will add more dimensions to the index an see how it affects the current ranking.
*Dimensions are described in Dataframes Section.

Data Sources:
In this project we will obtain our data from two different open sources, the first one is Gapminder's repository and the second one is CTdata360's repository.
Gapminder is an independent Swedish foundation with no political, religious or economic affiliations. Gapminder is a fact tank, not a think tank. Gapminder fights devastating misconceptions about global development. Gapminder produces free teaching resources making the world understandable based on reliable statistics. Gapminder promotes a fact-based worldview everyone can understand. Gapminder collaborates with universities, UN, public agencies and non-governmental organizations. All Gapminder activities are governed by the board. https://www.gapminder.org/about-gapminder/

Gapminder's dataframes:
Human Development Index
Population
Gross National Income
Gender Equality Index
CO2 Emissions
Fundamental Rights
Murders/100k people
*Data link: https://www.gapminder.org/data/
TCdata360 is an initiative of the World Bank Group's Macroeconomics, Trade & Investment Global Practice, which helps countries achieve the Bank Group's twin goals, ending extreme poverty and boosting shared prosperity, through rapid and broad-based economic growth, centered on strong contributions from the private sector. https://tcdata360.worldbank.org
TCdata360's dataframes:
Press Freedom Index
*Data link: https://tcdata360.worldbank.org/indicators/h3f86901f?country=BRA&indicator=32416&viz=line_chart&years=2001,2019
Dataframes:
Human Development Index (hdi):
Index used to rank countries by level of "human development". It contains three dimensions: health level, educational level and living standard.
Value Range: 0 to 1 (at higher values greater, human development)
Country Range: 187 countries
Year Range: 1990-2015 (27)
Population (pop):
Total population.
Country Range: 195 countries
Year Range: 1800-2100 (prediction) (302)
Gross National Income per capita (gni):
Gross National Income divided by midyear population. Data are in constant 2010 U.S. dollars.
Country Range: 155 countries
Year Range: 1975-2018 (45)
Gender Equality Index (gender_equality):
Contains five dimensions: power distribution by gender, female participation in civil society organizations, ratio between female and male mean years of schooling, proportion of lower chamber female legislators and proportion of women in ministerial level positions.
Value Range: 0 to 100 (at higher values, greater gender equality)
Country Range: 186 countries
Year Range: 1960-2017 (59)
CO2 Emissions (emissions):
Carbon dioxide emissions from burning of fossil fuels (metric tonnes of CO2 per person).
Values: higher values are obviously worse
Country Range: 192 countries
Year Range: 1800-2014 (216)
Fundamental Rights (fundrights):
It includes three subattributes: acces to justice,civil liberties, and social rights and equality
Value Range: 0 to 100 (at higher values, more fundamental rights are respected by the country)
Country Range: 155 countries
Year Range: 1975-2018 (45)
Murders/100k people (murders):
Mortality due to interpersonal violence, per 100,000 standard population, age adjusted. This rate is calculated as if all countries had the same age composition of the population.
Values: higher values are obviously worse
Country Range: 103 countries
Year Range: 1950-2016 (68)
Press Freedom Index (press_freedom):
The data is collected through an online questionnaire sent to journalists, media lawyers, researchers and other media specialists selected by Reporters without Borders (RSF).
Values: 0 to 100 (at higher values, the country has a freer press)
Country Range: 180 countries
Year Range: 2001-2019 (18)