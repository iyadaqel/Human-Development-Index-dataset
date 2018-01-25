# Human Development Index dataset
When i needed to access Human Development dataset, i was surprised to see that the data is not offered through APIs, i tried many python libraries i found online but all failed to retrieve data. So, i decided to scrape it from the website myself. 

## Files: 
The code is split into two notebooks:   
* **Scrapping Human Development Index.ipynb**   
which will load the csv `HDI_KPIs.csv` The file only has the urls for all HDI indicators which will be used to scrape the data. The code will scrape all the indicators and store each one of them in a seperate csv in `input_data` folder. 

* **Human Development Index.ipynb**   
This notebooks will load all the csvs, clean the data and store it in `HDI-complete.csv` inside `output_data` folder. 



