# cereal-price-inflation-analysis
Analyse cereal price inflation and for developing countries with data visualisation.

## 6 month inflation analysis

To run the inflation analysis, open `Global Food Prices.ipynb` and do the following:

1. Download World Food Programme data
Download [wfpvam_foodprices.csv](https://data.humdata.org/dataset/wfp-food-prices)
2. Point dataframe, `df`, to read from the location where you saved `wfpvam_foodprices.csv`

`df = pd.read_csv('/your_path_to/wfpvam_foodprices.csv')`

3. Modify timeframe according to your needs
Currently, the inflation analysis is conducted on a 6 month horizon, with start month October 2020 and end month April 2021. However, if you'd like to change the time window of analysis or start and end month, modify accordingly.
