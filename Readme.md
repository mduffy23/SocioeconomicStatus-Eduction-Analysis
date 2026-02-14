# Socioeconomic Status and Education

## Project Overview

A state government wants to know if socioeconomic and demographic factors generally affect a student's success. They believe if these factors affect student success during high school, it will also often set a trajectory for their life outcomes. Changing educational norms and implementing new strategies and programs to best educate people of different backgrounds could enable social mobility like never seen before.

The government wants to know how these factors affect a student's academic success, but also more unorthodox measures of success like their sense of belonging and engagement in school. Academic achievement is a straightforward indicator of success in today's society but feeling part of something bigger than oneself and engaging in one's community are some of the most important things one can do in their life. If there are substantial influences on unorthodox success metrics, corrective action should be taken.

## Dataset

**Provider:** The National Center for Educational Statistics (nces.ed.gov)

The National Center for Educational Statistics offers many long-term studies on education. The datasets contain categorical data (like sex, race, religion, region), continuous variables (like GPA, math test score, school sense of belonging, school engagement, and socioeconomic score), and ordinal data (like socioeconomic quintile and family income level).

**Source**: High School Longitudinal Study of 2009

The dataset describes students that started high school in 2009 and studied them throughout their high school years and into college. The dataset contains information about the student (GPA, math test scores, sense of belonging, sense of engagement, race, sex...), but also their socioeconomic status, family income, parent education, and many more.

**Size**: 
- ~25,000 records
- Over 9,000 columns (used only 15)

## Methodology

For this analysis, I will employ exploratory data analysis (EDA), cluster analysis, and logistic regression to address the research question. EDA will reveal important insights about the data and what relationships likely exist through visualization of relationships. Cluster Analysis will uncover the natural structures within the data. The cluster solution could confirm if socioeconomic metrics often coincide with student success measures, designating an association between them. Lastly, I will use logistic regression to explore the relationships between socioeconomic/demographic factors and student success more granularly. Logistic regression robustly examines relationships between both continuous and categorical variables and offers clear metric indicators of the extent and significance of those relationships (via coefficients and p-values).

### Variables Used

Our subset of columns contains:

- Student ID
- Socioeconomic status composite
- Quintile coding of socioeconomic composite
- Total family income from all sources 2008
- Parents'/guardians' highest level of education
- Parent 1: employment status
- Mathematics theta score
- GPA for all academic courses
- Ever dropout
- Student's sex
- Student's race/ethnicity
- Poverty indicator (relative to 100% of Census poverty threshold)
- School locale (urbanicity)
- Scale of student's sense of school belonging
- Scale of student's school engagement