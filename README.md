This project involves analyzing data from Yulu, India's leading micro-mobility service provider, to understand factors affecting the demand for shared electric cycles. Using statistical analysis and visualization techniques in Python, we explore customer behavior patterns, demographic preferences, and usage trends across different products offered by Yulu. By uncovering insights such as peak usage times, customer demographics, and weather impact, this analysis aims to provide actionable recommendations for optimizing operations and enhancing customer satisfaction in the micro-mobility industry.

## Business Problem
The company wants to know:
* Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
* How well those variables describe the electric cycle demands

## Insights & Recommendation

1. Based on the hypothesis testing following features have been identified as significant for predicting bike rental demand: 
    1. datetime
    2. season
    3. workingday
    4. weather
    5. atemp
    **Recommendation:** Given the significance of these features, Yulu should focus its predictive models and marketing efforts around these factors. For example, the company can create targeted marketing campaigns that consider both weather conditions and seasonality, offer promotions on non-working days, and optimize bike availability during peak demand hours based on these features to maximize rental demand and customer satisfaction.


2. The data shows that most bike rentals occur during the morning, afternoon, and evening hours. However, there is a drop in rentals during the night.\
    **Recommendation:** Yulu should consider implementing a maintenance and recharging schedule during the night time hours when bike rentals are lower. This can help ensure that bikes are in good condition and fully charged during peak rental times, enhancing customer satisfaction and operational efficiency.


3. The Peak hour for bike rentals is at 8 am in the morning and again from 4 pm to 7 pm in the evening.\ 
    **Recommendation:** Yulu should implement a dynamic pricing strategy that reflects the demand during peak hours. During the morning and evening peak hours, when demand for bike rentals is high, the company can slightly increase rental rates. Conversely, during off-peak hours, offering discounted rates or promotions can encourage more usage. This flexible pricing approach can help balance demand throughout the day. Additionally, the company should ensure that there is a sufficient supply of bikes available during these peak periods to meet the high demand. 


4. The data indicates a strong positive correlation between the total number of bike uses and the frequency of bike usage by registered users. This suggests that registered users tend to use the bikes more often compared to casual users. On the other hand, the correlation between casual users and the total bike count is weakly positive, further supporting the notion that registered users are the primary drivers of frequent bike usage.\
    **Recommendation:** Given that registered users are more active in using the bikes, Yulu should focus on strategies to retain and engage this user segment. Offering exclusive benefits, discounts, or loyalty programs to registered users can encourage them to continue using the service regularly. At the same time, efforts should also be made to attract and convert more casual users into registered users to strengthen the user base.
  

5. On average, the Spring season had the lowest number of bike rentals, while the Fall season saw the highest number of bike rentals.\
    **Recommendation:** Yulu should take advantage of the higher demand during the Fall season, possibly by launching special promotions, events, or marketing campaigns to attract more users during this period. During the Spring season, when demand is lower, the company can focus on maintenance and preparation for the upcoming peak season to ensure bikes are in excellent condition for the Fall surge in rentals.


6. In clear weather conditions, there is a higher demand for bike rentals, while in rainy weather, the number of bike rentals decreases.\
    **Recommendation:** Yulu should take advantage of the increased demand during clear weather by promoting bike rentals and potentially offering weather-related discounts or incentives. During rainy weather, the company can consider strategies such as offering rain gear or special promotions to encourage rentals despite the less favorable conditions. Additionally, ensuring that bikes are well-maintained and safe for riding in rainy conditions can help retain customers.


7. The classification between working days and non-working days does play a significant role in predicting bike rental demand.\
    **Recommendation:** Yulu should adapt its operational and marketing strategies to align with the varying demand on working days and non-working days. On working days, the company can focus on promoting bike rentals for commuting purposes. On non-working days, it should emphasize leisure or recreational use of the bikes. Additionally, Yulu should explore partnerships with delivery service providers, such as food or grocery delivery, to maintain consistent demand throughout the week. 
    

8. The distinction between holidays and non-holidays does not significantly impact the prediction of bike rental demand.\
    **Recommendation:** Since holidays and non-holidays do not have a substantial impact on bike rental demand, Yulu may choose to allocate its resources and marketing efforts more evenly throughout the year. This means that the company doesn't need to create separate strategies for holidays and regular days but can maintain a consistent approach to serve its customers effectively.
 

9. More users choose Yulu bikes when the temperature is slightly higher and humidity levels are lower.\
    **Recommendation:** Yulu should consider adjusting its marketing strategies and promotions to target periods with these weather conditions, as they appear to attract more users. Additionally, the company might want to focus on maintaining and expanding its bike fleet during these weather conditions to meet the increased demand effectively.
    

10. Based on the number of bikes rented in each season under various weather conditions, it appears that there is a significant relationship or dependency between weather and season.


Thank You!
