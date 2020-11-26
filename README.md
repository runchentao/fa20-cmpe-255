# fa20-cmpe-255
- San Jose State University
- Fall 2020 - CMPE 255 Data Mining

## Team Members
- Xuan Shi
- Runchen Tao
- Xueli Yang

## Project Dataset Selection
[Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)

## How to compile program
  1. Download 6 source data files from [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)
  1. Download .ipynb files in this repo
  2. Open it in Jupyter Notebook or Google Colab
  3. Configire the file path based on your settings
  4. Now you are ready to compile

## How to load model
  
  1. If you already have a testing and training set ready, it is easy to just load the model and use it to make prediction
  2. Download the .sav files in this repo
  3. ```import pickle```
  4. ```load_model = pickle.load(open("SAV_FILE_PATH", 'rb'))``` Edit SAV_FILE_PATH based on your directory 
  5. Now you are ready to use the loaded model
  
## How to load subtest
  1. Download subtest from repo
  2. ```import pickle```
  3. ```subtest = pd.read_pickle("FILE_PATH")``` Edit FILE_PATH to your file location of subtest
  4. *This subtest contains 1% data of the testing set
