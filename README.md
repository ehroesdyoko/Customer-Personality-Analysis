# Customer-Personality-Analysis
Purwadhika JCDSOL08 - Module 2: Data Analysis


# Background
An e-commerce company wants to analyse its Customer by using their internal customer data that was gathered during 2012-2014. Those data consist of 4 major categories which follows the Marketing 4Ps, they are People, Product, Promotion and Place.

This Analysis consist of these sections, which will be presented by given order: Data Understanding and Cleaning, Data Analysis - Customer Background Overview, Data Analysis - Marketing Campaign and Key Takeaways.

The goal of this analysis is to improve the current marketing campaign effectiveness and efficiency through suggestion based on the findings of their customer's background.

# Problem Statement
The company wants to see the results of their marketing campaign during 2012-2014, through this infromation and historical data they want to improve their marketing campaign to be more efficient and effective.

As a Data Analyst, we would like to answer this following question:

How is the performance of the existing marketing campaign? and How to improve the effectiveness and efficiency of the marketing campaign?

# Key Takeaways
The accepted campaign rate is ~6% on average (6%, 1%, 7%, 7%, 7%). Based on the average conversion rate for marketing campaign in e-commerce industry which is 3.71%. So the campaigns can be considered as succesful. [Source](https://popupsmart.com/blog/what-is-a-good-conversion-rate).

Even though the campaign can be considered successful there are some improvements that can be implemented to enhance the effectivity of the marketing campaign. Beforehand, we will elaborate the condition of the existing marketing campaign data (`AcceptedCmp1-5`). Here are few conditions:
* There is no explanation what is the `AcceptedCmp1-5` about and the differences between them
* Since there is no explanation about each marketing campaign, the goal of the campaign is remain unknown
* The current marketing campaign does not time-bound, meaning that there is no information about what the campaign starts and ends
However, these conditions can be intenioally implemented to follow company's regulation and/or country's regulation.


These are few suggestions to improve the marketing campaign:
1. For customer's retention campaign, the company's can focus on customers that have high Income, big spending amount on Wine and Meat (based on historical Data) and using catalog as the channel of purchase. (Reference: Correlation Matrix)
2. The trend of Customer Enrollment by Month, The Distribution of Deals Purchase by Customer's Enrollment Date and The Sum of Total Purchase by Customer's Enrollment date showing the similar trend, meaning that these customers are the most active and also well the most well-informed customer in terms of promotion. In Addition, this customer group is also the majority of customer who accepted the marketing campaign (Reference: Accepted Campaign 1-5 based on Customer's Enrollment Date graph)
3. **If possible** create an marketing campaign for acquiring new customers, the backgrounds for this potential customer are:
    * Married
    * Education background: Graduation, Master, and PhD
    Reference: Pair Plot Graph and Customer's Background Overview
4. The marketing campaign for customer's retention and acquiring new customer should not only provide discount to trigger the purchase and also customer's enrollment (for the latter) but also it should have a time span for the marketing campaign. For example Year End Sale (29 Dec - 2 Jan) or a more thematic campaign such as 11.11 or CNY (22 Jan). By adding time-bound characteristics, it is easier to use for further analysis.
