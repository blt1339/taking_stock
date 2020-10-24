# taking_stock
 
Project 1 Proposal

### Members: Beverly Thompson, Clark Pfifer

- Topic: Dividend-Oriented Stocks
- Databases used: Kaggle, Yahoo Finance API

### Questions to answer:
- What are the top 5 highest-returning dividend stocks in the given dataset (monthly)?.
    - no hypothesis here... just exploratory

- What are the quantifiable impacts on stocks between March 2020 to the present?
    - what does "falls" mean below?
    - alt hypothesis doesn't match structure of null hypothesis
        - try using this format:
            - Null:
                If [factor 1 is related to factor 2], then [a measurable amount of factor 1 will NOT cause more or less of factor 2]
            - Alt:
                If [factor 1 is related to factor 2], then [a measurable amount of factor 1 will cause more or less of factor 2]


        Null: If a stock falls between March 2020-present, then there will be no significant impact from COVID.
    
        Alternative: If a stock falls between March 2020-present, then that will indicate the onset of COVID created a drop in [set percent amount in stock price]. 

- What are the top stocks in terms of overall price growth? 
    - sentence structures should mirror each other like:
        - alternative: If a stock is not a dividend stock, there will be no significant correlation to overall price growth.
        - null: If a stock is a dividend stock, there will be significant correlation to overall price growth.

        Null: If a stock is a dividend stock, there will be no significant correlation to overall price growth.
    
        Alternative: If a stock is a dividend stock, there will be a [defined amount of percent growth] to overall price growth. 

### Hypotheses:


Title: Taking Stock- Dividends v Growth

Outline: Our presentation will be focused on the performance statistics of dividend stocks and overall stock growth metrics in a 2-year timespan.

Definitions:
- Dividend-Stock: stock prices only matter during initial buy and liquidation
- Liquidation: trying to convert stock to actual currency.
- Variation: In dividend stocks, a consistent stock is, for practical purposes, one that isn't losing money over the course of its existence.

### Scope/Limits:
- Where: U.S.(NASDAQ, NYSE)
- When: 11/1/2018-Present (which we assume will be around the end of 10/2020)
### Task Breakdowns:
- Access Kaggle: [https://www.kaggle.com/tsaustin/us-historical-stock-prices-with-earnings-data?select=dataset\_summary.csv](https://www.kaggle.com/tsaustin/us-historical-stock-prices-with-earnings-data?select=dataset_summary.csv) and pull Yahoo Finance API data together for up-to-date financial findings.
- Limit data findings to 11/1/2018 to present and only NASDAQ and NYSE
- Identify top performing dividend stocks:
    - Overall
    - Pre-March 2020
    - March 2020-Present
- Identify top stocks in terms of price growth:
    - Overall
    - Pre-March 2020
    - March 2020-Present
- Find the overlap between top dividend stocks and top growth stocks

### Roles:
- Clark: Strengths are more on the side of what I describe as "What humans will read". So, while I will do my best to help in coding through our datasets, my input will be best focused in the written analysis and how visualizations will appear for presentation.
- Beverly: Beverly will be more focused on the actual data analysis of the links provided. 
