# Student Loan Risk with Deep Learning

## Overview
The objective of this project is to create a model to predict the likelihood that an applicant will repay their student loans.  Provided is a CSV file that contains
information about previous student loan recipients, such as credit ranking.

## Model
The model selected uses machine learning and neural networks to predict if an applicant will repay their student loan.  EDA was performed using a Jupyter notebook with the following libraries:

![Screenshot 2024-07-23 152531](https://github.com/user-attachments/assets/fb264897-64fc-4683-94cf-d44925e7fb58)

## Considerations

**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**
The data needed would be financial data, household income-related data, employment data, credit history, major/minor and it should be specific to the student.  I think past loan repayment history should 
be weighed the highest.  Other factors that compare students similar to the student 
should be considered but not as high as the students personal repayment history.

**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**
I would consider using a combination of collaborative, content-based and 
context-based filtering.  When predicting repayment of a loan I think the 
students personal credit history should be considered first, and then the student
as compared to their peers as well as contextual data should be considered. 

**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**
One real-world challenge would be how lay-offs would affect a student's ability
to repay their loan.  Especially, during times of economic crises such as 
pandemics and recessions.  

Another challenge would be a personal finanical hardship for the student.  For
instance, a student could have fallen into health issues or death, preventing 
them from repaying the loan.
