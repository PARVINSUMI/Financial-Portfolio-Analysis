
# 📊 Portfolio Analysis Project  

This project demonstrates portfolio analysis using Python with a focus on asset allocation, returns, and risk metrics. The analysis leverages asset price data, portfolio weights, and asset family classifications to evaluate portfolio performance.  

---

## 📂 Data Files  

- **`asset_price_data.csv`** – Historical daily prices of financial assets.  
- **`portfolio_weights.csv`** – Portfolio weights for each asset over time.  
- **`asset_information_data.csv`** – Metadata mapping each asset to an asset family (e.g., equities, bonds, commodities).  

---

## 🧮 Analysis Steps  

### 1. Data Loading & Price Normalization  
- Loaded historical asset price data.  
- Normalized each asset’s price series to start at 100.  
- 📈 **Output:** Line chart of normalized asset prices.  

### 2. Daily Returns & Risk Metrics  
- Calculated **daily percentage returns** for each asset.  
- Computed:  
  - **Correlation matrix** between assets.  
  - **Annualized volatility** of each asset.  
  - **Scatter plot** of two asset return series.  
- 📊 **Outputs:**  
  - Correlation matrix table (and optional heatmap).  
  - Scatter plot of asset returns.  

### 3. Portfolio Returns  
- Computed portfolio daily returns as weighted sum of asset returns.  
- Calculated **annualized return** of portfolio and individual assets:  

  \[
  Annualized\ Return = (1 + \bar{r}_{daily})^{252} - 1
  \]  

- Constructed **cumulative portfolio return** over time.  
- 📈 **Output:** Line chart of portfolio cumulative returns.  

### 4. Portfolio Weights & Asset Families  
- Aggregated asset weights by **family** using `asset_information_data.csv`.  
- Plotted an **area chart** of family-level allocations over time.  
- 📊 **Output:** Stacked area chart of portfolio asset allocation by family (soft pastel colors for readability).  

### 5. Percentile Analysis of Portfolio Returns  
- Converted daily portfolio returns into **percentiles** (relative ranking of each day).  
- 📈 **Outputs:**  
  - Time series plot of return percentiles.  
  - Histogram of percentile distribution.  

---

## 📌 Visualizations  

- **Normalized Asset Prices**  
- **Daily Returns Scatter Plot**  
- **Correlation Matrix**  
- **Annualized Volatility Table**  
- **Portfolio Cumulative Returns**  
- **Asset Allocation by Family (Area Chart)**  
- **Portfolio Return Percentiles (Line + Histogram)**  

---

## ⚙️ Technologies Used  

- **Python**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib** – Visualizations  

---


## 📖 Key Insights  

- Volatility and correlation structure highlight diversification potential.  
- Asset family allocation trends help visualize portfolio strategy.  
- Percentile analysis contextualizes daily returns vs. history.  


## Link 

- Presentation: https://docs.google.com/presentation/d/1EMeA8mMzZF_CfJ6ShN-C5PYSFb3zGlKb/edit?slide=id.g3799df8de2d_1_0#slide=id.g3799df8de2d_1_0
 
