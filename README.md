# DS3001_project

Student outcomes (graduation rate, income)


Data Wrangling/EDA Tasks: 

1. What is in your data? Lily

The College Scorecard 2022-2023 dataset provides detailed information on higher education institutions across the United States. When we downloaded the data from the US Department of Education, the file was too large to upload to Github so we chose specific variables of interest and combined them into a dataset to use for this project. It includes data on institutional information, student aid, enrollment, cost, and student outcomes. By offering insights into these factors, the dataset helps assess the accessibility, affordability, and effectiveness of universities. This dataset is a valuable resource for analyzing patterns in higher education, allowing us to investigate factors that influence student success and performance.

**Data Dictionary**

| Variable | Description | Type |
|-----------------|-----------------|-----------------|
| ACTCMMID   | Midpoint of the 25th and 75th percentile ACT cumulative scores   | Numeric   |
| ADM_RATE   | Admission rate   | Numeric   |
| C150_4   | Completion rate for first-time, full-time students at four-year institutions (students completing a 4-year degree within 150% of the expected time)| Numeric   |
| CONTROL_PEPS   | Whether the institution’s governance structure is public, private nonprofit, or private for-profit | Categorical |
| COSTT4_A   | Average cost of attendance (academic year institutions)   | Numeric |
| FAMINC   | Average family income   | Numeric  |
| FEMALE   | desc   | type   |
| GRAD_DEBT_MDN_SUPP   | desc   | type   |
| INSTNM   | desc   | type   |
| MD_EARN_WNE_4YR   | desc   | type   |
| PCTFLOAN_DCS_POOLED_SUPP   | desc   | type   |
| PCTPELL_DCS_POOLED_SUPP   | desc   | type   |
| PPTUG_EF   | desc   | type   |
| PREDDEG   | desc   | type   |
| REGION   | desc   | type   |
| STABBR   | desc   | type   |
| STUFCAR   | desc   | type   |
| UG   | desc   | type   |
| UNITID   | desc   | type   |
| ZIP   | desc   | type   |

2. How will these data be useful for studying the phenomenon you're interested in? 


  The College Scorecard 2022-2023 dataset  will help us investigate the question of whether college is a "scam" and what factors contribute to the perceived value of higher education. Comparing MD_EARN_WNE_4YR against tuition costs can reveal whether graduates from certain institutions earn significantly more, supporting or challenging the idea that more expensive schools lead to better financial outcomes. Analyzing COSTT4_A and FAMINC in relation to affordability and using GRAD_DEBT_MDN_SUPP to evaluate student debt burden will further inform whether the cost of education is justifiable by financial stability after college. 
  
   We are also interested in studying the demographic and institutional differences between colleges. For instance, CONTROL_PEPS will facilitate comparisons between public and private institutions, while REGION and STABBR will highlight geographic influences on educational outcomes and costs. Metrics like PCTFLOAN_DCS_POOLED_SUPP and PCTPELL_DCS_POOLED_SUPP will provide insights into financial assistance and socioeconomic disparities among students. Including gender demographics through FEMALE can also reveal differences in educational outcomes based on gender. Ultimately, this comprehensive analysis will address questions about whether colleges operate more as businesses than educational institutions, and whether the current system perpetuates neoliberal values at the expense of educational equity and quality. 

4. What are the challenges you've resolved or expect to face in using them? Together
   
Visualizations: Eva, Rachel, Siobhan, Noya
