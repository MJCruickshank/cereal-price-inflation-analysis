# Cereal Price Inflation Analysis
Analyse cereal price inflation and for developing countries with data visualisation.

![image](https://user-images.githubusercontent.com/78884789/121784143-8e7b6200-cbb2-11eb-971d-720b7b3f00e9.png)

## How To Run the Inflation Analysis

**Open `Global Food Prices.ipynb` and do the following:**
1. Download World Food Programme data
Download [wfpvam_foodprices.csv](https://data.humdata.org/dataset/wfp-food-prices)
2. Point dataframe, `df`, to read from the location where you saved `wfpvam_foodprices.csv`

`df = pd.read_csv('/your_path_to/wfpvam_foodprices.csv')`

3. Modify timeframe according to your needs
Currently, the inflation analysis is conducted on a 6 month horizon, with start month October 2020 and end month April 2021. However, if you'd like to change the time window of analysis or start and end month, modify accordingly.
