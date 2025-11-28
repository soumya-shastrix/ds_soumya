Data Science Project – Trader Behaviour and Market Sentiment


This is my simple data science assignment where I tried to understand
how traders behave when the market is in Fear or Greed. I joined two datasets:
one with market sentiment and one with trader activity. After that,
I did some cleaning, created a few features, and made one bar graph to compare
total trade value in Fear vs Greed days.






 Project Folder Structure


ds_soumya/
├── notebook_1.ipynb           
│   ├── fear_greed_index.csv  
│   └── historical_data.csv  
├── outputs/                        
│   └── trade_value_vs_sentiment.png  
├── ds_report.pdf                   




What  did in This Project


*  Cleaned the datasets (removed duplicates and missing values)
* Converted date and time columns into proper format
* Joined (merged) the sentiment data and trader data using dates
* Did simple EDA (value counts, average profit, etc.)
*  Made a bar graph comparing trade value in Fear vs Greed days






 Output of My Project


*  bar graph: trade_value_vs_sentiment.png
*  PDF report:ds_report.pdf 
*  clean and working notebook: notebook_1.ipynb




 How to Run This Notebook


*  Open `notebook_1.ipynb` in Google Colab.
*  Upload both CSV files from `csv_files` folder.
*  Run the cells from top to bottom.
*  The graph and results will appear automatically.
