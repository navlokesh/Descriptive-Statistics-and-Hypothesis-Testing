# Descriptive statistics and Hypothesis Testing:
A descriptive statistic is a summary statistic that quantitatively describes or summarizes features from a collection of information, while descriptive statistics is the process of using and analysing those statistics.
We will check different ways to explore the data for exploratory data analysis using univariate and bivariate data analysis.

Please check the jupyter notebook for a detailed discussion on this.

Teh dataset was used to illustrate this as below is the brief of our analysis:

#### Region:
We can see that the Region 'Other' has higest spends.
If we consider the region 'Other' as multiple regions put together, we may say that the particular region 'Lisbon' has highest spends.
#### Channel:
The Channel 'Hotel' has the highest spends
#### Lowest Spends:
#### Region:
The Region 'Oporto' has lowest spends.
####Channel:
The Channel 'Retail' has the lowest spends.

### We can further dive in and perform various hypothesis tests on this data.
There are 6 different varieties of items are considered. we checked if all varieties show similar behaviour across Region and Channel.

#### A p-value table was created after using t_statistic on all of our variables. Below is the p-value table:

![image](https://user-images.githubusercontent.com/33120664/222853272-e0e098e5-8070-468f-b731-5ef7b07a9a91.png)

We can utilize this table to formulate and conclude hypothesis tests at different alpha-levels.
For example:
#### At alpha level of 5%:
![image](https://user-images.githubusercontent.com/33120664/222853454-f4a2949c-3696-4764-b51f-317f7b864aee.png)

#### At alpha level of 1%:
![image](https://user-images.githubusercontent.com/33120664/222853480-74e3a498-45d4-4856-a307-e2a768677683.png)

#### At alpha level of 10%:
![image](https://user-images.githubusercontent.com/33120664/222853500-dcba30bd-3d2d-4ed9-b83e-2bb7929c8056.png)

Few of the hypothesis tests are as below:
### Hypothesis:
#### Null: The varieties show similar behavior across Regions and channels
#### Alternate: The varieties so not show similar behavior across Regions and channels
#### Across Channels:
From the above tables, we can see that the varieties Fresh, Milk, Grocery, Frozen and Detergents_Paper do not show similar behavior accross the channels Hotel and Retail, at 95%, 99% and 90% confidence.
The variety Delicatessen shows similar behavior across the channels.
#### Accross Regions:
All of the varieties show similar behavior across the Regions at all the 3 significance levels (for alpha 0.05,0.01 and 0.1)


### On the basis of the descriptive measure of variability, we can check which item shows the most inconsistent behaviour and which items shows the least inconsistent behaviour.

By caluculating the co-efficient of variation, we can infer the following:
#### Most inconsistent : Delicatessen
#### Least inconsistent : Fresh

We also get to see there are number of outliers in the data. We need to be carful when we use this data for distance based calculations as value of mean would largly depend on the magnitude of the data.
Below is the snap of boxplot for few variables:

![image](https://user-images.githubusercontent.com/33120664/222854026-0c1b2a75-8d70-4b82-82d0-ad841c4cde1f.png)


### After such analysis, we can provide recommendations based on the report as below:
From the data, We can see that the region for most of the Buyer/Spender is given as 'Other'. The company need to work on specifying the region instead of providing the region as 'Other'. This will help in better studies of the data, drawing inferences and making conclusions based on the study.

It is highly recommedned that the process of conducting the investigation needs to be improved and made more reliable to conduct statistical tests and drawing better inferences.

It is necessary that the various variables in the data sets are re-visited and re-tested for better reliability.

From the co-efficient of variation of the varieties, we can see that all of the varieties are inconsistent. Need to work on the consistancy of the varieties.
All of the varieties except Delicatessen do not show similar behavior accross the channel. The company need to investigate the behavior of varieties and compare them across the the channels to understand why we do not see similar behavior of varieties across the channels..

Note: Please check the jupyter notebook from files section of the repository to understand the coding aspect of above analysis in python.
