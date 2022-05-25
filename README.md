# Murders Analysis | Poland 1999-2020 <br>Data Analysis in Python.
<a class="anchor" id="intro"></a>
### The scope of analysis and main conclusions
<br>

<p style="text-align:justify;"><b>The purpose of the reserach is</b> the analysis of data presenting <b>number of murders across Poland between 1999 and 2020 (included), broken down by provinces</b> and compared with data related to <b>population and area of the provinces</b> in 2020. The data is extracted from two sources: <b><a href="https://statystyka.policja.pl/st/przestepstwa-ogolem/przestepstwa-kryminalne/zabojstwo/64003,Zabojstwo.html">Police Statistics</b></a> and <b><a href="https://stat.gov.pl/obszary-tematyczne/ludnosc/">Central Statistical Office</b></a>.</p>

<p style="text-align:justify;">The research is composed of two parts. <b>Part 1</b> is focused on <b>murder crime trend analysis over the years by provinces</b>, and leads to the recognition of frequency and volume of crimes within particular locations. On top of that, observation dedicated to analyzing crime intensity in time and identification of periods with the highest and lowest rate levels. Additional metric taken under consideration is the general detection rate level and its values over the years. The last component covers comparison between 2019 and 2020, so that key differences can presented and examined. <b>Part 2</b> enables <b>widening the perspective by adding data about population and provinces areas and exploring correlation</b> by identyfing coefficient relationship between variables. This part covers oly 2020 for all data included in the correlation test. Basing on the results, the relationdhip between key variables is visualised.<p><br>
   
<b>Definitions applied in analysis:</b>
<p style="text-align:justify;">- <b><i>administrative unit</i></b>: provinces of Poland, e.g. Silesia.
- <b><i>crime registered</i></b>: number of murders within particular province; followed with official procedures by investigative authorities.
- <b><i>crime detected</i></b>: number of crimes (among registered) where at least one suspect is appointed.
- <b><i>detection rate</i></b>: number of crimes detected divided by crimes registered and multiplied by 100, for percantage calculation.</p>

-----------
 
<b>Questions to answer:</b>
- [1] What is the general trend of registered crimes across Poland within last 22 years? 
- [2] Which provinces note the greatest number of murders? What is the share of each in Poland?
- [3] What is the crime detection effectiveness? Does it improve over time?
- [4] When the greatest and the lowest numbers of murder crime incidents are noted?
- [5] Is there any remarkable difference between 2019 and 2020? Which of the provinces stand out and how?
- [6] Are there relationships between murders and the characteristics of particular province in 2020? What correlations are observed?

------------
<b>Conclusions:</b>

<p style="text-align:justify;"><b>Crime level of the incidents classified as murders decreases with each year.</b> When looking at the provinces with the geatest volume of murders, four of them focus attention. These are: Masovia, Silesian, Lower Silesian, Lodzkie. The first three of them represent the majority of overall share between 1999-2020, where the exact percentage rates are: <b>Masovia (15,8%)</b>, <b>Silesian (12,9%)</b>, <b>Lower Silesian (9,9%)</b>. On the other hand, the lowest records are characteristic for <b>Opole (2%)</b>, <b>Subcarpathian (3%)</b>, <b>Świętokrzyskie (3%)</b>, <b>Podlaskie (3%)</b>. Interesting fact: <b>Masovia notes the highest number of murders every year</b>. Unlike Opolskie, which stands for the lowest results consistently.<br><i><u>Questions [1] and [2]</u></i></p>

<p style="text-align:justify;"><b>Described results are not equal to high or low level of crime generally.</b> Each case needs to be considered individually, due to local characteristics related to population and area. As the main indicator, the crime rate metric is analzyed as even when the number of crimes itself is lower, the crime rate may be higher once comparing different locations.</p> 

<p style="text-align:justify;"><b>Detection of crimes grows significantly</b> while number of crimes decreases. Within last 22 years, the general detection rate increases by ar.12 percentage points, <b>from 86% to 98%</b> countrywide. <b>The highest records are noted in 2000 and 2001</b> (accordingly: 1270, 1325). On the contrary, <b>in 2016 notes the lowest record of 456 murders.</b> This also confirm the overall decline that happens over the years.<br> <i><u>Questions [3] and [4]</u></i></p>

<p style="text-align:justify;">Nevertheless, there is <b>remarkable growth in the number of murders in 2020</b> once comparing to 2019. In some locations the number is <b>twice as big</b>. As example, it is worth mentioning <b>Masovia (+109%), Lubusz (+100%)</b>, Kuyavian-Pomeranian (+80%). The opposite situation is observed in <b>Subcarpathian</b> where quite spectacular <b>decline is noted - by 50% in 2020 vs 2019</b>. This phenomenon can be dictated by pandemic and strict rules of health control and public safety followed around the world, what led to minimized crime. In order to confirm such hypothesis, more complex and deepen analysis would be required in order to include additional factors and data volume.<br> <i><u>Question [5]</u></i></p>

<p style="text-align:justify;">In Part 2 of the analytical work, <b>enriched with two variables: population and area of each province in 2020, there are some relationships identified</b>. Facotr like big <b>population (corr. 0.8)</b> and <b>population density (corr 0.52)</b> seem to present positive relationship with the number of murders. The provinces with the highest number are Masovia, Silesian. Meanwhile, the ones with the <b>highest crime density (number of crimes per resident)</b> are <b>Lubusz, Lower Silesian, West Pomerania</b> and these are classified as more dangerous.<br><i><u>Question [6]</u></i></p>

<p style="text-align:justify;">Second interesting thing is quite <b>negative correlation between crime detection rate and population (-0.37); similarly with the area of the province (-0.32)</b>. The bigger the population is, the more challenging it is to identify the suspects. Within provinces with bigger area, there is also a better way to hide or escape. Next to this, there are also <b>provinces with high detection rate</b> as a rule, represented by: <b>Kuyavian-Pomeranian, Opole, Lubusz</b>. These are locations with significantly small area and higher crime density. These factors can also contribute to higher detection than in other locations on average.<br> <i><u>Question [6]</u></i></p>
