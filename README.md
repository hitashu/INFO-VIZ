# INFO-VIZ Capstone Project 
# Walmart Sales Forecasting
## Team Members - Gourang Patel, Sanjan Vijayakumar, Hitashu Kanjani, Sagar Singh


# Context

Ecommerce has been an ever-growing industry with retail revenues projected to grow to 4.9 trillion US dollars in 2021. With  this  tremendous  growth,  sales  forecasts  will  help  every  business understand  changing  customer demands, manage inventories as per the demands thus reducing the financial risks, and create a pricing strategy that reflects demand. Companies will be able to take strategic steps on their short - term and long - term performances and can decide  their decision  metrics. 
This project will present the right methodologies to analyze time-series sales data and predict 28 days ahead point forecasts for the company to take strategic decisions based on the predictions. Additionally, the project’s goal includes making recommendations on inventory  management based  on  the  28  days  forecast. Sales  forecasting is  a very crucial  research  area with companies heavily investing and proposing advanced Methods like FaceBook’s Neural Prophet, Amazon’s DeepAR Model, Dilated convolutional neural networks. We plan to leverage the traditional time series forecasting methods as well as the modern forecasting methods and analyze the time-series sales data for Walmart.

# Proposed Plan
Making predictions about the future is called extrapolation in the classical statistical handling of time series data. We plan to address this problem statement by using M5 forecasting competition 2020. This is Walmart’s dataset with information about various products sold in the US into 3 different states California, Texas, and Wisconsin. The dataset involves the unit sales of 3049 products classified in 3 product categories(Food, Household, Hobbies) and 7 product departments across a timespan of 5 years starting from 2011 to 2016. The Data  also includes  explanatory  variables  such  as  sell  prices,  promotions,  days  of  the  week,  and special events that typically affect unit sales and could improve forecasting accuracy. 
For the forecasting and predictions on sales data, we are planning to use 3 fundamental approaches to attain best possible results:

# Risks and Mitigation Strategies
When it comes to Sales Forecasting, accuracy plays an important role to inform decision making. If a prediction is too optimistic, businesses may overinvest in products and personnel, resulting in squandered funds. Companies may underinvest if the prediction is too low, resulting in a shortage of goods and a poor customer experience. However, high accuracy remains challenging for two reasons:
Traditional forecasts struggle to incorporate large amounts of previous data, resulting in the omission of significant past signals that get lost in the noise.


Traditional forecasts rarely include related but independent data (Exogenous Variables) that can provide important context (for example, price, holidays/events, stock-outs, marketing promotions, and so on). As a result of this, most forecasts fail to accurately predict the future without the full history and context.
To mitigate the above risks, we will be leveraging models like SARIMA, and various Deep Learning and Ensemble based models that can account for exogenous variables and handle both large data and multi step forecasting. For implementation, the potential risks would be:
