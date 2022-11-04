---
title: "R Projects"
type: page
showTableOfContents: true
---

1. **Understanding the arrest story with the Uniform Crime Report - NIBRS 2021 DC data**

The trilogy entitled *Fostering Social Impacts with Data Science* is a series of data blogging works that explored all arrests made in DC in 2021 from different angles. Through data wrangling, explorative data analysis/data storytelling, and general linear regression, I found out that arrest skyrocketed in August 2021 with a rise from under 100 arrests in July to over 600 cases. Additionally, 90% of arrestees were African Americans with most of them in age 20-40. Additionally, simple assaults and intimidation accounted for around half of all arrests, and 80ish% of arrests did not involve any weapon (firearm/knife). The series is published by ***Towards AI*** on **Medium**. 

- Part I: Intro and Data Wrangling [(Link)](https://pub.towardsai.net/fostering-criminal-justice-with-data-science-part-i-be4cabdeb0a1) 

- Part II: Data Storytelling - Who and When [(Link)](https://pub.towardsai.net/fostering-social-impacts-with-data-science-part-ii-a73f5b90ebf5)

- Part III: Data Storytelling II - How, Data Modeling, and Final Thoughts [(Link)](https://pub.towardsai.net/part-final-fostering-social-impacts-with-data-science-c853e50d0379)

$\textbf{packages}$: `tidyverse`, `ggplot`, `lubridate`, `stringr`, `forcats`, `gt`, `kableExtra`, `sjPlot`, `Quarto` (not a package. *Quarto* is a Rmarkdown-like framework used to publish high quality articles)

> Available at (https://github.com/jcvincentliu/data-blogging)


2. **Nonprofit Sector In Brief Flex Dashboard and Shiny Portal**:
      
This is the project that I worked on during my summer data science internship with Urban Institute. In this position, I developed a R Shiny portal and a flex dashboard that incorporates a handful of features to enhance user interactivity and expand user choices. Both dashboards incorporate a number of interactive charts and maps. I also created a number of easy-to- helper functions to develop a data acquisition -> data cleaning -> data visualization pipeline and reduce the running time.

$\textbf{packages}$: `tidyverse`, `stringr`, `ggplotly`, `leaflet`, `httr`, `flex_dashboard`, `Shiny`

> Available at (https://github.com/jcvincentliu/Urban-Institute-internship-dsproject)


3. **Statistical Analysis of the Police-Public Contact Survey data**:

I conducted some statistical analysis on PPCS data to examine statistical relationships
  between frequency of police stops and arrests and suspects' socioeconomic (age, sex, income), racial, and geo-spatial factors (where they live).

$\textbf{packages}$: `tiydverse`, `survey`, `base R functions` 
