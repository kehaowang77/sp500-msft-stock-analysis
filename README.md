# sp500-msft-stock-analysis
## ACC102 Mini Assignment Track 2
### Microsoft Stock Return & Volume Analysis Based on WRDS CRSP Database

### Project Overview
This project completes the required empirical data analysis for ACC102 Track 2 Mini Assignment. It focuses on Microsoft Corporation’s long-term monthly stock performance, including database connection, SQL data extraction, data cleaning, statistical analysis, time-series visualization and core financial indicator calculation.

### Data Source
- Database Platform: WRDS (Wharton Research Data Services)
- Original Dataset: CRSP Monthly Stock File (`crsp.msf`)
- Target Firm: Microsoft Corporation (CRSP Permanent Number: PERMNO = 10107)
- Time Range: April 1986 to December 2024
- Extracted Variables:
  - `date`: Monthly trading date
  - `ret`: Monthly total stock return
  - `vol`: Monthly trading volume

### Tools & Programming Libraries
- Python 3
- `wrds`: WRDS database official connection interface
- `pandas`: Tabular data processing and cleaning
- `matplotlib`: Time-series chart visualization

### Full Project Workflow
1.  Import required Python libraries
2.  Establish secure connection to personal WRDS account
3.  Extract Microsoft stock data via standard SQL query statements
4.  Preprocess data: datetime format conversion and missing value elimination
5.  Generate descriptive statistical summary of returns and volume
6.  Create dual-axis time-series plot for monthly return and trading volume trend
7.  Calculate core financial metrics: cumulative return, annualized return, return volatility, maximum drawdown
8.  Automatically save output charts to local directory
9.  Safe closure of WRDS database connection session

### Key Project Outputs
1.  Cleaned structured stock dataset
2.  Descriptive statistics table
3.  Dual-axis trend plot of monthly return and trading volume
4.  Calculated long-term risk and return financial indicators

### How to Run the Code
1.  Install all dependent libraries in advance: `wrds`, `pandas`, `matplotlib`
2.  Open the `analysis.ipynb` Jupyter Notebook file
3.  Run all code cells in sequential order
4.  Enter personal WRDS username in the database connection cell
5.  All charts and statistical results will be generated automatically

### AI Disclosure
All code framework, analysis logic and operation steps follow the in-class teaching content of ACC102. AI tools are only used for auxiliary document sorting and standard README format optimization. All data query logic and financial calculation principles are completed according to course requirements.
