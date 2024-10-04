### Livia Mucciolo

*I am between two project ideas, one has cleaned data but has already been widely published, including an [article on visualizations](https://www.nytimes.com/interactive/2023/12/28/us/migrants-children-data.html) of the data, while the other is more novel but would require more cleaning.*

## Option 1: Court Debt Jailings

### Project Description 
While debtors' prison for private debts is illegal, imprisonment for failure to pay fines, fees, or court debts is commonplace across many states. Often, the debt is not from criminal charges but from traffic and other non-criminal violations. High-profile investigations in Missouri and Mississippi over the last decade have uncovered the frequency with which courts imprison court debtors, with little to no regard for their ability to pay. These practices often serve as monetary punishment for the poor, who have the most to lose from being imprisoned. 

Before coming to CAPP I used to [research](https://www.urban.org/sites/default/files/publication/105331/following-the-money-on-fines-and-fees_final-pdf.pdf) the prevalence of fines and fees across the US and their impact on state and local government budgets. Through this project, I hope to expand my knowledge of this topic and understand the prevalence of court debt jailings as well as what minorities are most affected. 


### Data Sources
My main data source comes from the reproduction materials for "Forgotten but not gone: A multi-state analysis of modern-day debt imprisonment" paper ([Github](https://github.com/stanford-policylab/debt), [website](https://policylab.hks.harvard.edu/debtors-prisons/)). The authors provide R/Python code to download the data bulk and tutorials on how to recreate the findings. The datasets include individual jail booking information from counties across Texas and Wisconsin. The datasets indicate (where available) each arrestee’s race, ethnicity, sex, age, state, ZIP code, booking date, release date, and release type, as well as each charge’s description, severity, and whether it represents a “failure to pay". There are about 4 million observations split across both states.

### Questions

* Should I limit my project to just one state, or would the work be more powerful by including both states?
* Is it worth adding additional information on demographics (using data from the census)?

## Option 2: Unaccompanied Migrant Children

### Project Description 
Unaccompanied child migrants are children or adolescents who enter the US without a legal guardian and legal immigration documents. Over the last 10 years, there has been a surge of unaccompanied minors crossing the border, especially those coming from Central and South America. Once they reach the US the Department of Health and Human Services is responsible for their placement with an adult sponsor. While about a third of minors are reunited with their parents, the rest are sent to live with other relatives or even strangers. Placement with non-parent strangers can put migrant children in vulnerable positions. Many are expected to find work and help their families back home, despite not being of legal working age.

In 2023, the New York Times published a series of articles detailing the reach of migrant child labor across the US. The author (Hannah Dreier) collected data from the Department of Health and Human Services through FOIA requests to help find locations in the US with high concentrations of children living far from their close relatives. These locations informed her of potential spots where children were being exploited. For this project, I will use the publicly available data to understand better where migrant children are living and to identify any trends based on country of origin, and across the years as the American political landscape has shifted.


### Data Sources
My main data source comes from the Githhub [(here)](https://github.com/nytimes/hhs-child-migrant-data) NYT published. They provide cleaned data from Jan 2015 - May 2023 of a child's gender and country of origin, date of entrance to the United States, date of release to a sponsor, relationship to that sponsor, and the ZIP code to which the child was released. There are about 550,000 rows. 

