# James Fourie

Applied Mathematics & Data Science @ Boston University  
Probabilistic Modeling • Portfolio Optimization • Machine Learning in Finance 

📍 Boston, MA  
📧 [jfourie@bu.edu] | 🔗 [https://www.linkedin.com/in/jfourie1/] | 💻 [https://github.com/jfour1e]

---

## Education 
- B.A in Applied Mathematics | Boston University (2023-2027) 
- B.S in Data Sciences | Boston University (2023-2027)
GPA: 3.70 / 4.0   

## Selected Projects 

### 1. StateSpaceDynamics.jl — Probabilistic State-Space Modeling Framework (Research, Core Contribution)
**Open-Source Julia Library for State Space Modeling**

- Contributed core modeling and inference components to an open-source Julia package for probabilistic state-space models, including Hidden Markov Models (HMMs), Generalized Linear Model HMMs (GLM-HMMs), and Switching Linear Dynamical Systems (SLDS).
- Implemented and optimized likelihoods, transition learning, and Bayesian parameter updates (Dirichlet and inverse-Wishart priors), with a focus on numerical stability and memory-efficient execution for large-scale time-series.
- Built and benchmarked EM and variational inference pipelines for regime-switching models used in behavioral neuroscience and decision-making experiments.
- Co-authored a research poster, *StateSpaceDynamics.jl: A Julia Package for Probabilistic State Space Models* (Senne, Loschinskey, Loughridge, Fourie, DePasquale, 2024, in preparation), describing the software architecture and applications to cross-species cognitive modeling.

[GitHub Repository](https://github.com/depasquale-lab/StateSpaceDynamics.jl) | 
[JOSS Paper Submission)](https://joss.theoj.org/papers/10.21105/joss.08077)

---

### 2. Quantitative Portfolio Construction & Risk System for BU Finance and Investment Club 
**Benchmark-Aware Optimization, Alpha Modeling, and Rebalance Engine**
- Designed and implemented a full-stack quantitative portfolio management system for a Russell-2000-benchmarked long-only equity portfolio, integrating data ingestion, alpha modeling, risk estimation, convex optimization, attribution, and execution.
- Built a benchmark-relative alpha framework that decomposes stock returns against sector ETF proxies, enabling clean separation of true security-selection alpha from market and sector effects.
- Implemented a Ledoit–Wolf shrinkage covariance model and a tracking-error-constrained convex optimization problem solved with MOSEK, incorporating long-only constraints, position limits, sector penalties, and cash handling.
- Developed an automated rebalance and trade-generation layer that converts optimal weights into executable orders with lot-size rounding, cash buffers, and broker-ready outputs.
- Created a real-time Dash dashboard for monitoring active risk, sector exposures, attribution, and information ratios, mirroring institutional risk-system workflows (e.g., Barra / Axioma style analytics).

[GitHub Repository](https://github.com/jfour1e/BUFC-fund-dashboard)  

---

### 3. Simulation-Based Inference for Drift Diffusion Models (Research)
**Neural Likelihood Estimation for Stochastic Decision Models**

- Developed simulation-based inference pipelines for Drift Diffusion Models (DDMs) using masked neural likelihood estimation (MNLE), enabling Bayesian inference in settings where analytical likelihoods are intractable.
- Implemented a pulse-based DDM simulator using Euler–Maruyama discretization, supporting flexible stimulus schedules, boundary conditions, and non-decision time components.
- Trained neural density estimators on millions of simulated trials to learn amortized likelihoods and posteriors, and validated inference through full parameter-recovery studies and simulation-based calibration.
- Deployed large-scale training jobs on HPC clusters using `qsub`, gaining experience with distributed experimentation, GPU scheduling, and performance profiling for Bayesian neural networks.

[GitHub Repository](https://github.com/jfour1e/SBI-for-Diffusion-Models)  

-- 

### 4. Regime Detection in Commodity Futures with Hidden Markov Models 
**Gold & Silver, 15-Minute Data, 2010–2024**

- Built a regime-switching framework for precious-metal futures using Hidden Markov Models trained on alternative time-series representations, including volatility bars, time bars, and Directional-Change sampling.
- Designed a purged K-fold cross-validation scheme to avoid look-ahead bias and to properly evaluate regime stability and transition dynamics in high-frequency financial data.
- Compared sampling schemes through extensive bootstrapped backtests and found Directional-Change representations to yield more stable state inference and improved out-of-sample performance.
- Implemented an end-to-end live trading pipeline (Databento → AWS EC2 → brokerage REST API), achieving sub-second latency from data ingestion to signal generation and execution.

---

### 5. NLP-Driven Sentiment Trading System

- Fine-tuned a BERT-based transformer on a curated 35k-sample financial news dataset, achieving ~93% validation accuracy for sentiment classification.
- Trained a recurrent neural network to model the temporal relationship between news flow and next-day equity returns, producing statistically significant backtested performance over a large-cap universe.
- Built an automated daily pipeline for data collection, model inference, signal ranking, and email-based trade distribution.

---

### 6. US Car Crash Prediction and Geospatial Risk Analysis

- Processed and cleaned over 7 million traffic accident records and trained a neural network to predict crash likelihood from environmental and infrastructural features.
- Achieved ~86–87% out-of-sample accuracy and deployed an interactive Plotly Dash application for county- and state-level visualization of crash density and risk factors.

[GitHub Repository](https://github.com/jfour1e/Car-Crash-Data-Analysis-)  

---

### 7. Large-Scale Graph Algorithms in Rust

- Implemented core graph algorithms (Dijkstra’s shortest path, BFS, clustering coefficients) on the California road network using Rust for performance and memory safety.
- Analyzed connectivity, subgraph structure, and average path lengths, and developed tooling for scalable graph analytics on real-world transportation data.

[GitHub Repository](https://github.com/jfour1e/DS210_Final_Project)  

## Publications & Posters

- **StateSpaceDynamics.jl: A Julia Package for Probabilistic State Space Models**  
  Senne, R., Loschinskey, Z., Loughridge, C., Fourie, J., DePasquale, B. (2024, in preparation).  
  Poster describing the design and applications of a high-performance probabilistic state-space modeling library for behavioral and neural data.

