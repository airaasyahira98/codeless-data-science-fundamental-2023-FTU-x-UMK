"Analysis of Dengue Cases by State and Age Groups for the Year [2018-2021]"




![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/2829a777-323f-49bd-9b4d-f2229ad945ee)



1. Abstract

Dengue fever is a significant public health concern in many regions, including Malaysia. This study aims to analyze and present the distribution of dengue cases across different states and age groups for the year in 2018-2021.



2. Introduction

Dengue fever, a mosquito-borne viral illness caused by the dengue virus, continues to be a significant public health challenge in Malaysia. Characterized by flu-like symptoms, dengue can range from mild to severe and, in some cases, may even be life-threatening. In the ongoing pursuit of effective dengue control and prevention strategies, a comprehensive understanding of the epidemiological landscape is essential. Dengue is a transmitted disease that can be affect to all people surrounding. Dengue occurs when surrounding not aware about cleanliness and healthiness. It can lower the risk of dengue with avoiding mosquitoes bite especially during the day. Dengue also can be threat with medicine because no specific treatment for this time.


Transmission

They have 4 transmission will occurs:

1)	Human-to-mosquito transmission
-	Mosquitoes become infected by people who are viremic with DENV. It allows people become symptom dengue infection, people who not have a symptoms infection but the people also not showing infection symptoms too.

2)	Maternal transmission 
-	The way of DENV carrying between human involves to mosquito vectors. However, it possibility spread by mother (from mother pregnant and baby).

3)	Transmission through the mosquito bite
-	This virus spreads to human by female mosquito bites that transmitted, especially Aedes aegypti mosquito. Another species in Aedes genus also react as vectors but they donated as a secondary to aegypti Aedes.

4)	Other transmission modes.
-	Rare cases occur by blood donation, organ donation and blood transferring has been recorded. Also, transovarial virus transmission in mosquito also recorded.

 This study seeks to provide a detailed analysis of dengue cases in Malaysia for the year 2018-2021, with a specific focus on the distribution of cases by state and age group.


3. Methodology


![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/32a2fef4-60bf-4436-9cf0-49ad436ad3ef)

Methods:

Data Collection: Data on dengue cases were collected from data government of Malaysia for the entire year 2018-2021.

Data Processing: The data were cleaned and categorized by state and age group. Age groups were typically divided into categories such as 0-4,5-9, 10-14,15-19,20-24,25-19,30-34,35-39,40-44,45-49,50-54,55-59,60-64,65-69,70-74 and >75 and also state which is Johor, Kedah, Kelantan, Melaka, Negeri Sembilan, Pahang, Perak, Perlis, Pulau Pinang, Sabah, Sarawak, Selangor, Terengganu, Wilayah Perseketuan and Wilayah Persekutuan Labuan.

Explanation:
Using Knime Analytics to perform the data and show the visualization of data such as histogram, pie chart and scatter plot.


![csv reader](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/16362b05-67a3-46ff-8d41-28872cbbebe7)

CSV reader : to import data that picked from internet resources.


![colour manager](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/70d2cc1d-4c01-410a-9137-6d8af583a5e6)


Color manager : function as labelling the data to differentiate each row and column and also title.


![column filter](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/35f04e03-a349-4b84-92cd-989a524117a6)


Column filter : function as filtered the column before visualize the data.


![row filter](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/d95421b7-83e1-4ce0-9360-d35d6860283a)


Row filter: function as filtered the row before visualize the data.


![statistics](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/6e655adf-1939-4d06-a9e2-eea3568d08c0)


Statistics : statistics that show overall the data based on year,state and age groups.


![partitioning](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/b55912ec-9824-4fc3-9e8d-67e35cf532fa)


Partitioning : separate from original data set as 80% for upper port and 20% to lower port.


![tree learner](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/a674d4c5-00f0-420d-9284-8c3b76d8a6ea)


Function : To predict the age groups.


![tree predictor](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/3f69323f-9fc2-40fe-aafc-8d77cb3c7fc8)


Function : To apply decision into tree model to test.


![interactive local](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/035e196d-7d14-46ad-83d5-b760c372afd8)


![scorer](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/516929f2-80bb-4589-8795-bf95c450b386)


![scatter plot](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/e7e0843a-6484-486d-a9d0-508d40b04ee8)


![donut chart](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/611256c0-5137-449c-b392-d8dc5481b994)


![interactive histogram](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/b8b8e673-1735-4821-918d-eb117c61a59e)



4. Experimental result

Histogram and statistics

This table shown years, ages group and states. This table are from data of government of Malaysia. This histogram shown in each state who infected dengue based on age groups from 4 years old until 75 years old and above.



![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/34697db3-d59e-4202-92f4-3ee32bc2c375)


![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/4814889e-02d4-403b-95ed-fcdb38db42a9)




Histogram local 

The table of histogram shown age groups and the state was selected.




![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/e6582156-5516-440d-9d82-0061e98f9a36)




Scatter plot

![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/d49d4444-7366-4140-8091-a7cc6cdb58b6)



Pie chart

The pie chart shows the age groups and the state was selected.


![image](https://github.com/airaasyahira98/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848310/d001d040-ab26-4436-af8e-d59587a072ab)




5. Conclusion
   
The conclusion is the states also responsibility to lower the case of dengue with publishes guidelines and handbooks for surveillance, case management, diagnosis, dengue prevention and control for Member States. However, we should provides technical support and guidance to countries for the effective management of dengue outbreaks to the people. Another way, supports countries in improving their reporting systems and capture the true burden of the disease.



6. References
   
data.gov.my

Kesihatan - Kluster - MAMPU (data.gov.my)

Dengue and severe dengue (who.int)








