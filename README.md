# Analysis of fruits and vegetables prices in Mercado Central de Buenos Aires

Check full report here: [Social Data Tech](https://socialdatatech.com/cheapest-fruits-and-vegetables-per-month/)

## Repo structure
### Getting data
get_data_fruits.ipynb and get_data_vegetables.ipynb download and unzip data from http://www.mercadocentral.gob.ar/.

There is one file per day with the price for each vegetable/fruit per kilo.

The script perform data cleaning and transformation and outputs a csv with all the dates. 

### Analysis
analysis_fruits.ipynb and analysis_vegetables.ipynb read csv with all the fruits and vegetable prices per day and make
tables and plots.

Inflation: To make the prices comparable across the time and isolate them from inflation, the daily price was converted to USD applying the official exchange rate for each day.

* Icons in plots were downloaded in https://www.freepik.com/flaticon
