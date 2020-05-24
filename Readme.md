# NNFL-Design-Project-2020

This is the [project presentation.](https://github.com/niravbhandari2000/NNFL-Design-Project-2020/blob/master/NNFL%20Project%20Presentation.pdf)
The [Main Model](https://github.com/niravbhandari2000/NNFL-Design-Project-2020/blob/master/ADRNN_Model_Final.ipynb)
is the Associated Deep Recurrent Neural Network model which predicts Open Price, Low Price and High Price of a Stock.
The [LSTM Model](https://github.com/niravbhandari2000/NNFL-Design-Project-2020/blob/master/LSTM_model_for_comparision.ipynb)
and 
[DRNN Model](https://github.com/niravbhandari2000/NNFL-Design-Project-2020/blob/master/DRNN_model_for_comparision.ipynb)
are other existing models which are use for comparison against the main model.

## DATA
The data files are the stock data which can be downloaded from [nseindia.com](https://www1.nseindia.com/products/content/equities/equities/eq_security.htm)
We have arbitrarily taken Tata Motors (ISIN: INE155A01022) stock prices. The files are available in year wise data. We have concatenated 15 years of data [here](https://github.com/niravbhandari2000/NNFL-Design-Project-2020/blob/master/tata_dataset.csv)
## INSTRUCTIONS TO RUN THE PYTHON FILE:
1) To run any file, please open it with google colab, whose link is provided in the github repository itself. 
2) You will have to upload the
[tata_dataset.csv](https://github.com/niravbhandari2000/NNFL-Design-Project-2020/blob/master/tata_dataset.csv)
file while running the command 'uploaded = files.upload()'. This will upload the 
   the dataset to the file.
3) After this all the files will run smoothly.



## Prediction by the final model:

![Prediction by the final model](4fde2e14-dd6a-4cbc-a3b2-55e1f075c2a5.png)

It is evident from the graph that the model works accurately. 

This was compared with the existing models, and result was as follows:- 
