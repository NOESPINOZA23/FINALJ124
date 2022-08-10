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

### Potential Interview Contacts:
#### 1- Jotaka L. Eaddy, a tech Advisor and Senior Strategist

[Contact Website](https://www.jotakaeaddy.com/contact)

Instagram: [@jotakaeaddy](https://www.instagram.com/jotakaeaddy/?hl=en)

Eaddy would be a qualified contributors to my story because she is very knowledgeable of the system the oppresses women. She has even made an organization, and has gave statements in the United Nations related to intolerances. As a leader women she understands the oppression from another point of view because she has lived it even at white collar scenarios. 
* Jotaka is the founder of the movement #WinWithBlackWomen (2020), an intergenerational, intersectional group of Black women leaders. These women are representing business, sports, movement, politics, entertainment and more. 
* #WinWithBlackWomen is credited with making a significant impact on the historic election of 2020 which resulted in the United States first Black woman Vice President–Kamala Harris. 
* Eaddy gave a statment at the Geneva, 5 – 16, October 2015 in Palais des Nations, Conference Room XXI in which she emphasized income inequality, education, access to technology and STEM education illustrating “the deep correlations between race and poverty” and women. 

#### 2- Dr. Christina M. Castro, founder contributor of The Three Sisters Collective
Email: [message3sc@gmail.com](https://mail.google.com/mail/u/0/#inbox)

Castro could contribute to my report because she know how disadvantaged people are always in economic needs. She has worked closely with low income and disadvantaged families. 
* Dr. Christina M. Castro and the organization she helped found, the Three Sisters Collective, worked hard to support the Indigenous Santa Fe community through many challenges this year. When COVID hit, she helped organize a fundraiser for native families experiencing hardship. 
* During the rough fire season, her organization members came together to purchase and distribute air purifiers and water for native families struggling with the air quality.
* Throughout these challenges, she worked tirelessly on the Three Sisters Collective’s mural project that protects existing Indigenous artwork in Sante Fe and is creating additional murals to celebrate Indigenous culture and people in the area.

#### 3- Oasis for Girls 

[Youth non-profit organization](https://www.oasisforgirls.org/)

[sfoasis@sfoasis.org](https://mail.google.com/mail/u/0/#inbox)

1091 Mission St, San Francisco, CA 94103

(415) 701-7991

Oasis for Girls is an organization that helps girls cultivate the skills, knowledge, and confidence to discover their dreams and build strong futures inside a country that lacks of women rights. 
* This organization can contribute to my research because they have been working with high school unprivilaged girls since 1999. 
* They have the knowledge of what it means to be a women in the United States under a system that is male and white suppresmacist.
* They may have the access to study girls closer, and find out how the system affects them as women. 
* They make sure to empower women to get out into the world no matter what the circumstances are. 



### Additional Sources: 
#### World Economic Forum
The Global Gender Gap Report presents information and data that were compiled and/or collected by the World Economic Forum, and it reports on different aspects of  gender inequalities worlwide. Gender wage gap not only happens in the United States but also in the whole wolrld, and this reports has a whole data report about the topic.

E-mail: [contact@weforum.org](https://mail.google.com/mail/u/0/#inbox)

Tel: +41 (0)22 869 1212




## Data Analysis Process
* First of all, download the all data sheets as .csv files, upload it to Google Drive, and open it with Google Sheets. Then, copy and paste each data set to new tabs in your main sheet 
* Insert a blank google sheet for data cleaning 
* Look at the metadata to name the headers of each column of your data sets with the orginal headers not the ID headers that census reporter provides.
* Copy and paste each column of data on the blank sheet to its perspective tittle





_Five data analysis questions will be answered step-by-step:_ 

#### Question 1: What is the state with the most unrepresented groups in the United States? Black or African American, American indian and Alaska Native, Asian, Native Hawaiian and other pacific islander, and hispanics or latinos. 
* Locate the columns with the disadvantaged groups: Black or African American, American Indian and Alaska Native, Asian, Native Hawaiian, and other pacific islanders, and Hispanics or Latinos 
*Sum all columns with the formula =sum(E2,F2,G2,H2,M2,N2,O2,P2,Q2,R2)
* Filter and sort the total sum column for Z-A, and the number in the first row is the answer


_Answer: California is the state with the most deprived people in the country_

![Screenshot (152)](https://user-images.githubusercontent.com/109619730/183802143-849f3a28-f9bb-424c-8baf-8962aea106a2.png)

### Question 2: Calculate the total rate below poverty for women and men in each state separately from the total population below poverty. What are the four states with the highest rates of poverty for each sex?

### Part 1: 

* First, make sure the state names are sorted A-Z ready to copy and past information from other columns in the right order.
* Insert a blank sheet in the same google sheet with the name–Question 2
* Look at the metadata to copy and paste your female and male below poverty level data with the orginal name headers not the ID headers that census reporter provides
* Use =SUM() formula to add the female below poverty and males below poverty to get a total of below poverty population
* Calculate the female below poverty rate by dividing the total number of females below poverty with the total below poverty population: =O2/P2
* Filter and sort the female below poverty rate column Z-A to get the answer

_Answer: Texas, Georgia, Louisiana, and California are the states with more poor women in the country_


![Screenshot (156)](https://github.com/NOESPINOZA23/FINALJ124/blob/main/screenshots/Screenshot%20(156).png)

### Part 2: Where is the highest number of males in poverty located? How does this compare to the highest number of women?

* Use the same sheet for Question 2 part 1
* Calculate the male below poverty rate by dividing the total number of females below poverty with the total below poverty population: =AF2/P2
* Filter and sort the male below poverty rate column Z-A 

_Answer: Alaska, New Hampshire, Arkansas and South Dakota are the states with higher males in poverty. Both females and males have high poverty rates in different states of the country._

![Screenshot (159)](https://github.com/NOESPINOZA23/FINALJ124/blob/main/screenshots/Screenshot%20(159).png)

### Question 3:  Who has higher poverty in the whole nation, males or females?

### Part 1: Females

* Use the same sheets for Question 2
* Make sure your filter are clear
* First, sum all the total female column which includes all states using the =SUM() formula at the bottom of the total female column. Do the same process for the total below poverty population
* Then, calculate the rate by dividing the total female below poverty with the total below poverty population: =O53/P53

![Screenshot (160)](https://github.com/NOESPINOZA23/FINALJ124/blob/main/screenshots/Screenshot%20(160).png)

### Part 2: Males

* Repeat the same process for males
* Use the same sheets for Question 2 
* Make sure your filter are clear 
* First, sum all the total male column which includes all states using the =SUM() formula at the bottom of the total female column
* Then, calculate the rate by dividing the total female below poverty with the total below poverty population: =P53/Q53

![screeshot (161)](https://github.com/NOESPINOZA23/FINALJ124/blob/main/screenshots/Screenshot%20(161).png)

_Answer: Females, there are more poor females in the United States_

### Question 4: What gender has the highest total of people that has attained at least a bachelor’s degree in the country, Males or Females? 

* Use the cleaned data set to SUM all the education level starting bachelor’s degree and over for males and females 
* Use =sum(BY2:CB2) for males, and =sum(CQ2:CT2) for females
* Insert a new sheet to make further calculations and avoid confusion 
* Copy and paste the name of states on the further left column
* Use the =Vlookup() formula to import the two calculated columns for at least bachelor’s degree education for females and males
* =VLOOKUP(A2,'Cleaned data'!A1:CV52, 82, false) for males, and =VLOOKUP(A2,'Cleaned data'!A1:CV52, 100, false) for females
* Finally, sum the all the values of the one column–females, then go for the next one–males at the very bottom

_Answer: Females have attained the higher number of people educated of at least bachelor’s degree_


![Screenshot (162)](https://github.com/NOESPINOZA23/FINALJ124/blob/main/screenshots/Screenshot%20(162).png)

### Question 5: What is the state that has the highest population with the lower incomes below $35,000? How does this relate to female poverty rates per state and race? 

* Insert a new sheet to avoid confusion 
* Copy and paste the name column on the further left
* Make sure the name column is clear of filters, and copy and paste all the income columns below $35,000
* Insert a pivot table, and plug the name colum on rows and the rest on the values 
* Summarize each column on the values section as MAX. This will give you the actual value of each box in the columns
* The total will give you the highest number of the column which is our answer 

_Answer: California is the states with the highest number of population earning lower than $35,000 annually. This relates to female poverty rates because California is one of the state with the most poor women in the nation with 92.02% like question 2 demonstrates. Also, California has the highest number of disadvantaged residents in the country_

![Screenshot (164)](https://github.com/NOESPINOZA23/FINALJ124/blob/main/screenshots/Screenshot%20(164).png)














