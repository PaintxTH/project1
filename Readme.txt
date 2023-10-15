{\rtf1\ansi\ansicpg1252\cocoartf2709
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 **Problem Statement**\
\
As a carwash shop owner, there is an uprising among our employees about welfare provided. This situation leave us short in employees due to competitiveness in wages & welfare. So, We are fixing this problem by considering uplift our employee welfare to be more delightful and competitive to the market by adding extra annual paid leave with affecting least on company's revenue.\
(Giving that employees are hire in monthly scheme)\
\
**Objective:** As "demand\'94 for car washes is typically lower during the rainy season than during other times of the year."*** rainy season will be the condition for the usage of extra annual paid leave for our employees to affecting least on company's revenue. Hence, we are trying to identify designated months for this condition.\
\
We already know that SG has 2 monsoon seasons,The Northeast Monsoon from December-March, and the Southwest Monsoon from June-September, but which one is the worse ? So, we can flag one and aim those season, Then which month could be a condition for our employee extra leaves\
\
\
**Conclusion and Recommendations**\
\
**Disclaimer:** As stated in Raw Data above, the metrological station has been relocated quite a few then moved to Changi since 1984, I didn't remove the data from 1982 to 1984 since station relocation may not be a big deal in Singapore context which as total area of a bit more from Phuket province!\
\
After quite a few EDA, It is certain that The Northeast Monsoon that occurs from December to early March is cause more serverity in terms of rains than the Southwest Monsoon from June to September. So, we suggest that condition to put in the rules for extra paid leaves for employee welfare should be around October, November, December and January; Although, this shouldn't extend to February since February has shown to be the least rain month of the year to effect least with business since It is proven *(from outsource article*)* that rain can associate with demand for Carwash.\
\
Else; It can put it in marketing perspective; rainy season can be put to a perfect chance to run a promotion of non-car washing associated service like car detailing / coating to avoid rain stain to damage car paint and have employee benefits from it for extra incentive for such services. So, both owner and employee can enjoy benefits both side.\
\
This may help in business decision in a perspective, but together with sales in carwash data over period of time could be perks more and help making smarter decision (if available; although is a 'no no' in this case) \
\
**Outside Research**\
\
1.Professional Carwashing & Detailing magazine, "Weather's impact on carwashing" article, published March 2022.*\
https://www.carwash.com/weathers-impact-carwashing/\
\
\
**Data Dictionary**\
|Feature|Type|Dataset|Description|\
|---|---|---|---|\
|**total_rainfall**|float|rainfall-monthly-total|Total rainfall in mm| \
|**no_of_rainy_days**|int|rainfall-monthly-number-of-rain-days|Total numbers of rainfall days by month|\
|**Avg_rf_perday**|float|sgrf|Average rainfall per day (only day that rains 0.2mm or more ) |\
|**sgrf**|dataframe|no_of_rainy_days| dataframe of total numbers of rainfall days by month |\
|**sgtr**|dataframe|total_rainfall| dataframe of total rainfall in mm |\
|**sd**|dictionary|total_rainfall + no_of_rainy_days| dictionary of total rainfall in mm and total numbers of rainfall days by month |\
|**sgrf2**|dataframe|total_rainfall + no_of_rainy_days| dataframe of total rainfall in mm and total numbers of rainfall days by month |\
|**GR_NumRainDays**|column|sgrf2| column that shows average growth rate Month on Month of rain days (>0.2mm) from 1982-2022 |\
|**GR_Totalrainfall**|column|sgrf2| column that shows average growth rate Month on Month of accumulated rain from 1982-2022 |\
\
\
}