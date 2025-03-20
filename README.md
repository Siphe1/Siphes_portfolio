# Siphe Mbonambi - Data Analysis Portfolio
## About
Hi, I am Siphe. I am currently on my second and final year of my Master's degree in Applied Data Science from the University of Johannesburg. I am an experienced analytics consultant in the financial services industry where I leverage data-driven insight to solve business challenges. I also hold an honours degree in Marketing from the University of Witwaterstrand which has helped me create a strong foundation in understanding customer behaviour, market trends and business strategy. I have strong domain knowledge in the financial services industry and a Postgraduate Diploma in Financial Services from the University of Kwazulu-Natal. During my Masters I have been able to develop skills in SQL, Python, Machine Learning, Power BI and Advanced Data Analysis techniques to deliver impactful solutions. I am passionate about combining my technical expertise and business knowlowledge to solve business problems and provide actionable insight.

## Portfolio Projects
In the below section I will list some of my data analytics projects a give a brief discription of the technology used in order to analyse the data.

### Analysing the toys dataset in order to gain any useful insight that could help grow the industry

**Code**: [`Analysis on the toys dataset`](https://github.com/Siphe1/Siphes_portfolio/blob/main/Toys_Sales_Project_.ipynb)

**Goal**: To analyse the data to find any patterns and possible opportunities that can be used to boost sales.

**Description**: The project is focused on analysing the toys sales dataset from January 2022 to July 2023. Though the time period is short we want to see if there is any insight that can be discovered from it. We will merge together the sales dataset, the products dataset and the store dataset. We will then perform some data cleaning, feature engineering, exploratory data analysis and lastly ask some business questions that will help us get insight from the data.

**Skills**: Data Cleaning, Exploratory Data Analysis, Data Visualisations.

**Technology**: Python, Pandas, Seaborn, Matplotlib

**Results**: Some of the things we learned from our analysis is that December is the month with the highest profits which adds up as it is christmas and a lot of toys are bought in that season. We could boast new toy ranges that are only avaiable in this season in order to further boast profits with limited edition products.
We noticed that Downtown stores are the most profitable locations by a huge margin with airport being the lowest. We could try boast the airport sales as they have a lot of foot traffic and when people travel love to buy souvenirs so we could try implement those type of products to the stores. We were also able to identify that the Dino Egg has the lowest profit margin and we could look into the impact of increasing it's price in order to gain a higher profit margin without impacting how many are sold. Lastly we noticed that Colorbuds was the most sold products with peak sales being in summer of 01-2022. There has been a steady drop though of the total unit sales of the product and a solution needs to be found to why the highest sold products is dropping unit sales consistently through the months.





### Using the service sales dataset in order to predict if people will subsribe to the offered digital services 

**Code**: [Predicting subsriptions of digital service](https://github.com/Siphe1/Siphes_portfolio/blob/main/Subscription%20Prediction%20Project.ipynb)

**Goal**: To create a machine learning model that can predict if a client will subsribe to offered services based on their demographic, economic and behavioural data.

**Description**: The project is focused on buidling a predictive model that can determine potential clients who are most likely to subsribe to the offered digital service. We will choose three classification models and pick the best performing one. The models purpose is to optermise the marketing efforts by targeting clients which have a higher conversion probability.  

**Skills**: Data cleaning, Exploratory Data Analysis, Machine Learning.

**Technology**: Python, Pandas, Seaborn, Matplotlib, scikit-learn.

**Results**: Based on the models that were used we noticed that the gradient boosting model performs the best overall, especially in terms of accuracy and the F1 score.
The model has the highest accuracy with 91.4%. For class 0 precision it had 0.94 and class 0 recall was 0.97% showing that the model is highly accurate at preicting non-subscribers.
For class 1 the precision was 0.68 and the recall was 0.51. While these are low compared to class 0 they do perform better than the other models.
To improve the performance of class 1 we can look into using other techniques that deal with class imbalance, like oversmaple by using SMOTE or undersample by reducing the number of class 0. We could also tune our model more by changing the parameters and possibly doing some feature engineering. Lastly trying different models could also assist.
