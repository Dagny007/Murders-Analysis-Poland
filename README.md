# Murders Analysis | Poland_1999-2020
Murders in Poland 1999-2020. Data Analysis in Python.
Data Engineering and Big Data | Warsaw School of Economics (SGH)
Postgraduate Studies Project

Contents
The scope of analysis and main conclusions
Part 1: Analysis of murders incidents
Data loading and structure verification
Calculating percantage share
Data grouping and verification
Overal analysis per province
Analysis of provinces share rate
Analysis of maximal/minimal values and crime intensity
Detection rate analysis
Differences between 2019 and 2020
Part 2: Correlation analysis for 2020
Data loading and structure verification
Data segmentation
Relationship analysis: murders, population, province area
Calculation of the murders crime rate
Correlation analysis with chosen variables

The scope of analysis and main conclusions

The purpose of the reserach is the analysis of data presenting number of murders across Poland between 1999 and 2020 (included), broken down by provinces and compared with data related to population and area of the provinces in 2020. The data is extracted from two sources: Police Statistics and Central Statistical Office.

The research is composed of two parts. Part 1 is focused on murder crime trend analysis over the years by provinces, and leads to the recognition of frequency and volume of crimes within particular locations. On top of that, observation dedicated to analyzing crime intensity in time and identification of periods with the highest and lowest rate levels. Additional metric taken under considaration is the general detection rate level and its values over the years. The last component covers comparison between 2019 and 2020, so that key differences can presented and examined. Part 2 enables widening the perspective by adding data about population and provinces areas and exploring correlation by identyfing coefficient relationship between variables. This part covers oly 2020 for all data included in the correlation test. Basing on the results, the relationdhip between key variables is visualised.


Definitions applied in analysis:

- administrative unit: provinces of Poland, e.g. Silesia. - crime registered: number of murders within particular province; followed with official procedures by investigative authorities. - crime detected: number of crimes (among registered) where at least one suspect is appointed. - detection rate: number of crimes detected divided by crimes registered and multiplied by 100, for percantage calculation.

Questions to answer:

[1] What is the general trend of registered crimes across Poland within last 22 years?
[2] Which provinces note the greatest number of murders? What is the share of each in Poland?
[3] What is the crime detection effectiveness? Does it improve over time?
[4] When the greatest and the lowest numbers of murder crime incidents are noted?
[5] Is there any remarkable difference between 2019 and 2020? Which of the provinces stand out and how?
[6] Are there relationships between murders and the characteristics of particular province in 2020? What correlation

<b>Conclusions:</b>

Crime level of the incidents classified as murders decreases with each year. When looking at the provinces with the geatest volume of murders, four of them focus attention. These are: Masovia, Silesian, Lower Silesian, Lodzkie. The first three of them represent the majority of overall share between 1999-2020, where the exact percentage rates are: Masovia (15,8%), Silesian (12,9%), Lower Silesian (9,9%). On the other hand, the lowest records are characteristic for Opole (2%), Subcarpathian (3%), Świętokrzyskie (3%), Podlaskie (3%). Interesting fact: Masovia notes the highest number of murders every year. Unlike Opolskie, which stands for the lowest results consistently.
Questions [1] and [2]

Described results are not equal to high or low level of crime generally. Each case needs to be considered individually, due to local characteristics related to population and area. As the main indicator, the crime rate metric is analzyed as even when the number of crimes itself is lower, the crime rate may be higher once comparing different locations.

Detection of crimes grows significantly while number of crimes decreases. Within last 22 years, the general detection rate increases by ar.12 percentage points, from 86% to 98% countrywide. The highest records are noted in 2000 and 2001 (accordingly: 1270, 1325). On the contrary, in 2016 notes the lowest record of 456 murders. This also confirm the overall decline that happens over the years.
Questions [3] and [4]

Nevertheless, there is remarkable growth in the number of murders in 2020 once comparing to 2019. In some locations the number is twice as big. As example, it is worth mentioning Masovia (+109%), Lubusz (+100%), Kuyavian-Pomeranian (+80%). The opposite situation is observed in Subcarpathian where quite spectacular decline is noted - by 50% in 2020 vs 2019. This phenomenon can be dictated by pandemic and strict rules of health control and public safety followed around the world, what led to minimized crime. In order to confirm such hypothesis, more complex and deepen analysis would be required in order to include additional factors and data volume.

Question [5]
In Part 2 of the analytical work, enriched with two variables: population and area of each province in 2020, there are some relationships identified. Facotr like big population (corr. 0.8) and population density (corr 0.52) seem to present positive relationship with the number of murders. The provinces with the highest number are Masovia, Silesian. Meanwhile, the ones with the highest crime density (number of crimes per resident) are Lubusz, Lower Silesian, West Pomerania and these are classified as more dangerous.
Question [6]

Second interesting thing is quite negative correlation between crime detection rate and population (-0.37); similarly with the area of the province (-0.32). The bigger the population is, the more challenging it is to identify the suspects. Within provinces with bigger area, there is also a better way to hide or escape. Next to this, there are also provinces with high detection rate as a rule, represented by: Kuyavian-Pomeranian, Opole, Lubusz. These are locations with significantly small area and higher crime density. These factors can also contribute to higher detection than in other locations on average.
Question [6]
