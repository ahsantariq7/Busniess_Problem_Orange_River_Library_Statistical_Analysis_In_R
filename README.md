# Busniess_Problem_Orange_River_Library_Statistical_Analysis_In_R

Task 1 (10 points)

The data set in its current form is not ready to address the business problem. Specifically, fix the following issues.

⚫ identify key variables that should be included in analyses to respond to the business problems. For these variables, justify and implement a solution to deal with the missing values. Consult the data dictionary to determine if there is a special kind of missingness for the variables. Create the target variable of visits per 100 individuals in the legal service area, Use visualizations

to determine if any transformations should be made or to identify any outliers. Justify any

transformation or any action taken to address outliers. . Many of the other continuous variables can also be turned into rates per 100, such as employee numbers, collection size, and the number of programs. Create rates per 100 versions of these variables. Use visualizations both univariate and against the target variable to justify possible transformations of these variables.

Perform a general cleaning and data validation for the data set. Write the technical data preparation section of your report. Because none of your code will be available to the reader, all evidence of the data preparation tasks must be contained in your report. This may include written descriptions as well as charts, however the work is most effectively conveyed.
Task 2 (2 points)

Address the issue of target leakage in the data. Are there variables that should not be used for prediction because they cannot be measured prior to the target variable being measured? Perhaps these are variables that are observed along with visits as opposed to numbers that can be planned in ahead. Be sure to not include those variables in the predictive models you will be building.
Task 3 (8 points)

The first business problem is to determine what factors are most associated with library visits. Address this problem in the following two ways.

    Build a linear regression or generalized linear model and tune the model appropriately. Use p-

values and test statistics to make conclusions as to which variables are important in the model. 2. Build a random forest model. Use feature importance measures and partial dependence plots to show the effect of the factors on library visits. Interpret the partial dependence plots appropriately.

Determine where the conclusions of the two models agree or disagree. Write a section of your technical report where you describe the models used and use the model output to answer the first business problem.
Task 4 (4 points)

The second business problem is to determine spending distributions for libraries similar to the Orange River Public Library. Instead of using a predictive model to answer this question, aggregate and summarize the data in useful ways. Filter the data in such ways as create a small subset that is appropriate for answering the question and provide a table and summary that will address the question. Use only libraries where the population in the legal service area is within 2,000 individuals for that of Orange River County Library's legal service area.

Write a section of a technical report where these conclusions are given and justified.
Task 5 (8 points)

The third business problem is to provide a range of predictions for expenses of the library based on the new features given. Build a Bayesian linear model to address this final question. The information provided in the business problem does not completely match the data given, so when building your model, be sure to use only variables that can be used for the prediction. If you use priors that are not the default priors, justify your choice of priors.



https://github.com/ahsantariq7/Busniess_Problem_Orange_River_Library_Statistical_Analysis_In_R/assets/109543910/aeafe49a-e52a-4d3f-b778-f75154f4a7b1




Write a section of the technical report that describes the model being used and provides and interprets the output that answers the business problem.
