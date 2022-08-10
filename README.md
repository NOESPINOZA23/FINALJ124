# FINALJ124
## Prominet Gender and Racial Disparities in the United States

## Story Pitch
Women of color continue to experience the most severe gender wage gap in the United States, a reality that reflects the effects of intersecting racial, ethnic, and gender biases that threaten the economic security of women and their families. Furthermore, women and disadvantaged monorities have earned an increasing proportion of bachelor's degrees and other advanced degrees, yet there has not been a similar increase in regulations in favor of these groups. The central problem is the continuing discrimination experienced by disadvantaged minorities and women at every stage of the innovation process, from the exposure and mentoring of children and youth in career fields to post-advancement educational barriers, and from discriminatory denials of patent applications to lack of opportunity. The stubborn resilience of the gender pay gap, coupled with intersecting racial bias in the workplace, means many women of color are perpetually underpaid, and these losses add up and grow over time. The combined effects of racism and gender discrimination, in particular on migrant, immigrant, indigenous, minority and marginalized women have had devastating consequences for their full enjoyment of equality and fundamental human rights both in the public as well as the private sphere.



### Sourcing
In this project, I analyzed different data sets from the [Census reporter](https://censusreporter.org/profiles/01000US-united-states/) in the United States:
["Sex by Educational Attainment for the Population 25 Years and Over"](https://censusreporter.org/data/table/?table=B15002&primary_geo_id=01000US&geo_ids=01000US),
["Poverty Status in the Past 12 Months by Sex by Age"](https://censusreporter.org/data/table/?table=B17001&primary_geo_id=01000US&geo_ids=01000US),
["Hispanic or Latino Origin by Race"](https://censusreporter.org/data/table/?table=B03002&primary_geo_id=01000US&geo_ids=01000US), and
["Household Income in the Past 12 Months (In 2020 Inflation-adjusted Dollars)"](https://censusreporter.org/data/table/?table=B19001&primary_geo_id=01000US&geo_ids=01000US). My analysis focused on the economic disparities that females and disadvatanged communities face.


## Data Analysis Process
* First of all, download the all data sheets as .csv files, upload it to Google Drive, and open it with Google Sheets. Then, copy and paste each data set to new tabs in your main sheet. 
* Insert a blank google sheet for data cleaning. 
* Look at the metadata to name the headers of each column of your data sets with the orginal headers not the ID headers that census reporter provides.
* Copy and paste each column of data on the blank sheet to its perspective tittle. 





_Five data analysis questions will be answered step-by-step:_ 

#### Question 1: What is the state with the most unrepresented groups in the United States? Black or African American, American indian and Alaska Native, Asian, Native Hawaiian and other pacific islander, and hispanics or latinos. 
* Locate the columns with the disadvantaged groups: Black or African American, American Indian and Alaska Native, Asian, Native Hawaiian, and other pacific islanders, and Hispanics or Latinos. 
*Sum all columns with the formula =sum(E2,F2,G2,H2,M2,N2,O2,P2,Q2,R2)
* Filter and sort the total sum column for Z-A, and the number in the first row is the answer. 
_Answer: California is the state with the most unrepressented people in the country_



