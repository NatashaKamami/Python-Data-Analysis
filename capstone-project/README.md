# SPENDING TRENDS IN INDIA: INSIGHTS FROM CREDIT CARD DATA

## Business Problem 
This analysis seeks to understand the spending patterns across India, with a special focus on Kolkata City. The goal is to uncover why Kolkata's spending behavior deviates from the general trend observed in other high-spending cities and identify the underlying factors that might be driving these unique patterns.

## Data
Data Source: https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india
It contains data in the following columns:

- **City** - The city in which the transaction took place.
- **Date** - The date of the transaction.
- **Card Type** - The type of credit card used for the transaction. 
- **Exp Type** - The type of expense associated with the transaction. 
- **Gender** - The gender of the cardholder. 
- **Amount** - The amount of the transaction. 

## Visualizations
**1. What is the most preferred card type associated with spending in India?**
![image](https://github.com/user-attachments/assets/1fbcc170-f7b8-41e9-9c68-0c0972966703)

The pie chart shows that the Silver card type is the most popular and widely preferred for transactions, while the Gold card type is the least preferred. However, since the segments in the pie chart are relatively similar in size, it suggests that card type preferences are evenly distributed in India. The popularity of Silver cards in India can be attributed to their affordability, with lower fees and fewer eligibility requirements in comparison to Gold cards, making them accessible in a price-sensitive market like India therefore catering to a significant portion of India's population. Additionally, Indian consumers' preference for cost-effective and straightforward financial products aligns with the features of Silver cards, while the stricter requirements and higher costs of Gold cards limit their appeal.

**2. Gender spending patterns and their card type preference**
![image](https://github.com/user-attachments/assets/13a4727c-0658-42e6-ae7c-e4088db166c6)

For each card type, Females tend to exhibit higher spending levels in comparison to Males. Notably, the Silver card type has a significantly higher number of Female users, which aligns with evidence that the Silver card is the most preferred card type in India. Women in India tend to spend more than men due to a combination of social roles, economic independence, and cultural factors. As primary household purchasers, women manage family budgets and purchase essentials like groceries and household goods. Their growing economic independence and participation in the workforce also provides them with greater disposable income. Additionally, cultural factors also play a role in spending patterns since women are often responsible for planning and spending on festivals, weddings, and other significant events.

**3. Gender spending patterns and their card type preference in the Top 10 Cities**
![image](https://github.com/user-attachments/assets/ee6032fd-74d0-4231-b333-454fc05c7fa0)

Total spending is seen to be concentrated in Delhi, Bengaluru, Greater Mumbai, and Ahmedabad. These cities are economic and financial hubs with high populations, greater disposable incomes, and better access to digital payment infrastructure and technologies, which contribute to higher spending levels. Affluent residents, more businesses, and increased credit access also drive spending in these areas. In terms of card usage, Greater Mumbai leads in usage of Gold cards for transactions (due to its wealthy population), Bengaluru leads in the usage of Silver and Signature cards, while Ahmedabad shows a preference for Platinum cards. Overall gender-based spending patterns show that women are the dominant spenders in most cities, except Kolkata, where men lead. This anomaly in Kolkata warrants further exploration to understand the factors driving this divergence.

**4. Total spending by expense type in the top 10 cities**
![image](https://github.com/user-attachments/assets/3ce92d6d-d1f8-4705-b019-918e7e6c117c)

In most of the top 10 cities, Bills dominate as the primary expense type, followed closely by Grocery, which is also a leading category in several cities. This indicates that these two expense types are both popular and essential. However, Kolkata stands out with Entertainment as its most dominant expense type, deviating from the broader trend. This suggests location-specific spending habits that differ significantly from the other cities. The larger rectangles for essential categories, such as Bills and Grocery, highlight a focus on necessities, while larger areas for discretionary categories, such as Entertainment, could reflect higher disposable income or distinct lifestyle trends in those cities. Given Kolkata's divergence both in gender spending patterns and its preference for Entertainment as the leading expense type, further investigation into spending habits in this city could provide valuable insights into its unique behavioral trends.

**5. Expense-Specific Spending by Card Type In The Top 10 cities**
![image](https://github.com/user-attachments/assets/82b86891-ec85-4ade-8da6-1cfabb2e0f68)

Silver cards tend to dominate every expense type except Travel where the Gold card dominates. Silver Cards' dominance in most expense types is because they tend to cater to a broader audience and are more commonly used for routine expenses like groceries, food and bills. Gold Cards on the other hand are dominant in Travel spending due to the fact that they often come with perks tailored to travelers, such as airline miles, lounge access, travel insurance and higher reward points for travel-related purchases like flights, hotels, likely making them the preferred choice for travel expenses. 

**6. Why does Kolkata follow a contrary trend when it comes to total spending on expense types and gender spending patterns?**
  
  **a) Total Spending by expense type**
![image](https://github.com/user-attachments/assets/842eb69d-3d7c-4471-a241-c3635b6d5550)

Kolkata is known for its rich cultural heritage, and entertainment plays a huge role in this. Major festivals like Durga Puja and Bengali New Year often involve significant cultural activities, which could drive up spending in the entertainment category. The city also hosts numerous art and film festivals as well as musical and theatrical performances, drawing large audiences hence fostering spending on these experiences. The rise of digital platforms such as Netflix and Amazon Prime, along with online gaming and subscriptions further boosts entertainment spending. Kolkata also has a thriving cinema culture and is home to renowned movie theaters like the Bengali cinema which further drives entertainment-related expenses. Lastly, Kolkata is a popular destination for tourism, with attractions such as Victoria Memorial, Indian Museum, Howrah Bridge which also contribute to entertainment spending through visits.

  **b) Total spending by expense type grouped by Gender**
![image](https://github.com/user-attachments/assets/56a5a55c-7a3d-4d5f-90ad-7375ac5b7875)

The bar chart highlights distinct gender-based spending patterns across different expense types in Kolkata. Men outspend women in nearly all categories, particularly in utility-related expenses like Fuel and Bills. This suggests that men in Kolkata may have greater expenditures related to transportation, home maintenance, or other essential services. On the other hand, women in Kolkata dominate the Travel category, indicating a higher expenditure on travel-related activities. This could reflect women's inclination toward leisure travel or vacations, often considered lifestyle-oriented expenses. This divergence in spending behavior offers valuable insights into gender-specific preferences.

  **c) Monthly spending trend in Kolkata**
![image](https://github.com/user-attachments/assets/53680540-1b5f-4944-bbfd-f2a5b5751cb3)

The line graph of shows peaks in January, April, August, and October. January marks New Year celebrations and cultural events like Makar Sankranti, driving spending on food, clothing, gifts and travel. April aligns with the Bengali New Year (Poila Boishakh), leading to high spending on traditional attire and gifts. August is marked by Durga Puja preparations and October is marked by Durga Puja celebrations- the city's biggest and most anticipated festival, as well as Diwali celebrations, driving significant expenditures on shopping, decorations, and travel. Low spending months such as February, March, May, September, and November reflect quieter periods after major celebrations. Overall, spending peaks are linked to key cultural festivals explaining why Entertainment is the highest spending expense type, while troughs occur during transition periods before the onsets of major festivals or during recovery periods after the festivities, highlighting the influence of Kolkata’s cultural calendar on consumer behavior.

  **d) Comparing monthly spending trends in the highest spending city in India (Greater Mumbai) and Kolkata**
![image](https://github.com/user-attachments/assets/9930cb34-76c4-48f5-9328-d4bc9dfeaa48)

The monthly spending trends in Mumbai show peaks in February, March, August, October, and December (with December 2014 being the highest). Peaks align with major events like the wedding season (February), fiscal year-end (March), and cultural festivities such as Ganesh Chaturthi (August), Diwali (October), and holiday shopping (December). Spending dips in January, April, July, and November reflect post-celebration recovery and fiscal year beginnings. Mumbai and Kolkata exhibit similar spending patterns, with peaks tied to festivals and troughs tied to recovery periods, despite differing total spending levels. This highlights the cultural calendar's significant influence on consumer behavior in both cities.

## Conclusion
The analysis of credit card spending in India reveals trends shaped by cultural, seasonal, and economic factors. Silver cards dominate routine expenses, while Gold cards are least preferred. Spending peaks align with festivals reflecting the influence of India's cultural calendar on spending. These insights can help tailor credit card rewards to align with specific spending behaviors. Adding demographic data on age groups related to the spending would help understand spending habits better.


