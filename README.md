# NYC Schools clustering

Unlike other school districts in major cities in the U.S., New York City schools tend to be so diverse that there is no outstanding race/ethnicity among students. Because of this,
trends concerning race/ethnicity are relatively trickier to explore, compared to other school districts. 

As an example, we know that high-poverty schools tend to be majority Black or Hispanic in Chicago. We also know that, when immigration raids escalate, attendance declines in schools in communities with a high Hispanic population. 

Using K-means clustering, we grouped NYC schools based on student demographic data to see which are similar in composition. 

The clustering could then be used to expand the analyses of other key education metrics, such as test scores, graduation rates, or chronic absenteeism, and explore whether trends emerge within these clusters.

Data used for this project are from the [NYC Schools website](https://infohub.nyced.org/reports/students-and-schools/school-quality/information-and-data-overview).

## Clusters

Cluster 0: at least half the students are Asian/Pacific Islander (51.4%), significant Hispanic population (26.7%)
Cluster 1: at least half the students are Hispanic (53.7%), significant Black population (31.8%)
Cluster 2: majority Hispanic (77.3%)
Cluster 3: majority Black (66.5%)
Cluster 4: predominantly white (42.4%), with a significant Hispanic (25.6%) and Asian/Pacific Islander (17.6%) populations

--

This project was developed as a requirement for the Secure AI class at the Craig Newmark Graduate School of Journalism at CUNY, under the instruction of [John Templon](http://github.com/jtemplon/).