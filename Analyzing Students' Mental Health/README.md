# Analyzing Students' Mental Health 🧠📊  

Does going to university in a different country affect mental health?  
In 2018, a Japanese international university conducted a study on its students, publishing findings in 2019 that were approved by several ethical and regulatory boards.  

## Key Findings  
The study revealed that:  
- International students face a higher risk of mental health challenges compared to the general population.  
- **Social connectedness** (belonging to a social group) and **acculturative stress** (stress of adapting to a new culture) are significant predictors of depression.  

## Project Overview  
Using PostgreSQL, this project explores students' data to validate these conclusions and investigates whether the length of stay is a contributing factor to mental health outcomes.  

### Dataset Description  
Below are the fields in the dataset:  

| **Field Name**  | **Description**                                            |  
|------------------|------------------------------------------------------------|  
| `inter_dom`      | Types of students (international or domestic)              |  
| `japanese_cate`  | Japanese language proficiency                              |  
| `english_cate`   | English language proficiency                               |  
| `academic`       | Current academic level (undergraduate or graduate)         |  
| `age`            | Current age of the student                                 |  
| `stay`           | Current length of stay in years                            |  
| `todep`          | Total score of depression (PHQ-9 test)                     |  
| `tosc`           | Total score of social connectedness (SCS test)             |  
| `toas`           | Total score of acculturative stress (ASISS test)           |  

### Objectives  
1. Validate the study's conclusions for international students.  
2. Investigate the impact of the length of stay on mental health.  

![mentalhealth](https://github.com/user-attachments/assets/4d9b3899-dee4-4173-ac82-eb4ce0f1961b)



