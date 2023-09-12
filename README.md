# NESS-Statathon-2022---Theme-1-Predicting-Policy-Cancellations
**#Overview**
This project is part of the 2022 NESS Statathon (Theme 1) and focuses on predicting property insurance policy cancellations using historical policy data. The goal is to create a multiclass predictive model to predict policies that are most likely to be canceled and those most likely to be renewed. Additionally, the project aims to identify the variables that are most influential in causing policy cancellations.

**#Dataset Description**
The dataset used in this project is based on four years of property insurance policies from 2013 to 2017. It contains approximately one million policies in the training data, with each policy having a single observation. During the effective term, nearly 230,000 policies were canceled. Key variables in the dataset include:

id: Policy ID (not used in the model)
tenure: Number of years with Kangaroo
claim.ind: Occurrence of a claim (0=no, 1=yes)
n.adults: Number of adults in the property
n.children: Number of children in the property
ni.gender: Gender of the policyholder
ni.marital.status: Marital status of the policyholder (0=no, 1=yes)
premium: Price of the policy
sales.channel: Medium through which the policy was purchased
coverage.type: Type of coverage
dwelling.type: Type of dwelling
len.at.res: Length at residence (how long the policyholder lived at the property)
credit: Financial credit level of the policyholder
house.color: Color of the house
ni.age: Age of the policyholder
year: Year of the policy
zip.code: Zip code of the property
cancel: Cancellation indicator (0=not cancel, 1=may cancel but can be convinced, 2=cancel). This is the response variable.
Please note that rows where cancel is -1 have been deleted.

**#Project Goals**
The primary objectives of this project are as follows:

Build a predictive model on the training data to predict policy cancellations.
Use the best-performing model to predict the cancellation indicator for each policy in the test data.
Calculate the performance of the model on the test partition using the weighted F1 score as the evaluation metric. The weighted F1 score can be calculated using scikit-learn's f1_score.
Getting Started
To get started with this project, follow these steps:

Download the dataset and save it to your local machine.

Install the necessary Python libraries, such as Pandas, NumPy, Scikit-Learn, and any others you may need for data analysis and modeling.

Clone this GitHub repository to your local environment:

bash
Copy code
git clone https://github.com/manas04/ness-statathon-2022-theme1.git
Navigate to the project directory:

bash
Copy code
cd ness-statathon-2022-theme1
Start working on your predictive model, analyzing the data, and building your code.

**#Usage**
Provide instructions on how to use the code, how to train the model, make predictions, and evaluate the model's performance.

**#Evaluation**
The performance of the predictive model will be primarily based on its accuracy and the quality of the code. Use the weighted F1 score as the primary evaluation metric for your model's performance on the test partition.

**#License**
This project is licensed under the MIT License - see the LICENSE file for details.

**#Acknowledgments**
The NESS Statathon organizing committee for providing the dataset and the opportunity to participate in this challenge.
**#Contact**
If you have any questions or suggestions, please feel free to contact us:

Name: manasj9507@gmail.com 



