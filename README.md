# James Fourie: Personal Portfolio 

### Technical Skills. Languages: Python, Julia, Rust, SQL. Natural Language Processing, Hierarchical Machine Learning models, State Space Models, Time Series modeling, AWS, Excel. 

## Education 
- B.A in Applied Mathematics | Boston University (2023- ) 
- B.S in Data Sciences | Boston University (2023-  ) 

### Projects 

**Regime Detection in Commodity Futures: An HMM Framework** 
- Using Volatility and event-driven data, built a regime switching trading strategy using Hidden Markov Models (HMMs) for identifying short-term regime shifts for commodity markets.
- Validated model using purged K-fold cross validation (1.5M+ rows of data). Live data scraping and cleaning functionality, and cached data for fast computation.
- Built robust time-series sampling pipeline from scratch; volatility bars, Directional-Change, time-based resampling. Handles 2M+ rows of data, developed multithreading functionality to reduce computation by 50%.
- Implemented full trading pipeline hosted on AWS EC2; Databento for market data, brokerage RestAPI requests.


**Natural Language Processing Trading Bot** 
- Obtained university funding for a sentiment analysis trading system, managing a team of four. Fine tuned
Bidirectional-Encoder-Transformer (BERT) neural net from Google Deepmind to 93% validation accuracy using 35,000 point self curated dataset.
- Constructed recurrent neural network (RNN) to uncover temporal relationship between news/sentiment and next day stock movements. 6% backtested returns over two months across portfolio of 20 large-cap equities. .



**Portfolio Optimization of BUFC's 1.2M Long Equity Fund**
- Implemented a 3d correlation graph to analyze time series correlations of the fund's holdings using the spearman coefficient.
- Designed position sizing algorithm for new positions that leverages a four factor model, idiosyncratic expected returns. 
- Proposed trading plan for favorable equity weightings based on industry exposure metrics and weighting scheme aligned to the Russell 2000 Index (Fund Benchmark).


**Analysis of Car Crashes in the United States**
(DS110 Final project on Github)
- Cleaned, normalized, and analyzed correlations of over 7 million car crashes using seaborn heatmaps and pandas
- Utilized a neural network built using tensorflow to predict the likelihood of a car crash based on several conditions (i.e. existence of an intersection, weather condition, ect.)
- Resulting Neural Net had 87% validation accuracy in predicting instances of car crashes. 
- Created an interactive application using the plotly dash python library to view the density of car crashes per county and state in the United States. 


**California road graph analysis using Rust**
(On github as DS210 final project) 
- Implemented graph algorithms such as Dijkstra's algorithm and Breadth-First Search (BFS) to find shortest paths and compute graph metrics using real-world data from the California road network.
- Analyzed graph properties, calculating graph density and clustering coefficients to understand connectivity and local structure.
- Conducted subgraph analysis, creating subsets of the graph to manage computational complexity and derive additional insights, including average distance calculations.
- Utilized Rust programming language to compile and execute the code, ensuring error handling and user input validation for accurate graph analysis.

