# Cereal Price Inflation Analysis
Analyse cereal price inflation and for developing countries with data visualisation.

![image](https://user-images.githubusercontent.com/78884789/121784143-8e7b6200-cbb2-11eb-971d-720b7b3f00e9.png)

## How To Run the Inflation Analysis

### 1. Install package dependency requirements

```console
$ pip3 install -r requirements.txt
```

### 2. Download World Food Programme dataset
- Navigate to [Global Food Prices Database (WFP) homepage](https://data.humdata.org/dataset/wfp-food-prices) where dataset is hosted and download `wfpvam_foodprices.csv`

### 3. Move dataset to expected location
The analysis Jupyter notebook, `Global Food Prices.ipynb`, expects the dataset to be saved locally in this repository folder at the root level. 

If you want to save it in a different location, update `Global Food Prices.ipynb` to read from the location you saved it to when initializing the dataframe, `df`:

`df = pd.read_csv('/your_path_to/wfpvam_foodprices.csv')`

### 4. Open inflation analysis Jupyter notebook

```console
$ jupyter notebook
```

Then navigate to browser where the `Global Food Prices.ipynb` notebook was launched & execute cells (Cells > Run All)

### 5. (Optional) Modify analysis timeframe according to your needs
Currently, the inflation analysis is conducted on a 6 month horizon, with start month October 2020 and end month April 2021. However, if you'd like to change the time window of analysis or start and end month, modify accordingly.
