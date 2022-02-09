# Project-1---Team-3
# Global Gender Equality

## Context


A comparison study of gender equality and work between a selection of countries in all regions of the world based on employment and world development indicators from the World Bank Datasets. We gathered our research using The World Bank Gender Statistics Data Catalog including 922 indicators on 227 countries dating back to year 1960. 

## Step 1: Install Dependencies

`matplotlib` 
`pandas`
`scipy.stats` 
`pyplot` 
`numpy`
`csv load and read`
`os path generator`
`requests` 
`BytesIO`
`Json`

## Step 2: Clean Data and create attributes for analysis

We narrowed our scope down to 18 countries representing all continents and the following indicators as reported in 2018:

* GDP per capita, PPP 
* Labor Force Participation Rates:  % of Population Male/Female
* Human capital index (HCI)
* Population
* Unemployment Rates % of labor force Male/Female


“Percent Delta” was created to measure Equality between Males and Females in the Work Force and we use the “Percent Delta” attribute to drive correlations to the other attributes within our study.  We also created the attribute to easily identify those countries in our study with higher rates of inequality to lower rates of inequality. 

## Step 3: Analysis

## Female labor force compare to HCI

*We found a positive up hill correlation of 0.66 between female labor participation of women 15 to 64 years of age and HCI.   Further analysis is needed to understand the relationship since the variables may be conditioned by each other but not related.  Female labor force participation is measuring economically activity women in 2018 and HCI predicts human capacity.

## Economic sectors compare to HCI

We than researched how HCI was related to different working activities (agriculture, industry, services) to have an insight on how HCI relates to different types of economies.  We thought that if HCI measures the return potential of the skills acquire by individuals and societies over time it should have a high correlation to the service employment sector since these activities belong to a tertiary economy in the three-sector-economic-model. Meaning economies that use high skills like service industries to facilitate the transport, distribution and sale of goods produced in the secondary (manufacturing) and primary economies (extraction of raw materials).

## Female labor force compare to HCIComparing GDP and labor force participation

* We sought to discover whether there was a correlation between gender gap in labor force participation and overall economic performance in that country. 
*We measured the difference between female and male participation rates and GDP per capita based on purchasing power parity.
* We found that there was no linear correlation (R Value -0.28) for the countries examined.
* We suspect that because only 18 countries were included that our sample size may have been too small and included too many outliers to detect a correlation. (P Value 0.25)

## Total population & Unemployment per country, year 2018

* The unemployment rate is calculated by dividing the number of unemployed people by the total number in the labor force, then multiplying by 100

* We found that female and male unemployment rates vary greatly between the countries.

