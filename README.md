
# Investolio

Investolio is a web app created with the intention of helping investors gauge different options while making long-term investments in the stock market. The purpose of this application is to guide investors when diversifying investment portfolios based on risk, dividends and estimated returns. It uses Python, its libraries, frameworks and a static database for development.


## Objective 

Stock market prices have always been uncertain and require an in-depth understanding to get good returns. Even seasoned investors can't always be sure due to the volatility of the market. Our goal with this application is to assist investors in making investment-related decisions based on the possible trends we provide.

With this web app, we also intend to help beginners learn what needs consideration before making such investments and eventually make them confident and independent.


## Methodology

1. Preprocess the data to make it easy to work with. This includes filtering outliers, duplicates, irrelevant values and unrealistic (most likely false) values.

2. Calculates minimum investment amount necessary to get returns.

3. The number of Minimum stocks required to get for each selected sector to show the selected number of recommendations.

4. Calculate investment per share and  add several columns: "Shares (Amount of Shares held for this stock), "Value of Shares (the value of the shares hold in this stock), "Total Dividends" (The number of Dividends in a month this stock makes with the 'amount of shares' it has), Contribution to Goal (% that this stocks dividends contributes towards the users' defined goal)

5. The dataset we've currenlty chosen to to use is static and focused more on building the model. In the future scope our goal is to integrate real-time dataset to make it actually usable.



## Result

Input given through filters

![filter1](./filter1.png)
![filter2](./filter2.png)

Output received

![numbers](./numbers.png)
![one year](./one%20year%20dividend.png)
![two year](./after%20two.png)
![five year](./after%20five.png)
![goal](./when%20goal%20reached.png)

(We also tried to include Google Cloud Platform and AMD instance by hosting it in the instance but even after numerous tries it didn't work. We understand that integrating these technologies was an important criteria for the hackathon but since we had built a project around one of the themes anyways we have made a submission. We hope you understand our situation.)
