## Predictive Analysis on Years of Employment

### Team

Point of contact: Tian Tian (Github id: MayliaCypher)

Ayush Saseendran (Github id: ayushsaseendran)

Yoon Lee (Github id: oliveingithub)

Francesca Fan (Github id: ffan04)

### Introduction

In today's work landscape, the significance of human resources cannot be overstated. However, investing in human resources also involves a considerable amount of time and resources, particularly in terms of training and development. Understanding the patterns and predictors of employment duration can greatly benefit companies across various industries by enabling better workforce planning and targeted policies. Additionally, for individuals, it can lead to enhanced career guidance and opportunities for personal growth.

### Goals

This project aims to leverage multiple waves of Real-Time Population Survey (RPS) data to develop a predictive model for years of employment across different regions and industry sectors.

Potential variables to be considered in the analysis include region of residence, state of residence, employment status, industry sector, employer type, job tenure, usual hours worked, actual hours worked, days working, days commuting, and more.

### Literature Review

Many companies have realized that losing a good employee takes a toll, but many times they don't realize the importance of reducing employee turnover. (Smither, 2002) Employment duration is closely linked to employment stability and prospects, which are critical for both organizations and individuals.
For these reasons, our project looks to leverage workplace-specific predictors to improve the accuracy and relevance of the Years of Employment forecasting model. By incorporating region-specific and industry-specific factors, we aim to provide organizations and individuals with more targeted and actionable insights in workforce planning and career development.

### Novelty and Success Factors

While existing studies may have explored predicting years of employment, our project aims to stand out by incorporating work environment specifics into our predictive model. By doing so, we believe our approach will provide more accurate and contextually relevant predictions.

By focusing on specific work environment factors, we aim to offer insights and predictions that are more tailored to the unique characteristics of different regions and industry sectors.

### Stakeholders and Impacts

Key Stakeholder: Company's personnel department. They need to know ahead of time what each employee is likely to be planning for and to organize their resources based on that information.

Industry to create better policies (maybe related to the government too). E.g., if the prediction shows a shorter amount of years than realistically needed, help spot what the problem is and implement policies that could encourage to stay longer. 

Years of employment are also important for Individuals to build a career path they are satisfied with. Identifying the predictors of years of employment and predicting years would help them plan out the right timing to change work environment, and jobs, or plan out their liver accordingly. 

### Data and methods 

For this project, we will use multiple waves of the RPS. Using years, region of residence, state of residence, employment status, industry sector, employer type, job tenure, usual hours worked, actual hours worked, days working, days commuting, etc., we hope to find a pattern in the years of employment. 

RPS data, in large, can be divided into two parts: data on employed individuals and the unemployed individuals. For the purpose of this project, we will only be using the employed individuals’ data. The data consists of more than 12 columns that can be used and 50,000 rows for each wave. 

To predict the employment years by regions and industry sector, we will employ machine learning techniques such as random forests, gradient boosting machines, and neural networks. 

### Risks 

The potential risk of this project is the RPS data not being sufficient to predict the employment year by region and industry sector. Also, there is a possibility that solely relying on the RPS data will limit capturing years of employment patterns amidst the everchanging job market. 

In order to mitigate such risks, we have already proposed using multiple waves of the RPS data. Yet, should it come to a point where we find that RPS data is not robust enough, we will find relevant data and add it to our analysis. 

### Weekly work schedule / Coordination of the work
					
| Week              | Details                  |Milestone|
|---|---|---|
| W 6/ CP 1 DUE   | Select topic, dataset, and work on the proposal   |  Identify the required data set. Then prepare the project proposal |
| W 7  | Merge data | Begin merging the selected datasets to create a unified dataset for subsequent analysis |
| W 8 | Clean data	Talk about outliers and missing data together   | Handle outliers and missing data to ensure data quality. Identify needed features and perform data culling |
| SPRING BREAK | Descriptive analysis    | Perform basic statistical descriptions, visualizations and preliminary exploratory analyses of data |
| W 9/ CP 2 DUE | Prelim model runs	| Begin building and training predictive models, and perform initial evaluations of the models |
| W 10-11 | finetune  | The model is tuned, including adjusting model parameters and feature selection |
| W 12 |  Try models  | Try more types of models further and compare their performance |
| W 13 | More models  | Meticulous tuning and optimization of the final model to achieve the best prediction |
| W 14/ CP 3 DUE | Work on deliverable | Complete preparation of project deliverables, including writing final reports, preparing presentations or demonstrations, and ensuring that all tasks are completed as planned |

### Reference 

Smither. L (2002). Managing Employee Life Cycles to Improve Labor Retention. https://ascelibrary.org/doi/abs/10.1061/(ASCE)1532-6748(2003)3:1(19)
