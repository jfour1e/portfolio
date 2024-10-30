# Aspiring Quantitative Analyst 

### Technical Skills: Python (Pandas, Tensorflow, numpy), Rust, Natural Language Processing, Flask, AWS EC2, Git and Github, Excel

## Education 
- B.A in Applied Mathematics | Boston University (2023- ) 
- B.S in Data Sciences | Boston University (2023-  ) 

### Projects 

**Dual Horizon Regime Detection in Commodity Futures: A Hybrid GMM-HMM Framework** 
- Using Volatility and event-driven data, built a trading strategy using a hybrid framework that combines Gaussian Mixture Models (GMMs) for long-term trend detection with Hidden Markov Models (HMMs) for identifying short-term regime shifts
- The strategy dynamically adjusts positions based on identified market regimes, optimizing asset allocation to capture favorable trends while minimizing exposure during high-risk periods.
- Over the past year, it has backtested returns exceeding the market by roughly 25% demonstrating its effectiveness in adapting to varying market conditions.
- Implemented a flask app to handle broker RestAPI requests for continuously automated trading. Currently live trading. 


**Natural Language Processing Trading Bot** 
- Built and trained a Bidirectional Encoder Representations from Transformers (BERT) language model to web scrape news from CapitalIQ to aid in short term sentiment analysis and earnings trading.
- Resulting trained model has 92.3% accuracy on validation data set. 
● Built a separate Deep Neural Network to identify sentiment change patterns for companies to identify favorable buy / sell opportunities. 
● Beta feature (currently implementing): Consistently updated the portfolio based on
adapting market conditions and any reversing sentiment in stocks or the overall market.


**Analysis of Car Crashes in the United States**
(DS110 Final project on Github)
- Cleaned, normalized, and analyzed correlations of over 7 million car crashes using seaborn heatmaps and pandas
- Utilized a neural network built using tensorflow to predict the likelihood of a car crash based on several conditions (i.e. existence of an intersection, weather condition, ect.)
- Created an interactive application using the plotly dash python library to view the density of car crashes per county and state in the United States. 


**California road graph analysis using Rust**
(On github as DS210 final project) 
- Implemented graph algorithms such as Dijkstra's algorithm and Breadth-First Search (BFS) to find shortest paths and compute graph metrics using real-world data from the California road network.
- Analyzed graph properties, calculating graph density and clustering coefficients to understand connectivity and local structure.
- Conducted subgraph analysis, creating subsets of the graph to manage computational complexity and derive additional insights, including average distance calculations.
- Utilized Rust programming language to compile and execute the code, ensuring error handling and user input validation for accurate graph analysis.


**Stock Analysis using Macroeconomic indicators**
- Used historical Inflation data, bond prices, S&P500 returns, housing price index (HPI), the Volatility index, to analyze overall investing environment. 
- Return a bullish/bearish signal (from scale of 1-10) to aid in long term investing strategies. 
