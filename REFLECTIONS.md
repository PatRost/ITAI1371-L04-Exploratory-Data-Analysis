# Module 04 – Exploratory Data Analysis
## Group 4 Reflective Journal

**Course:** ITAI 1371 – Introduction to Machine Learning  
**Assignment:** Lab 04 – Exploratory Data Analysis  
**Group:** Group 4

---

## Patrick Rostand Gandjouon Tchassem

This lab helped me understand why Exploratory Data Analysis, also called EDA, is important before building a machine learning model. Before doing this lab, I thought working with data was mostly about loading a dataset and using it to train a model. After completing the lab, I learned that we first need to understand the data and look for patterns or problems.
One of the first things I learned was how to get basic information about a dataset. We used the Titanic dataset, which contains information about passengers such as age, gender, passenger class, fare, and whether they survived. I learned that commands like df.info() and df.describe() can help us understand the data. For example, we could see which columns had missing values and also find information such as the average age, survival rate, and fare range.
The visualizations were the most interesting part of the lab for me. Looking at graphs made it easier for me to understand relationships in the data. For example, the passenger class graph showed that first-class passengers had a better chance of survival compared to third-class passengers. The gender graph also showed that females had a higher chance of survival than males.
The experimentation section gave me more practice with creating visualizations. I created a countplot to compare the port where passengers boarded with whether they survived. I also created a boxplot to compare passenger fares with survival. These experiments helped me become more comfortable using Seaborn and Matplotlib.
One challenge for me was understanding what the graphs were actually telling me instead of only focusing on getting the code to run. I learned that creating a graph is only one part of EDA. We also have to look at the graph, understand the pattern, and explain what it means.
Overall, this lab gave me a better understanding of the beginning stages of a machine learning project. My biggest takeaway is that we should explore and understand the data before trying to build a model. EDA can help us find missing values, patterns, relationships, and unusual values. I would like to continue learning how to choose the right visualization for different types of data and how EDA can help us make better decisions when building machine learning models.


---

## Collaborator 2 – [saimi manasiya ]
L04 Reflective Journal

ITAI 1371 – Machine Learning
Module 04: Exploratory Data Analysis

This lab helped me understand the importance of Exploratory Data Analysis (EDA) before building a machine learning model. Before completing this lab, I understood that datasets contain information that can be used for modeling, but I did not fully understand how much we can learn about the data before training a model. This lab showed me that EDA is an important step because it helps us identify patterns, relationships, missing values, unusual values, and possible problems in a dataset.

The Titanic dataset used in this lab was helpful because it allowed me to explore several different variables and see how they were connected to survival. The first step was examining the dataset and its basic information. I learned that checking the structure of a dataset is important because it shows the columns, data types, and missing values. For example, the dataset contained missing values in columns such as Age and Cabin. This showed me that understanding the condition of the data is necessary before using it for further analysis or modeling.

The descriptive statistics section also helped me understand how numerical summaries can provide a quick overview of a dataset. Looking at values such as the mean, minimum, maximum, and standard deviation gave me an initial understanding of variables such as age and fare. However, I also learned that statistics alone do not always tell the complete story.

The visualizations were one of the most useful parts of the lab for me. The survival distribution showed that more passengers died than survived. When survival was compared with passenger class, there was a noticeable relationship between class and survival. First-class passengers had a much better chance of survival than third-class passengers. The gender visualization showed an even stronger pattern, with females having a much higher survival rate than males. The age visualizations also helped show differences between passengers who survived and those who did not, including the noticeable presence of younger children among survivors.

The experimentation section helped me understand that EDA is not limited to the examples provided by someone else. We can ask our own questions and create visualizations to investigate them. Exploring variables such as the port of embarkation and fare helped me think about how different features might be related to survival. This made EDA feel more like an investigation rather than simply running commands and looking at outputs.

One of the biggest things I learned from this lab is that visualization can reveal patterns that are difficult to notice from summary statistics alone. A mean or count gives us a number, but a graph can show differences, distributions, relationships, and patterns much more clearly. This is especially important in machine learning because understanding the data can help us decide which variables may be useful and identify issues that could affect a model.

Overall, this lab changed the way I think about the beginning of a machine learning project. I now understand that building a model should not be the first step. We should first investigate and understand the data. EDA helps us ask better questions, recognize important relationships, and make more informed decisions before modeling. My main takeaway from this lab is that good machine learning begins with understanding the data rather than immediately trying to build a model.



---

## Collaborator 3 – Kenneth Kouokam

My main takeaway from this lab is that understanding a dataset begins before creating a graph. My
focus on data quality and descriptive statistics helped connect the information in the Titanic table with
the conclusions that could reasonably be drawn from it. A clear visualization is useful, but its meaning
depends on which records are present, which values are missing, and what each column represents. I
see EDA as a way to question the information before relying on it.

The missing values provide a useful example. Out of 891 passenger records, 177 had no age, 687 had
no cabin entry, and two had no embarkation entry. These are different levels of missing information, so
using one cleaning rule for every column would be difficult to justify. Removing every row with any
missing value would leave only 183 records. That could discard a large amount of useful information and
change the group of passengers being analyzed. I would consider the purpose of each column before
choosing whether to fill, exclude, or further investigate its missing values.

The average age also needs to be interpreted carefully. The value of about 29.7 years is calculated from
the 714 recorded ages, rather than all 891 passengers. It therefore describes the available ages, and it
may not represent the missing ones equally well. This makes the number of observations an important
part of a summary. A statistic can be calculated correctly while still giving an incomplete picture of the
dataset. For me, checking the count behind a result is as important as reading the result itself.

Comparing the mean and median fare shows another reason to avoid relying on one number. The mean
is about 32.20, while the median is about 14.45. High fares pull the mean upward, so the average alone
does not describe what a typical passenger paid very well. At the same time, an unusually high fare is
not automatically an error. I would investigate its context before removing it. This connects my numerical
review with the group's visualizations, which can make the spread and unusual values easier to see.

I also need to distinguish how a column is stored from what it means. Passenger class is stored as a
number, but it represents ordered categories; a passenger ID identifies a record rather than measuring a
passenger characteristic. These differences affect which summaries and future modeling choices make
sense. The lesson I would carry into another project is to inspect the structure, check completeness,
compare several summaries, and document any limitations before drawing conclusions. That approach
gives the group's charts a stronger foundation and makes later decisions about preparing the data more
thoughtful.



---

## Collaborator 4 – [Name]

**Write your personal reflection here.**



---

## Collaborator 5 – [Hashim Sayed Hoosini]
L04 Reflective Journal

Course: 1371- Intro to Machine Learning

Module 04: Exploratory Data Analysis

Professor: Viswanatha Rao

05 Oct 2026

This lab strengthened my Exploratory Data Analysis learning. Through this project, I learned how to be a detective, searching for clues in the dataset and finding patterns. Understanding the data, handling missing values, finding anomalies, and extracting insights from the dataset for data visualization is a critical step before model training. Also, I learned that data visualization helps us to better understand the data. For this lab, I used the Titanic dataset, which contains passenger information, to search for the factors that increased the survivability rate.
The dataset contains passenger information like passenger name, passenger ID, pclass, sex, age, fare, cabin, and embarked port. I analyzed the data to find out whether these were factors in survivability, searching for relationships between the variables to find out how the variable relationships affect the survivability rate.

First, I imported the necessary libraries, like pandas, matplotlib, and seaborn, for data visualization. Then, I loaded the dataset directly from the provided link and printed the first 5 rows of the data with basic information to study the data. For a better understanding, the high-level numerical summary of the data was generated using the describe() method, which calculates statistics like mean, standard deviation, min, and max for numerical columns. Then, I used matplotlib to plot the patterns and find out the relationships between variables. Matplotlib turned the data into insights for data visualization.

Then, I noticed there is a strong relationship between variables. For example, first-class passengers had a much higher chance of survival compared to second-class and third-class passengers. Also, I looked for more patterns and noticed gender is another clue for survival; a high proportion of females survived compared to male passengers. By looking at the graphs, I found more patterns, like age and embarkation port, and noticed younger passengers, especially children, had a higher chance of survival, while the median age had a slightly lower rate and fewer elderly survived.

I explored the data to find more patterns and noticed fare also has a relationship with the survival rate. The graph shows that passengers who paid higher fares had a better chance of survival. The calculations confirm that first-class passengers had a survival rate of 63%, while the second class had a survival rate of 47%, and the third-class survival rate was around 24%.
Additionally, I noticed that the embarkation port has a clear relationship with the survival rate. The data shows that passengers who boarded from Cherbourg had a higher chance of survival compared to those who embarked from Southampton or Queenstown. This pattern correlates directly with passenger class, as a large portion of first-class passengers boarded the ship at the Cherbourg port, which helps explain the higher survival rates observed for that specific location.

To summarize, this lab helped me to strengthen my exploratory data analysis and understand the data better before model training. These necessary steps help us to build a better model. My biggest takeaway from this lab was how to explore and understand the data, looking for missing values, finding patterns within the dataset, and how to extract insights from data for data visualization.


LLM used: Google AI mode

Purpose: spelling check and grammar problem




