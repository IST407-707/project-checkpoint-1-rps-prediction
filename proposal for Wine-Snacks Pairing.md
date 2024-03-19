## Recommendation system for Wine-Snacks Pairing

### Team

Point of contact: Tian Tian (Github id: MayliaCypher)

Ayush Saseendran (Github id: ayushsaseendran)

Yoon Lee (Github id: oliveingithub)

Francesca Fan (Github id: ffan04)

### Introduction
This project aims to develop a user-friendly wine-food pairing recommendation system using machine learning techniques. By leveraging data on wine characteristics such as sweetness, acidity, tannins, alcohol content, body, flavor intensity, identity, and finish, along with information on the main flavors of various foods, the system seeks to demystify and optimize the wine and food pairing process.

### Goals

The aim of this project is to develop an intuitive system that provides wine pairing suggestions for various foods, with a focus on cheese or chocolate.
We want to use machine learning algorithms to analyze the characteristics of wines and foods and provide personalized suggestions based on user preferences.

By taking into account factors such as sweetness, acidity, and flavor, we are able to ensure optimal pairings that enhance the wine pairing experience and give users a comprehensive understanding of the principles of wine and food pairing, enabling them to make informed choices and enhance the dining experience.

### Literature Review

Food recommendation systems using machine learning have already been proposed in various contexts (e.g., Phanich et al., 2010; Toledo et al., 2019). As seen from prior literature, many food recommendation systems focus on recommending customized diets for patients. The techniques used in these literature start with clustering and then incorporate tools for filtering out foods that are not appropriate, AHPSort to make multi-criteria decisions. 

Similar techniques are used in food recipe recommendation systems (Vivek et al., 2017) or food and restaurant recommendation systems (Melese, 2021). However, there is only a few research on using recommendation systems for daily use. In particular, while there are many wine recommendation systems, there rarely is research on wine-food paring. Yet, primarily using a class project report on wine recommendations for meals using JOSHUA (Javanmardian, 2005) as our main resource, we plan to incorporate the approach of this article but apply and refine it to wine and snack pairing. 

### Novelty and Success Factors

Based on existing research on wine recommendation systems, we plan to adapt and refine our approach to wine and food pairing. By incorporating techniques from previous studies and adapting them to our specific situation, we aim to develop a robust and effective recommendation system that meets the needs of users seeking guidance on wine and food pairing for everyday use.

### Stakeholders and Impacts

Individuals: first and foremost, it would be a user-friendly system that anyone can use to have the best wine experience. 

Wine industry: 1) demystify that wine is hard. But also 2) promote the best way to enjoy the wine and the wine itself.  

Potentially restaurants or wine retailers too. 

### Data and methods 

For this project we need two sets of data: wine and food. There are multiple datasets that we can use for wine. For now, we are looking at two different datasets. Wine Enthusiast Dataset has at least 8 columns that we could use in categorizing the wine containing 130,000 rows. Another dataset is from UC Irvine that contains 13 columns including alcohol, malic acid, ash, magnesium, and so forth. 
As for the food data, we do not have the dataset yet but we are also open to narrowing down our focus to chocolate or cheese so it is easier to label. 
After obtaining the appropriate dataset, we will use machine learning techniques such as feature engineering, classification algorithms (clustering), and recommendation systems to predict optimal pairing. 

### Risks

Systems may inadvertently encourage or facilitate abnormal alcohol intake. It is important to ensure that the system encourages responsible drinking and that rules or warnings about alcohol consumption are in place. The system may not be able to satisfy all users due to differences in individual perceptions of taste, which may limit the usefulness and appeal of the system.

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

M. Phanich, P. Pholkul and S. Phimoltares, "Food Recommendation System Using Clustering Analysis for Diabetic Patients," 2010 International Conference on Information Science and Applications, Seoul, Korea (South), 2010, pp. 1-8, doi: 10.1109/ICISA.2010.5480416. keywords: {Diabetes;Medical treatment;Ontologies;Diseases;Humans;Mathematics;Performance evaluation;Medical control systems;Control systems;Blood},

R. Yera Toledo, A. A. Alzahrani and L. Martínez, "A Food Recommender System Considering Nutritional Information and User Preferences," in IEEE Access, vol. 7, pp. 96695-96711, 2019, doi: 10.1109/ACCESS.2019.2929413.
keywords: {Recommender systems;Optimization;Proposals;Diseases;Task analysis;Tools;Planning;Daily meal plan recommendation;user preferences;nutritional information;multi-criteria decision making;recommender systems},

Amanuel Melese. (2021). Food and Restaurant Recommendation System Using Hybrid Filtering Mechanism. North American Academic Research, 4(4), 268-281. doi: https://doi.org/10.5281/zenodo .4712849

Vivek, M.B., Manju, N., Vijay, M.B. (2018). Machine Learning Based Food Recipe Recommendation System. In: Guru, D., Vasudev, T., Chethan, H., Kumar, Y. (eds) Proceedings of International Conference on Cognition and Recognition . Lecture Notes in Networks and Systems, vol 14. Springer, Singapore. https://doi.org/10.1007/978-981-10-5146-3_2

Javanmardian, K. (2005). A wine paring recommendation system. https://mitocw.ups.edu.ec/courses/electrical-engineering-and-computer-science/6-871-knowledge-based-applications-systems-spring-2005/projects/javanmardian_pap.pdf

