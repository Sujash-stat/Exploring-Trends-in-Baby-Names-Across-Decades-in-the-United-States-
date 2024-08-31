
# Exploring Trends in Baby Names Across Decades in the United States


Our project delves into the captivating world of baby names in the United States spanning from 1920 to 2010. Envision it
as a journey through the evolving panorama of names over the years.

## 1. Motivation
Names transcend mere labels; they function as time capsules, offering insights into the societal trends of various decades.
Our objective is to delve into these capsules, unraveling the stories they hold and deciphering how people’s preferences
for baby names have transformed. At the core of our exploration is the mission to unveil trends in US baby names across
decades, distinguishing between timeless classics and passing fancies.




## 2. Data Set

- We have gathered the top 100 names for each decade, culminating in a comprehensive dataset of 1,000 observations, encompassing both male and female babies.

- In addition to charting the trajectory of baby names in the United States from 1920 to 2010, our project extends its reach to compile a rich tapestry of information. We meticulously gather data on the history and origin of every name that has graced the top 100 rank list throughout these decades. This multifaceted approach allows us not only to track the ebb and flow of naming preferences but also to unravel the fascinating stories behind each name. 
Instead of static databases, we opt for real-time data scraping directly from the source. To bring this dynamic data to life, we showcase it seamlessly on our custom-designed RShiny app, specifically crafted for detailed Name-specific Analysis.
The app serves as a vibrant portal, allowing users to explore the intricacies of baby names in the United States.

 - **Check out our Rshiny app here -> [RShiny](https://github.com/dootika/class-project-group_20/tree/main/App)**

 ## Obtaining the data

Our dataset, on Rank Table, has been acquired through web scraping from the official Social Security website of the
United States, https://www.ssa.gov (https://www.ssa.gov).
The supplementary layer has been acquired through diligent web scraping from https://www.behindthename.com/
(https://www.behindthename.com/), providing a comprehensive perspective on the historical roots and origin stories
associated with each name.

## Source and Reliability

The Social Security website serves as a trusted repository of demographic data, including comprehensive information on
baby names in the United States. By obtaining our dataset directly from this official source, we enhance the reliability of
our findings, instilling confidence in the accuracy and authenticity of the information presented. To enhance the
trustworthiness of the historical and origin data obtained from https://www.behindthename.com
(https://www.behindthename.com), we conducted a thorough validation process. Importantly, Behindthename.com
provided additional links to support their information, reinforcing the validity of the presented details.

## Limitation

They rise in popularity, enjoy a period of dominance, and then fall. “Emma” and “Liam” will be hot for a while, until suddenly… they’re not. But why? What makes a name suddenly pop—and then die?

The driving force behind these fluctuations is often linked to pop culture. Parents draw inspiration from a myriad of
sources, including their favorite celebrities and characters from best-selling books.
It’s evident that the popularity of names is influenced by a multitude of factors. While analyzing the history and origin of
every name is beyond our scope, we have conducted research on some prominent ones.

**Anomalies :-**
- The female name “Aria” has experienced a surge in popularity, likely influenced by the well-known character from the web series “Game of Thrones.”
- When Kool and the Gang’s song “Joanna” hit the Billboard Hot 100 List in 1984, the name Joanna shot up in popularity. The same thing happened to “Rosanna” after Toto’s song of that name in 1982.
- Political events can also wield influence on naming trends. Following Ronald Reagan’s presidency in the 80s, the name “Reagan”—once relatively uncommon—experienced a notable surge in popularity, eventually securing a place in the top 100 names by 2010.

## Conclusion 

In this project, we delved into the popularity trends of the most favored male and female baby names in the U.S. spanning
the past ten decades. Our exploration encompassed factors such as diverse name choices, variations in initial and ending
letters, and differences in name lengths.

**Methodology:**

For our analysis, we employed metrics such as the total number of babies and the mean rank corresponding to various
factors, providing a comprehensive view of name popularity.

**Key Insights:**
- Biblical Origins Dominating: Mary emerges as the foremost female name, while James and John reign as the  leading male names, all rooted in biblical origins.
- Length Matters: Names with moderate lengths (5, 6, 7 characters) consistently maintain moderate popularity. Distinct short (e.g., Ava) and long (e.g., Christopher) names exhibit heightened popularity among females and males, respectively.
- Initial Letter Influence: The initial “J” stands out as the most popular for males and exhibits considerable popularity among females as well.
- Variety in Female Initials: Females exhibit a broader spectrum of popular initials compared to males.
- Temporal Dynamics of Initial Choices: The preference for initial letters has significantly fluctuated over time for both genders, with only a select few maintaining consistent popularity. 
- Gendered Ending Sounds: Notably, female names predominantly conclude with vowel sounds, while male names typically end with consonants.
- Gender-Neutral Names: While names like Jamie, Jordan, Taylor, Terry, and Willie are popular across genders, their moderate popularity within each gender suggests that parents may not commonly opt for gender-neutral names for their children.
- Increased Variety in Names: Back in 1900, for example, 91% of all children of any gender were given a name from the top 1,000 most popular names. But a century later in 2000, only 75% of girls were given a name from the top 1,000 most-popular girl names, and that percentage had dropped for boys too, to 86%. In other words, more kids were getting names that would have been considered unusual or new. (This data was also collected from ssa.gov)

## Acknowledgement 

We want to express our special thanks of gratitude to our professor Dr Dootika Vats, who gave us this fantastic opportunity
to do this great project of Data Science on “Exploring Trends in Baby Names” and who also helped us out at various
stages and eventually helped us in completing the project with our best efforts and in time. We learnt a lot of new things throughout this project’s journey, and it was an amazing experience for us as a team to understand and implement things
collaboratively.

## References

- https://www.ssa.gov/oact/babynames/decades/names2010s.html
- https://www.behindthename.com/ 





## R Dependencies

- [dplyr](https://cran.r-project.org/package=dplyr)
- [tidyverse](https://www.tidyverse.org/)
- [rvest](https://rvest.tidyverse.org/)
- [shiny](https://shiny.posit.co/)
- [shinydashboard](https://rstudio.github.io/shinydashboard/)
- [ggplot2](https://ggplot2.tidyverse.org/)
- [ggiraph](https://cran.r-project.org/package=ggiraph)
- [DT](https://rstudio.github.io/DT/shiny.html)

## License

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
