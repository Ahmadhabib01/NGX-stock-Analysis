NGX Stock Risk \& Performance Analysis Dashboard



An end-to-end financial data analytics project that analyzes the historical performance and risk characteristics of 10 Nigerian Exchange (NGX) listed companies using Python, Pandas ,and Tableau Public .



This project demonstrates the complete data analytics workflow—from data collection and cleaning to financial risk analysis and interactive dashboard development.



**Project Overview**



Investors often need to balance  return  and  risk  when selecting stocks. This project evaluates the historical performance of selected NGX-listed companies by calculating key financial metrics and visualizing them through an interactive Tableau dashboard.



The analysis covers the period  June 2022 – June 2026  and compares companies across multiple sectors, including Banking, Agriculture, Consumer Goods, Industrial, Oil \& Gas, and Telecommunications.



&#x20;Objectives



The project aims to:



\- Analyze historical stock performance of selected NGX companies.

\- Calculate daily stock returns.

\- Measure investment risk using financial risk metrics.

\- Compare stocks across different sectors.

\- Build an interactive dashboard for financial analysis.



&#x20;



&#x20;🏢 Companies Included



&#x20;Company  Sector 

&#x20;    --

&#x20;ACCESSCORP-  Banking 

&#x20;GTCO-  Banking 

&#x20;UBA- Banking 

&#x20;ZENITH - Banking 

&#x20;DANGCEM - Industrial 

&#x20;DANGSUGAR - Consumer Goods 

&#x20;NESTLE - Consumer Goods 

&#x20;MTNN - Telecommunications 

&#x20;SEPLAT - Oil \& Gas 

&#x20;PRESCO - Agriculture 



&#x20;



&#x20;📂 Data Source



Historical stock price data were collected manually from publicly available Nigerian Exchange (NGX) market data.



Each dataset contains:



\- Date

\- Closing Price

\- Opening Price

\- High

\- Low

\- Trading Volume

\- Daily Percentage Change



&#x20;



&#x20;⚙️ **Methodology**



The project followed the workflow below:



&#x20;1. Data Collection



\- Downloaded historical stock price data.

\- Imported CSV files into Python.

\- Standardized date formats.

\- Converted price columns into numeric values.



&#x20;2. Data Cleaning



\- Removed missing values.

\- Converted percentage values to decimal format.

\- Calculated daily percentage returns.

\- Aligned all stocks to a common analysis period (June 2022–June 2026).



&#x20;3. **Financial Metrics**



The following metrics were calculated for each stock:



\- Daily Return

\- Annual Return

\- Annual Volatility

\- Sharpe Ratio

\- Historical Value at Risk (95%)

\- Maximum Drawdown

\- Sector Beta



&#x20;4. **Data Visualization**



An interactive Tableau dashboard was created to visualize:



\- Risk vs Return

\- Annual Return Ranking

\- Sharpe Ratio Ranking

\- Maximum Drawdown

\- Sector Performance



&#x20;



&#x20;📊 Dashboard Preview





!\[Dashboard Preview]-(dashboard/dashboard.png)



&#x20;



&#x20;🌐 Interactive Dashboard



&#x20;Tableau Public 



>  https://public.tableau.com/views/NGXStockRiskAnalysis/RiskandPerformanceAnalysisofNigerianExchangeStocks?:language=en-US\&publish=yes\&:sid=\&:redirect=auth\&:display\_count=n\&:origin=viz\_share\_link

&#x20;



&#x20;📈 Key Findings



\-  PRESCO  recorded the highest annual return and the strongest risk-adjusted performance based on the Sharpe Ratio.

\-  SEPLAT  combined relatively high returns with lower volatility, making it one of the strongest performers.

\-  DANGSUGAR  experienced the largest maximum drawdown, indicating higher downside risk.

\- Banking stocks (GTCO, UBA, ZENITH, and ACCESSCORP) showed similar return and risk characteristics.

\- The Risk vs Return chart illustrates the expected trade-off between higher returns and increased volatility.



&#x20;



&#x20;🛠 **Tools \& Technologies**



\- Python

\- Pandas

\- NumPy

\- Jupyter Notebook

\- Tableau Public

\- Git

\- GitHub



&#x20;



&#x20;📁 Repository Structure



```

NGX-Stock-Risk-Analysis/

│

├── data/

│   ├── ACCESSCORP.csv

│   ├── DANGCEM.csv

│   ├── ...

│

├── notebooks/

│   └── NGX\_Stock\_Analysis.ipynb

│

├── output/

│   ├── final\_stock\_metrics.csv

│   ├── daily\_returns.csv

│   └── correlation\_matrix.csv

│

├── dashboard/

│   ├── dashboard.png

│   │

├── README.md

├── requirements.txt

└── LICENSE

```



&#x20;





&#x20;



&#x20;⚠️ **Limitations**



\- Historical data for ACCESSCORP before June 2022 was unavailable in the selected data source.

\- Some stocks contained numerous zero-return trading days due to limited trading activity, which influenced historical VaR estimates.

\- Sector Beta was calculated using the average return of stocks within each sector because a sector index was not available.

\- This project is intended for educational and analytical purposes and should not be considered investment advice.



&#x20;



&#x20;🔮 Future Improvements



\- Incorporate the NGX All-Share Index to calculate market beta.

\- Include portfolio optimization using Modern Portfolio Theory.

\- Add Monte Carlo simulations for future return scenarios.

\- Connect to live financial APIs for real-time market analysis.

\- Expand the analysis to additional NGX-listed companies.



&#x20;



&#x20;👤 Author



**Ahmad Habib**



Statistics Graduate |Quantitative Researcher  |Data Analyst



\- LinkedIn:www.linkedin.com/in/ahmad-habib-119bb3335

\- X (Twitter): https://x.com/habibrise





Acknowledgements



This project was completed as part of a personal data analytics portfolio to strengthen practical skills in financial data analysis, Python programming, and Tableau dashboard development.



Thanks.

