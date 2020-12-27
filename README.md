# Analysis-of-HIP-on-freshmen
A group project conducted while at UW Bothell 


              Impact of early adoption of High impact practices on student graduation 
				                               Alec Radliff, Nora Abdi 
			                             University of Washington Bothell  
    

































				          Abstract:

The purpose of this study was to observe the relationship between students' introduction to High impact practice classes in their education.The link between the inclusion of High impact practices in college classes and an increased graduation rate has been clearly linked, but many studies don't go into when students should specifically take their HIP classes.So our group was interested if there was any link between a early introduction to high impact practices and a greater graduation rate when compared to students who had HIP later in their educational careers. By using Rstudio and the data supplied by the University of Washington:Bothell we created 2 different visuals showing what we found.The data included undergraduate students from across the campus with differing ages,genders,and majors. Our visualizations showed that including early HIP courses for incoming freshmen lead to a decrease in graduation rates compared to students who took HIP classes later in their education.














Background
 	Early adoption of high impact practices are shown to be linked to higher graduation rates and future endeavors after college. As students in the school of Interdisciplinary arts of sciences at the University of Washington, we are curious at the impact that these high impact practices have on graduation rates. Furthermore we also want to see what these high impact practices can do for the speed of graduation and for post graduation plans as a result. 
HIP stands for high impact practices. Preliminary research has shown that High Impact Practices are practices taken up by colleges and universities in helping increase student success even more on campus then.  According to a Kilgo article, it says that practice drastically changes the success rate for students. It also takes the impact of each HIP practice and sees how it impacts the success rate of the demographic which are college freshman.  But in a Bower’s study it describes how those HIP practices have affected and/or if using all can change the graduation rate of the students involved in the HIP practices. It also says that with the earliest installation of the high impact practices has a higher chance of helping graduates get post graduation plans. This relates to what we're doing is essentially how the installation of the HIP impact was done as early as possible, how it can dramatically change the students' success and the graduation rates of each student. According to a price’s study as well, it was also listed out that it was clear that with assessing how and which hip practices have had the biggest impact on students' graduation rates, even adding the time for which the HIP practices were installed, how it can change the rates dramatically even more so. It was clear that it also helped give the students higher GPA and a better chance in receiving a better likeability in what they want to do. 
It is with this research, we ask the following the question: How does early installation of high impact practices impact the graduation rates of students? By addressing the question, we are going to analyze the preliminary research already one and the data provided about how these high impact practices have impacted the graduation rates of the students that are part of these research to fill in the gaps. 

Data summary: 
The data used for the research comes from the Global Initiatives program at the University of Washington:Bothell. The data set includes various HIPs,graduation rates,student retention, and when the students started taking HIP classes . The data also has information relating to student majors,transfer status,ethnicity,gender and a few other identifiers, but these will not be the main focus for our study. Our sample includes 8,695 students divided into two groups based on students who took HIP classes in their first years and students who took them at a later date. This divides our data into 1,111 undergraduate students who took HIP classes upon their entrance into UW Bothell and 7,584 students who took HIP classes later in their education.The specific data we are using comes from the studentdata.xml file and we are using the CareerLevel,
TimeToFirstHIP.(Yrs),GraduatedByYr1,GraduatedByYr2,GraduatedByYr3,and GraduatedByY4 columns.There are two main data types for each of the columns; Career Level is categorical,TImeToFirstHIP is ordinal and the GraduateByYr# are numerical.We are looking at the times that each student graduated and comparing them from the early HIP students to the later HIP students.We measured the percentage of students in both groups to see if it was obvious or not that our hypothesis was correct.
The student data has all the data we need to answer our research question.

Analysis:
To answer our research questions on how early HIP classes affect graduation rates all we need to do is find the total number of students who dropped out in the early HIP students and the later HIP student groups.Once we compare these amounts we can calculate the percentage of graduates from the twop groups and answer our question.
We do not need any complex models to calculate the data we need as once we select the data from the file we can use the subset tool to only select undergraduate students who either had HIP classes in their first year or later. Then for both groups we do another subset to select students who did not graduate and students who did graduate from the groups. This gives us the data we need to conduct a difference of proportions study.We are going to show the conclusion with two pie charts, one for the HIP students who took classes upon their entrance into UWB and the students who took HIP classes later in their school careers.We will not need any complex algebra to show what the answer to our hypothesis is  as it can only have 3 answers.The students who took later HIP classes could have the same graduation rate, a greater graduation rate, or a lower graduation rate than the students who had early HIP classes.

 
Alec Radliff: Bar graph comparing the graduation and dropout rates of students attending HIP classes during their first semester and students who took HIP classes later in there education.




 
Nora Abdi:This visualization of this graph is the relationship between time to degree and how fast someone can do their first HIP and how it affects the graduation rate. 



Results:
Once the visual was made it became obvious that there was a flaw in our data, many students did not have any HIP history but we did have their graduation rates and we can still compare the Early HIP students and the Late HIP students.For the Early HIP group they had a dropout rate of 32% and a graduation rate of 67%. The Late HIP group had a dropout rate of 16% and a graduation rate of 83%, and the Other group had a dropout rate of 51% and a graduation rate of 48%.The data does not support our question. It shows that the later inclusion of HIP classes leads to a higher graduation rate than taking HIP classes directly upon school entry.There are many caveats to this answer though, the early HIP student groups are significantly smaller than the other 2 similarly groups and the lack of HIP data for the students in the Other group leads to the accuracy of the late and early HIP student groups being questioned.HIP classes have been in a flux and are constantly changing as even the types of HIP classes benign given to freshman are different each year.This also interferes with finding a definitive answer to our research question.





Discussion:
With all the research stating that HIP classes improve graduation rates and student outcomes, it seemed like a very interesting idea to study if an early introduction to these classes correlated with an increase in graduation rates. We assumed that since HIP classes lead to higher graduation rates per the other studies being done on them that an early introduction for these classes would also increase graduation rates. The data we have from UW Bothell shows us that many students don't have HIP data at all, almost 10,000 students in fact. This left us with a comparatively small amount of data about HIP students.
When looking at the data for the two HIP groups it's obvious that the later inclusion of HIP classes leads to a higher graduation rate than the early inclusion of HIP classes. This goes against our expectations that an early inclusion would help graduation rates. Indeed, this could be from many different things. The idea behind HIP classes is a new thing that's slowly being adopted across the nation and this means that each school has a different definition of HIP classes and UW Bothell is no different, they've been switching the HIP curriculum over-time to help ease freshman and sophomores into more rigorous classes and sometimes they make mistakes that make it difficult for students to gain a proper foothold in school leading to more dropouts. If we had a larger data set with a more complete amount of students who have had HIP classes as freshmen then we could gain a more solid answer than what we have currently. The large number of students who have dropped out and graduated without any HIP data skews our results by such a large amount that we cannot really gain a serious answer for this question till we gain more data.
If we could do this study over we would change the visuals to more represent the effect HIP classes have on a student's graduation rate over time, instead of only caring about freshman's first-class being a HIP we could look at students and the times they attended HIP classes and repeat each of those times to a graduation rate. Doing so would show how and where the most effective placement for HIP classes would be. If we did this the school could make sure that all students at that specific point in their education all attend a HIP class.
	If we take the data at face value then we can say that for students taking HIP classes later will help them graduate instead of taking them earlier. For professors, it could mean that we need to change the curriculum for freshman HIP classes to help freshmen get a stable start for their college education, and for the staff they could offer more services and support for new students who don't have any networks to gain help from on-campus. This paper is just the first part to learn more about how HIP classes affect students, and we will need more study and data to definitively answer our questions and the many other questions about HIP from professors and students alike.




Bibliography
Kilgo, The link between high-impact practices and student learning: some longitudinal evidence, Higher education, June 14th 2014
Kilgo was taking different HIP practices that would essentially be used to assess student access at the end of the day. 
  Bonet, High impact practices: student engagement and retention, College Student Journal, June 2016
Bonet takes an approach where she assesses the impact that HIP has on community colleges and universities while  comparing them together and seeing how much it has impacted each group. By using certain HIP practices and seeing how differently it would be. 


Randall, Academic Engagement and Student Success: Do High-Impact Practices Mean Higher Graduation Rates, Harvard Business School, April 2018


Randall talks of the relationship of 10 high impact practices and students graduation rates on average at four year universities. While using 101 student samples from all over the country as well as using secondary and primary sources in the research has an impact on the graduation rates of the data samples for which they are used. 

-------------

 Kuh, G. D. (2008). “High-Impact Educational Practices: What They Are, Who Has Access to Them, and Why They Matter. Retrieved from https://apps.weber.edu/wsuimages/oie/Support Documents/Kuh_HighImpactActivities.pdf

Kuh demonstrates that a specific set of educational practices have a significant impact on student success.Using data from the National Survey of Student Engagement Kuh explains why these practices are beneficial for all students.

Price, D. V. (2014, March 18). Student Engagement and Institutional Graduation Rates: Identifying High-Impact Educational Practices for Community Colleges. Retrieved March 1, 2020, from https://naspa.tandfonline.com/doi/abs/10.1080/10668926.2012.719481

Using the 2007 administration of the Community College Survey of Student Engagement they were able to reinforce the link between student engagement as a predictor for college completion.

Brower, M.|Inkelas, A., & Kurotsuchi, K. (2009, November 30). Living-Learning Programs: One High-Impact Educational Practice We Now Know a Lot about. Retrieved May 1, 2029, from https://eric.ed.gov/?id=EJ923859

Goes over some of the high impact practices that can boost graduation rates for college student.Specifically LEAP provided info to president obama's American graduation initiative.





Rstudio code:

Nora Abdi:
Final research project
Nura A
6/1/2020
The effect of early adoption of HIP practices on graduation rates
We are the the student data set to determine the effects of implementing HIP practices have on graduation rates.
-------------------------------------------
-------------------------------------------

-------------------------------------------
-------------------------------------------

-------------------------------------------
-------------------------------------------
-------------------------------------------

-------------------------------------------
-------------------------------------------

-------------------------------------------










Alec Radliff:
---
title: "ResearchProj"
author: "Alec Radliff"
date: "6/3/2020"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(readxl)
library(readxl)
library(gapminder)
library(tidyverse)
studentdata <- read_excel("~/R/Data Research/studentdata.xlsx")
View(studentdata) 
```

## R Markdown
# shows undergraduate students who had HIP classes first and then students who had HIP classes later

```{r newdatatable}
newtable <- studentdata %>% 
  select(`TimeToFirstHIP.(Yrs)`,CareerLevel,GraduatedByYr4) %>%
  filter(CareerLevel == "UG") %>%
  mutate(timing = if_else(`TimeToFirstHIP.(Yrs)` == 0,"Early HIP ","Late HIP")) %>%
  mutate(timing = if_else(is.na(`TimeToFirstHIP.(Yrs)`),"Other",timing)) %>%
  mutate(GraduatedByYr4 = if_else(GraduatedByYr4 == 0,"Dropped","Graduated")) %>%
  group_by(timing,GraduatedByYr4) %>%
  summarise(N = n()) %>%
  mutate(percent = (N/sum(N)))


ggplot(newtable,mapping = aes(x = timing,y = percent,fill = timing)) +
  geom_col() + 
  facet_grid(~GraduatedByYr4) +
  ggtitle("Student graduation rate when taking HIP classes") +
  labs(fill = "Legend" ,y = "Percent",x = "HIP Class Timing",subtitle = "Other columns are for students with no HIP data on record                       ") +
  theme(axis.ticks.x = element_blank()) +
  scale_y_continuous(labels = scales::percent_format(accuracy = 1, scale = 100))

  
```




