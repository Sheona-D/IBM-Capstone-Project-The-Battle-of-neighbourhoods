# IBM-Capstone-Project-The-Battle-of-neighbourhoods
<h1>Coronavirus Covid-19 - A Study</h1>

<h2>Introduction</h2>

<h4>Background and Problem Statement</h4>
  2019 Novel Coronavirus (2019-nCoV) or Covid-19 is a virus (more specifically, a coronavirus) identified as the cause of an outbreak of respiratory illness first detected in Wuhan, China. Early on, many of the patients in the outbreak in Wuhan, China reportedly had some link to a large seafood and animal market, suggesting animal-to-person spread. However, a growing number of patients reportedly have not had exposure to animal markets, indicating person-to-person spread is occurring. 

<br>Individual risk for the disease is dependent on exposure. Covid-19 has now been detected in almost 150 locations internationally, including in the United States.There have been close to 170,000 people sickened by COVID-19 and more than 6,500 people have died from the disease—a death toll that has far surpassed that of the severe acute respiratory syndrome (SARS) epidemic that occurred in 2002 and 2003. Officials everywhere have implemented measures to contain the virus, including travel restrictions and quarantines. Based on the circumstances, WHO (World Health Organization) has declared COVID-19 a pandemic (an epidemic that spreads throughout the world).

This study will highlight the different regions affected globally, the number of people affected, deaths, people who have recovered and the common symptoms.The different visualisations will help us understand the spread of the disease, the estimated mortality rate and other statistics. This study aims to create awareness among the general public, which is of extreme importance in this situation and provides several useful insights into the data. This can also be used by researchers, students who are interested in the subject. 

<h2>Data</h2>
The data used for this study has been taken from the links mentioned below. Furthermore, we will access data through FourSquare API interface and arrange them as a dataframe for visualization. One of the datasets consists of data from 22nd Jan, 2020 while the other consists of daily case reports of the number of confirmed, dead and recovered cases. The usage of data is explained in detail in the implementation section.   
<br>Links :-
https://github.com/CSSEGISandData/COVID-19
<br>
https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

<h2>Methodology</h2>
This section will describe the main components of our Study. The steps are as follows:-
<ol>
<li>Collect covid-19 related data from https://github.com/CSSEGISandData/COVID-19 and https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
<li>Explore, understand the data, data preprocessing
<li>Using FourSquare API we will find all location related information
<li>Visualize and Analyse using folium library(python) and plotly
</ol>
