Mohamed.EDA2022
================
Asma Mohamed
2022-05-10

# Introduction

Mental health is very important to a person’s overall health and
well-being. Mental health is composed​ of emotional, physiological, and
social aspects of our lives. The recent COVID-19 pandemic has brought a
lot of changes to our lives whether it be work, school, the ability to
leave the house, etc. As a result of these changes, our emotional, and
psychological health, as well as our social lives have been impacted,
and not necessarily for the better health impacts a person’s overall
health and well-being, and this includes a person’s emotional,
physiological, and social aspects of their life. With the recent
COVID-19 pandemic, a lot of changes have been brought into our lives. A
similar study recently aimed to quantify the impact of the COVID-19
pandemic on the prevalence and burden of major depressive disorder and
anxiety (Racine N, McArthur BA, Cooke JE, et al). To address this topic,
we used data sets about SNAP (Supplemental Nutrition Assistance
Program), MDE (major depressive episode), poverty, and reports of
symptoms of depressive disorders. MDE stands for the major depressive
episode; it is a feeling of hopelessness, sadness, etc. For 2 weeks or
longer. SNAP stands for Supplemental Nutrition Assistance Program, it
helps people with a low income to buy nutritious food. Our results may
help us understand the effect of COVID-19 on adults’ mental health in
the United States.​

https://9a7337f8e18e42efbc9024a91973523b.app.rstudio.cloud/file_show?path=%2Fcloud%2Fproject%2FMDEChart.png

# Methods

This project used R Version 4.0.3 and R Studio Version 1.3.1093 (R Core
Team, 2020; R Studio Team, 2020-citation for R). The links are in the
references section, and all graphs were made in R studio.

\- To get the SNAP data, I went to the USDA website, clicked on SNAP
data tables, and downloaded them. The SNAP data was from the SAMHSA
website.

\- To get the poverty data, I went to the US census website and
downloaded based on National Level Statistics of 1980 to 2022.

\- The MDE data came from CDC.org. I downloaded this data set statistics
at the national level from ( U.S. Census Bureau, Household Pulse Survey,
2020-2022).

# Results

![](poverty.data.png)

**Fig.1.** The overall graph trend of the number of people in poverty
from 2016-to 2020.

![](snap.data.png)

**Fig.2.** The overall trend of the number of SNAP users from 2016-to
2020.

![](MDE.Data.png)

**Fig.3.** Number of Reports from Adults of ages 18-80+ who responded
weekly about experiencing symptoms of the depressive disorder from Apr
23 to Dec 30, 2020.

# Discussions

-In (Fig.1). The poverty levels decreased from 2016 to 2019 and then
increased back up starting in 2020. Due to the financial uncertainties
brought on by the COVID-19 pandemic, there was a spike in cases of
poverty, and SNAP users in 2020. There were no cases of COVID-19 in the
US until January 2020. The amount of major depressive episodes have been
increasing from 2016-to 2020, but the biggest increase in depressive
episodes occurred the year the pandemic started which was in 2020.

\- (Fig.3) there’s a decrease then increase in the number of reports
from ages (18-to 29) experiencing most symptoms of depressive order from
Apr to Dec 2020. With the rest of the ages, groups it goes in order
starting from the group 18-29 that reported most depressive symptoms
disorder then following in order with age range. The ages 80+
experienced symptoms were small in the number of reports compared to the
other age group (Fig.3). The graph with Ages that reported symptoms of
depressive disorder and MDEs are correlated shows that the age group
with the most MDEs is 18-29. Approximately 200 or more people ages 18-29
in Fig.3 said they had experienced symptoms of MDE.​ This study by (Lai
et al) found that in hospitals with COVID-19 patients, health care staff
reacting to the spread of COVID-19 recorded high rates of depression
symptoms and distress. The majority of recorded patients with symptoms
of high depression were young adults (Lai et al.). With the increase in
SNAP users and an increase in people in poverty from 2019 to 2020, we
can understand why there is an increase in major depressive episodes,
especially among adults between the ages of 18-29. Mazza et al. (2020)
was the only study that focused on the influence of personality traits
on depression rates during the COVID-19 pandemic. In this study, it was
found that there was a higher rate of depression in young individuals.
This specific group of adults is more vulnerable because your early
teens into your mid to late twenties are very uncertain times in one’s
life.​

\- According this recent study it claimed that individuals have become
less likely to seek care for their mental health issues than before the
pandemic because of concerns about becoming infected with Covid-19 (Kola
L, Kohrt BA, Hanlon C, et al.). There are others aspects of mental
health as to why young adults ages 18-29 are experiencing symptoms of
mental health disorders more than older adult groups. The first aspect
can be social/community. Ages 18-29 like to socialize outside and meet
up with friends more than the ages because of the Covid-19 pandemic this
might have affected them to interact with others due to the lockdown.
The second aspect is finance/income. Young adults between the ages of
18-29 might not have much work experience as the older group above 65+.
Most adults in ages 18-29 who work in retail and have minimum wages or
are still finishing graduate school are not financially able to pay
their rent etc. because of not having a secure job.

# References

R Core Team (2022). R: A language and environment for statistical
computing. R Foundation for Statistical Computing, Vienna, Austria. URL
[\[https://www.R-project.org/\](https://www.R-project.org/.).](https://www.R-project.org/%5D(https://www.R-project.org/.).)

\- RStudio Team (2020). RStudio: Integrated Development Environment for
R. RStudio, PBC, Boston, MA URL <http://www.rstudio.com/.>

\- Shrider, E. A., Kollar, M., Chen, F., & Semega, J. (2021, September
14). Income and Poverty in the United States: 2020. The United States
Census Bureau.
[\[https://www.census.gov/library/publications/2021/demo/p60-273.html​\](https://www.census.gov/library/publications/2021/demo/p60-273.html​)](https://www.census.gov/library/publications/2021/demo/p60-273.html​%5D(https://www.census.gov/library/publications/2021/demo/p60-273.html​))

\- ‌Supplemental Nutrition Assistance Program (SNAP) \\\| Food and
Nutrition Service. (2019). Usda.gov.
[\[https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap​\](https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap​)](https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap​%5D(https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap​))

\- SAMHDA \\\|. (n.d.). Www.datafiles.samhsa.gov.
[\[https://www.datafiles.samhsa.gov/​\](https://www.datafiles.samhsa.gov/​)](https://www.datafiles.samhsa.gov/​%5D(https://www.datafiles.samhsa.gov/​))

\- ‌Centers for Disease Control and Prevention. (2022, March 23). Mental
health household pulse survey - covid-19. Centers for Disease Control
and Prevention. Retrieved from
<https://www.cdc.gov/nchs/covid19/pulse/mental-health.htm> ​

\- ​Racine N, McArthur BA, Cooke JE, Eirich R, Zhu J, Madigan S. Global
Prevalence of Depressive and Anxiety Symptoms in Children and
Adolescents During COVID-19: A Meta-analysis. JAMA Pediatr.
2021;175(11):1142–1150.
\<<a href="doi:10.1001/jamapediatrics.2021.2482\"
class="uri">doi:10.1001/jamapediatrics.2021.2482\</a>\>

\- Lai J, Ma S, Wang Y, Cai Z, Hu J, Wei N, Wu J, Du H, Chen T, Li R,
Tan H, Kang L, Yao L, Huang M, Wang H, Wang G, Liu Z, Hu S. Factors
Associated With Mental Health Outcomes Among Health Care Workers Exposed
to Coronavirus Disease 2019. JAMA Netw Open. 2020;3:e203976

\- Kola L, Kohrt BA, Hanlon C, et al. COVID-19 mental health impact and
responses in low-income and middle-income countries: reimagining global
mental health. Lancet Psychiatry. 2021; 8: 535-550

\- Mazza C., Ricci E., Biondi S., Colasanti M., Ferracuti S., Napoli C.,
Roma P. A Nationwide Survey of Psychological Distress among Italian
People during the COVID-19 Pandemic: Immediate Psychological Responses
and Associated Factors. International Journal of Environmental Research
and Public Health. 2020;17:E3165. doi: 10.3390/ijerph17093165.
