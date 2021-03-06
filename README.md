# ICE Solitary Confinement: The Result of Racism, Homophobia, and Power Dynamics

## By Nikki Rosenbloom

### The International Consortium of Investigative Journalists (ICIJ) released [data](icij-solitary-voices-final-dataset-for-publication.csv) of nearly 8500 Immigration and Customs Enforcement detention incident reports from 2012 to 2017. This data set taught me that ICE yields more power than I realized. The magnitude of its authority allows its officers to isolate detainees for essentially any reason without justification. These reasons are often rooted in racial discrimination and other personal beliefs. 

### As I interrogated and analyzed the data, I noticed certain trends in the detention centers in different states. Overall, I learned more about the process of solitary confinement and ICE's corrosive objectivity at the forefront of the detention centers.

I obtained this data from the International Consortium of Investigative Journalists (ICIJ) that was attached in their [article published in 2019](https://www.icij.org/investigations/solitary-voices/about-the-solitary-voices-data/) from the Data is Plural structured archive. After I downloaded the CSV file, I imported it into Google Sheets and used its functions to interrogate and analyze the data.

ICE only tracks records of solitary confinement for two reasons:
1. If the detainee is held in isolation for more than 14 days
2. If the detainee has a "special vulnerability" in isolation

## Distribution of Placement Reasons

The following bar chart breaks down the 8489 reported cases of solitary confinement in ICE detention centers across the nation.

![Reasons for solitary confinement](https://user-images.githubusercontent.com/68294139/89715939-2dfe1180-d95e-11ea-963f-5616876bf1be.png)

## Most Frequent Placement Reason in Each State After "Disciplinary"

I wanted to see how reasons for solitary confinement varied in each detention center listed in the dataset so I created a pivot table to break down the reasons and used it to make a map in Datawrapper. Since "Disciplinary" was almost always the most frequent reason for isolation I decided to make a map of the second-most frequent placement reason.

![image](https://user-images.githubusercontent.com/68294139/89807470-8283c700-daed-11ea-982d-3ed9ac07522a.png)

I created a pivot table to track the divisions of citizenship for each of these placement reasons. In 22/25 of the categories, detainees from Mexico reigned supreme as having the highest number of isolations, usually followed by El Salvadorians or other Central Americans. The only categories they did not count as the most cases are hunger strike, medical: detox/withdrawal, and protective custody for other detainee safety.

![image](https://user-images.githubusercontent.com/68294139/89754379-7cabc880-da90-11ea-900f-248b7eb47ce1.png)



I was intrigued by the number of hunger strike and LGBTQ+ isolations and wanted to find out more details about their patterns regarding facility and citizenship. I created a filter in Google Sheets on the placement reason column to show only the incident reports of hunger strikes in each detention center. I also organized the data according to date so it essentially became a vertical timeline. 

## Hunger Strike Isolations

![image](https://user-images.githubusercontent.com/68294139/89754279-263e8a00-da90-11ea-91b5-59495a883a33.png)

I noticed the isolations for hunger strikes occurred predominantly in Atlanta, Georgia – specifically, the Stewart and Irvin County detention centers. I used the following formula in the state column to count how many of the hunger strike isolations were in GA detention centers: 

```
=COUNTIF(E:E,"GA")
```

Out of the total 182 isolations from hunger strikes in this dataset, 57 of them occurred at the Stewart Detention Center _in 2016 alone_. Both GA detention centers accounted for 79/182 isolations, or 43.4%, from 2012-2017. This history of isolations from hunger strikes is interesting to note because the Stewart Detention Center has had a rise in hunger strikes amid the COVID pandemic this year. Although we do not know why hunger strikes are more frequent in these detention centers, the data casts a light on the different behaviors of ICE officers and detainees compared to other detention centers: that Atlanta ICE officers generally do not support the freedom of expression via hunger strikes.

## LGBTQ+ Isolations

I also wanted to explore any trends from the LGBTQ+ incident reports, so I created another pivot table to count the frequencies of isolations for "protective custody" in different states. I then created the following donut chart to show the total occurrences in the nation's detention centers.

![image](https://user-images.githubusercontent.com/68294139/89746855-c4225c80-da70-11ea-8e39-8bc18f64cca9.png) 

According to this chart, the most isolations due to LGBT reasons occur in Louisiana, which is not surprising considering conservative values of the South, and California, which is pretty unexpected from a state known for its liberalism. Another interesting thing to note is that 50 out of 93 total isolations – _more than half_ – happened after the national legalization of same-sex marriage in 2015. 

## Placement Reasons for Longest Periods of Isolation

Lastly, I wanted to look at which placement reasons justified the incidents of solitary confinement that lasted 6 months or more (about 180 days). I sorted the number of days solitary column in descending order to make this line chart.

![image](https://user-images.githubusercontent.com/68294139/89815978-89650680-dafa-11ea-9f5a-621a9150934e.png)

The four categories with notably high averages are Facility Security Threat: Due to Seriousness, Protective Custody: Criminal Offense, Protective Custody: Gang Member Status, and Other. Unfortunately, we do not have more information about what "seriousness" or "other" entails and why it leads to longer periods of solitary confinement. Clearly the ICE officers are hiding the truth from us by waiving these incidents into these arbitrary categories.

Though these four categories are somewhat surprising, the other averages are relatively high for their placement reasons. For instance, the averages of solitary confinement due to mental illness and suicide risk are alarmingly high; the idea of isolating someone with supposed mental illness or thoughts of physical harm seems like the opposite of the psychological treatment the individual needs.

## Questions to Come

There are still plenty of unanswered questions in the data; what constitutes the "Other" category? What did the LGBTQ+ detainees do to deserve solitary confinement? Why are the hunger strikers being punished for their personal expression?

This dataset is just the start of a further investigation into ICE detention centers and the process and logistics of solitary confinement. Now that some of the groundwork is accessible and publicized, it is up to us to expose the federal officers for their wilting objectivity and radical treatment of the detainees.
