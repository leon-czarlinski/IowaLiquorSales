# IowaLiquorSales
_Unlocking the Spirits of Iowa_ is a hands-on project focused on unveiling patterns in liquor sales across Iowa. Build alongside with my two college peers, Amos Chew and Ezekiel Oluwole, the project aims to provide insightful analytics on liquor sales patterns and contribute using machine learning methodologies for valuable data-driven decision-making in the retail liquor industry.

## Data Analytics Methodology
**Transforming data into insights**: the six steps of data analytics include: *ask*, *prepare*, *process*, *analyze*, *share*, and *act*. 
1. **Ask**: effective questions and collaborate with leaders and managers who are interested in the outcome
1. **Prepare**: It all start wth a solid preparation. During this step, the analysts identify what data they need to achieve the succesful result they identified in the previous step.
1. **Process**: In this step, the data analyst make sure how data would be collected, stored, managed, and protected.
1. **Analyse**: This is the moment where the data analyst dive into the data, combine data from multiple sources, do the calculations and data validations.
1. **Share**: Share the results with stakeholders involved in the project.
1. **Act**: The last stage of the process where the team of analysts work with stakeholders within their company and decide how best to implement sugegstions and actions based on the fidings. 

## Tasks in this project
1. Understand the problem statement
1. Import libraries and dataset
1. Perform exploratory data analysis
1. Perform k-means clustering
1. Fitting a MLR Model

## Data Source
For this project we will be using the [Data source](https://www.kaggle.com/datasets/leonczarlinski/iowa-liquor-sales) available at kaggle.

## Code Source
To develop the analysis, I used the Kaggle notebook available on **GitHub**. [Click here](https://www.kaggle.com/code/amoschew95/unlocking-the-spirits-of-iowa/notebook) to access the file and see the results. 

## Conclusions about the EDA
The exploratory data analysis (EDA) phase of our project provided profound insights into the distribution of liquor sales across Iowa. By mapping sales data by latitude and longitude, we were able to visualize a comprehensive map of Iowa, which illuminated the geographic trends in liquor consumption. This spatial analysis was not only insightful but also visually striking, revealing patterns that might have been overlooked in a traditional data table. The map's clear depiction of sales intensity across different regions was instrumental in understanding regional preferences and market dynamics.

In our K-means clustering approach, the critical step of removing outliers proved essential in achieving an optimal clustering solution. Initially, the data included several stores with extremely high sales, which distorted our analysis. By identifying and excluding these outliers, we were able to refine our model significantly. This led to the identification of 2 distinct and meaningful clusters of stores, offering a clearer understanding of the sales patterns and aiding in strategic decision-making for targeted marketing and distribution efforts.

The success of our Multiple Linear Regression Model relied on the careful selection of features and the implementation of 10-fold cross-validation. The chosen features, including number of bottles sold, volume sold, and the number of stores by zip code, proved to be highly predictive of sales, demonstrating their relevance in forecasting. The use of 10-fold cross-validation enhanced the accuracy and generalizability of our model, ensuring that our predictions were not only accurate within our sample but also robust across different subsets of data. The high level of accuracy (99%) underscores the effectiveness of our feature selection and the reliability of our predictive model in real-world applications.

**Enjoy the content!**
