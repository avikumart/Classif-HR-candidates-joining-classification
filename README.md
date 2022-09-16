# Classif-HR-candidates-joining-classification-project

This dataset was part of recruitment process of a perticular client of ScaleneWorks. ScaleneWorks supports several information technology (IT) companies in india with talent acquisition. One of the challange they face is about 30% of the candidate who accept the jobs offer, do not join th compnay, this leads to huge loss of revenue and time as the companies initiate the recrutiment process again to fill thw workforce demand.  SceleneWorks wants to find out if a model can be built to predict the likelihood of a candidates along with a column that indicates if the candidate finally joined the company or not.

## Dataset feature description
1) Candidate - Unique reference number to identify candidate
2) DOJ Extended - Date of joining asked by candidate or not
3) Duration to accept offer - Number of days taken by th candidate to accept the offer
4) Notice period - Notice period served before candidate can join the company
5) Offered band - Band offered to candidate based on experience, performance
6) Pecent hike expected in CTC - Percentage hike expected by the candidate
7) Percent hike offered in CTC - Percentage hike offered by the company
8) Percent difference CTC - Difference between expected and offered hike
9) Joining Bonus - Joining bonus is given or not
10) Candidate relocate actual - Candidates have to relocate or not
11) Gender - Gender of the candidate
12) Candidate Source - Source from which resume of the candidate was obtained
13) Rex in Yrs - Relevant years of experience
14) LOB - Line of business for which offere was rolled out
15) Location - Company location for which offer was rolled out
16) Age - Age of the candidate
17) Status - Target varible whether the candidate joined or not

## Objectives and Tasks

- Analyse and visualize HR joinee dataset to find insights on jon applicants
- Use SMOTE technique to solve unbalanced class classification problem
- Using various classification models find best models to predict candiates's joining chances and classify their joinee status

## Approches and techniques 
1) Firsly, Decribe the summary of dataset, find is any missing value is there or not and clean dataset
2) Exploratory data analysis to find and visualize insights such as distribution of numerical fields their relationship with candidates' joinee status
3) Used pie chart, column charts to find candidate's jon preferences and percentage of offer band share
4) Pre-proceesing of dataset using List comprehansions, OneHotEncoder and SMOTE to balance the classes of dataset
5) Built logistic regression model as baseline 72% accuracy 
6) Built ML pipeline of 8 different models using gridsearhCV to find best model which was GradientBoostingMachine with 86% accuracy.

## Learnings from this project
1) Learnt various techniques to explore datasets like pivot table, pandas pivot, groupby functions and matplolib chart components to visualize insights derived
2) Learnt to use SMOTE technique to deal with imbalanced class classification problems
3) Learnt to use GridSearchCV technoque to tune the hyperparameters to improve the accuracy of models.
4) Learnt scikit-learn's feature importance technique to decide which 'attribute' is most important in predicting candidates' joinee status

## Technology used
- Python
- Scikit-learn
- Pandas
- Numpy
- matplotlib

## License

[Appache](https://choosealicense.com/licenses/apache-2.0/)
