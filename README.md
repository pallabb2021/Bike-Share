# Project Name : Bike Demand Case Study

- Background\
BoomBikes, a US bike-sharing provider, has faced significant revenue declines due to the COVID-19 pandemic. To recover, they aim to understand the post-pandemic demand for shared bikes. They plan to use this insight to prepare for increased demand and outperform competitors. BoomBikes has hired a consulting firm to identify key factors influencing bike demand in the American market and to determine how well these factors predict future demand. This strategic approach is intended to help BoomBikes thrive once the economy stabilizes.

- Objective\
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Modules Used](#Modules-Used)
* [Conclusions](#Conclusions)


## General Information
BoomBikes, a US bike-sharing provider, has faced significant revenue declines due to the COVID-19 pandemic. To recover, they aim to understand the post-pandemic demand for shared bikes. They plan to use this insight to prepare for increased demand and outperform competitors. BoomBikes has hired a consulting firm to identify key factors influencing bike demand in the American market and to determine how well these factors predict future demand. This strategic approach is intended to help BoomBikes thrive once the economy stabilizes.

## Modules Used
- numpy
- pandas
- seaborn
- sklearn
- statsmodel
- scipy
- statsmodels

## Conclusions

- Year progression show increase in bike demand in 2019.
- Temperature is a strong factor, demand goes down in low temperatures.
- Summer and winter shows more bike demand compared to other seasons.
- Rain, cloudy and misty weather decreases the demand, clear weather is preferred.
- Holiday has a negative coefficient, meaning demand goes down on holidays.
- Few months are preferred like Sep which has a positive coefficient which matches with EDA analysis.
- Wind speed shows a negative coefficient, demand goes down with wind speed is more.
-  Equation of line becomes/Bike Demand = const*0.12 + yr*0.23 + holiday*-0.1 + temp*0.57 + windspeed*-0.15 + season_summer*0.08 + season_winter*0.13 + weathersit_Light Snow & Rain*-0.28 + weathersit_Mist  & Cloudy*-0.08 + mnth_Jul*-0.04 + mnth_Sep*0.09
