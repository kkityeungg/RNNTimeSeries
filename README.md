# Prediction of Rossmann Store Sales
# 1. Data description
- A set of data on Rossmann Store Sales (RSS) from Kaggle website.
- Rossmann operates over 3,000 drug stores in 7 European countries.
- Day, Month, Year, StoreID, Open, Promo and Promo2 from training are used.

# 2. Data pre-processing
The data was sorted first according to the StoreID then the Year then the Month and finally the Date of the training file, In order to get the sorted data set consisting of every StoreID with their date of sales sorted.

We were focusing on the effect of promotion to predict the sale so we dropout the other columns.

# 3. Model
- Recurrent Neural Network(RNN ) which is a type of artificial networks that applied to sequence data mainly used for time series prediction.
- RNNs are classes of  neural network that allows previous outputs to be used as inputs while having hidden states.
- Trying to predict the data using five time frames for all the stores.
- Used Long Short Term Memory which is modified version of RNN and it uses forget gates to forget  some data and retain the others.

# 4. References
1. https://www.kaggle.com/c/rossmann-store-sales/data
2. https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks
3. https://builtin.com/data-science/recurrent-neural-networks-and-lstm

## Authors

- [@kkityeungg](https://github.com/kkityeungg)


## Feedback

If you have any feedback, please reach out to me at kit63020618@gmail.com
