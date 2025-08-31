## Objective
The project analyzes the relationship between trader behavior (profitability, leverage, volume, risk) and market sentiment (Fear vs Greed index). The aim is to identify hidden trends or signals that can help design smarter trading strategies.Also an ML model is made using CatBoost.

## Datasets
1. Historical Trader Data  
   - Columns include: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp IST`, `Closed PnL`, `Leverage`, etc.

2. Bitcoin Market Sentiment (Fear & Greed Index)  
   - Columns include: `date`, `value`, `classification` (Fear, Greed, Extreme Fear, Extreme Greed).

## How to Run
1. Open the notebook in Google Colab:  
   - [Insert your Colab link here]  
   (Make sure the notebook is set to “Anyone with the link can view”)

2. Run all cells in `notebook_1.ipynb`.  
   - https://colab.research.google.com/drive/1JSrriGafaVGIeXBtn16Dum3jYl6bhlsl?usp=sharing
   `  
   - Visualizations will be stored in `outputs/`

3. Refer to `ds_report.pdf` for summarized insights and conclusions.

## Outputs
Some of the outputs included in `outputs/`:
- `pnl_vs_sentiment.png` - Scatterplot of PnL vs sentiment  
- `leverage_boxplot.png` - Leverage distribution during Fear vs Greed  
- `risk_profiles.png` - Profitability segmented by risk-taking behavior  

## Notes
- Raw data files were provided in the assignment.  
- Intermediate CSVs are stored in `csv_files/` for reproducibility.  
- Analysis code is written in Google Colab (Python, Pandas, Matplotlib, Seaborn).  
- The structure follows the exact submission guidelines.  
