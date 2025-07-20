# Dataset: Predicting new crescent moon visibility applying machine learning algorithms dataset

## Associated Publication  
**Predicting new crescent moon visibility applying machine learning algorithms**  
*Published in Scientific Reports (2023)*  
DOI: [https://doi.org/10.1038/s41598-023-32807-x](https://doi.org/10.1038/s41598-023-32807-x)


## Abstract  
The world’s population is projected to grow 32% in the coming years, and the number of Muslims 
is expected to grow by 70%—from 1.8 billion in 2015 to about 3 billion in 2060. Hijri is the Islamic 
calendar, also known as the lunar Hijri calendar, which consists of 12 lunar months, and it is tied to the 
Moon phases where a new crescent Moon marks the beginning of each month. Muslims use the Hijri 
calendar to determine important dates and religious events such as Ramadan, Haj, Muharram, etc. 
Till today, there is no consensus on deciding on the beginning of Ramadan month within the Muslim 
community. This is mainly due to the imprecise observations of the new crescent Moon in different 
locations. Artificial intelligence and its sub‑field machine learning have shown great success in their 
application in several fields. In this paper, we propose the use of machine learning algorithms to help 
in determining the start of Ramadan month by predicting the visibility of the new crescent Moon. 
The results obtained from our experiments have shown very good accurate prediction and evaluation 
performance. The Random Forest and Support Vector Machine classifiers have provided promising 
results compared to other classifiers considered in this study in predicting the visibility of the new 
Moon.

## Data Description
Data collection To commence our study, we began by collecting data to construct our dataset. We 
ensured that our dataset was thorough and adhered to the necessary standards by sourcing data from the Inter
national Crescent Observation Project (ICOP). Our data collection involved recording observations and all 
associated features of multiple states and cities in each country registered by the ICOP. The data was accumulated 
over a period of 11 years from 2009 (1431 Hijri) to 2020 (1441 Hijri). In selecting the features to include in our 
dataset, we utilized common features used in this type of study while also adding our own features, such as ARCL 
and illumination (previously mentioned, aiding in calculating W). Other features encompassed in our dataset 
are date, country, city, state, atmosphere, latitude, longitude, Sunset, Moonset, Sun_Moon_Lag, Age_of_Moon, 
MoonAltitude, SunAltitude, altitude_Difference, MoonAzimuth, SunAzimuth, azimuth_Difference (DAZ), and 
V_eye. Table 1 outlines the important formulas for feature calculations. To focus solely on data relevant to the 
Ramadan month, we removed all the Hijri months except for Ramadan. Additionally, we added data pertain
ing to the last two Hijri years (1442 and 1443), including the current year 2022, by utilizing Accurate Times 
5.6 software47. Our final dataset consists of a total of 358 observations from 43 countries

## Access Instructions  
To obtain access to the dataset, please contact us by email at: **murad.al-rajab@adu.ac.ae**; **samia.loucif@zu.ac.ae**; **yazanrisheh@hotmail.com**  
Access is granted on a case-by-case basis for academic and non-commercial research purposes only.

## Citation Requirement  
If you use this dataset, you **must cite** the following publication:
Al-Rajab, M., Loucif, S. & Al Risheh, Y. Predicting new crescent moon visibility applying machine learning algorithms. Sci Rep 13, 6674 (2023). https://doi.org/10.1038/s41598-023-32807-x

> [Authors], *[Title of the Paper]*, Scientific Reports (2023).  
> DOI: [10.1038/s41598-023-32807-x](https://doi.org/10.1038/s41598-023-32807-x)

## Usage Restrictions  
- Redistribution of the dataset to third parties is **not allowed**.  
- The dataset is provided for **non-commercial research use only**.  
- Use of the dataset must comply with all applicable laws and institutional guidelines.
