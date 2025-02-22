# Aspring Finance Professional: Equity Research, Risk management, Quant Research, Data Analyst. 

### Technical Skills: Python, Tensorflow, Julia, Rust, SQL, Natural Language Processing, Flask, AWS EC2, Git and Github, Excel, Microsoft Office, CapitalIQ

## Education 
- B.A in Applied Mathematics | Boston University (2023- ) 
- B.S in Data Sciences | Boston University (2023-  ) 

### Projects 

**Regime Detection in Commodity Futures: An HMM Framework** 
- Using Volatility and event-driven data, built a regime switching trading strategy using Hidden Markov Models (HMMs) for identifying short-term regime shifts for commodity markets. 
- The strategy dynamically adjusts positions based on identified market regimes, optimizing asset allocation to capture favorable trends while minimizing exposure during high-risk periods.
- Over the past year, it has backtested returns exceeding the market by roughly 25% demonstrating its effectiveness in adapting to varying market conditions.
- Implemented configuration support with broker RestAPI requests for continuously automated trading. Currently live trading. 


**Natural Language Processing Trading Bot** 
- Built and trained a Bidirectional Encoder Representations from Transformers (BERT) language model to web scrape news from CapitalIQ to aid in short term sentiment analysis and earnings trading.
- Resulting trained model has 92.3% accuracy on validation data set. 
- Built a separate Recurrent Neural Network (LSTM) to identify sentiment change patterns for companies to identify favorable buy / sell opportunities.
- Bactested returns are approximately 6% over the last two months trading.
- Bata feature (currently implementing): Consistently updated the portfolio based on
adapting market conditions and any reversing sentiment in stocks or the overall market.


**Analysis of Car Crashes in the United States**
(DS110 Final project on Github)
- Cleaned, normalized, and analyzed correlations of over 7 million car crashes using seaborn heatmaps and pandas
- Utilized a neural network built using tensorflow to predict the likelihood of a car crash based on several conditions (i.e. existence of an intersection, weather condition, ect.)
- Resulting Neural Net had 87% validation accuracy in predicting instances of car crashes. 
- Created an interactive application using the plotly dash python library to view the density of car crashes per county and state in the United States. 

**Personal Portfolio Optimization using Markowitz's Efficient Frontier**
- Implemented a 3d correlation graph to analyze time series correlations using the spearman coefficient
- Identified favorable equity weightings in personal portfolio based on max returns, max sharpe ratio and minimum volatility. Resulting portfolio Outperformed the S&P500 by 3% in 2024. 

**California road graph analysis using Rust**
(On github as DS210 final project) 
- Implemented graph algorithms such as Dijkstra's algorithm and Breadth-First Search (BFS) to find shortest paths and compute graph metrics using real-world data from the California road network.
- Analyzed graph properties, calculating graph density and clustering coefficients to understand connectivity and local structure.
- Conducted subgraph analysis, creating subsets of the graph to manage computational complexity and derive additional insights, including average distance calculations.
- Utilized Rust programming language to compile and execute the code, ensuring error handling and user input validation for accurate graph analysis.


**Stock Analysis using Macroeconomic indicators**
- Used historical Inflation data, bond prices, S&P500 returns, housing price index (HPI), the Volatility index, to analyze overall investing environment. 
- Return a bullish/bearish signal (from scale of 1-10) to aid in long term investing strategies. 
