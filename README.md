# Data analysis portfolio
## Projects

**Analyzing the increased rate of customers cancellation**
Code: [cancellation-analysis.ipynb](https://github.com/EduardErich/Data-Analysis-Portfolio/blob/main/Cancellation-causes/Cancellation-analysis.ipynb)
Objective: The company recently realized that of its total customer base, the majority are inactive customers, that is, those who have already canceled the service.
In order to improve its results, the company wants to understand the main reasons for these cancellations and what are the most efficient actions to reduce this number.
Description: This project reads a database of customers, which contains some data, like age, gender, their plan, the time they are our customers, the amount of callcenter calls, etc.... The first step was to load this dataset, look for null and/or useless values and cleaning it. Next, the start point is realizing how much of the customers canceled the services.
Once we find how bad the situation is, we proceed comparing every variable with the cancellations, to see if there are any correlations. For example, there is a problem with the callcenter calls. Customers that received more than five calls are certainly canceling the services. Right after finding all the problems, we simulate what the results would be, considering the company has taken the proper actions. Just by fixing 3 problems, the rate fell from 56% to 18%.
