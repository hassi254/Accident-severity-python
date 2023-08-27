# Accident-severity-python
Scope of the Project:
In this project, with the help of Python programming language, we selected accidents, casualties, and vehicles datasets from the “UK Department For Transport” website (link to the website: https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data). In our group of four, we collected road safety data for 2021.
We acted as a team of data analysts for the company ‘Street Safe Solutions’ (we came up with this name), to predict the severity of accidents; fatal, serious, or slight. 
Group Analysis: 
In this part of the project, we carried out the process of data cleaning and preprocessing, where insights and basic statistics about the datasets were generated after merging them. After merging the datasets, we generated approximately 150,000 rows and 81 columns. After dropping the null or duplicate values, we were left with approximately 55000 rows. On the other hand, using the provided data guide on the website, we chose 24 important columns related to our problem statement (mentioned in the ipynb file). 
Since our supervisors decided that we should work with 8000 to 10,000 rows, we randomly selected those using python inbuilt functionality. After that, we performed descriptive statistics and univariate/bivariate data visualization to get a better understanding of our data. Then, with the help of the correlation concept, we figured out the top 5 features affecting the severity of accidents.
Individual Analysis:
In this part of the project, we were obliged to apply Machine learning techniques to deduce the performance of each of the models used, and which model provides the best estimate for our problem, so that, as a data analyst, we can report to the upper management where they should focus the companies’ resources for the better outcome. 
Firstly, the data was split into a training and testing set and more exploration was carried out. After that, Linear regression between two continuous variables was run. No good insights were generated from that. Since our data mostly had categorical features, therefore, considering it as a classification problem, we applied different techniques of dummy variable encoding, so that our variables can be used for machine learning models: Logistic regression, decision tree classifier, random forest classifier, and support vector machine. Furthermore, we used different methods for cross-validation and hyperparameter tuning, keeping in mind the requirements of the model.
Finally, an evaluation of the model was carried out, and based on that, we provided conclusions and recommendations to the team and managers. 
Usefulness of the project:
This project can help data scientists and business analysts to make informed decisions and more secure insurance policies. 
This project can help individuals learn more deeply about how the machine learning models work and they can apply those techniques into their own choice of projects.

