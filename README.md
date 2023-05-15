# OUR SOLUTION TO THE PROBLEM AT HAND

- We are trying to solve this problem by creating a Machine Learning model to help in classifying the fraudulent and non-fraudulent transactions.
- Here, we have used a dataset that contains information specifically on credit card transactions database - 2.84L x 31
- So, if the model predicts it’s a fraud given it is really a fraud, the transaction will be cancelled directly, the company will have no costs or just administration fees and the users will not have to pay for the services and goods they never bought.

# IMPACT METRICS
- In the traditional binary classification problems, we try to minimize the loss function such as Log-Loss or maximize metrics like F1-score, Accuracy AUC, etc. But as our dataset is unbalanced here, i.e we have 99% more non-fraudulent data and less than 1% fraud data,these traditional impact metrics may not work accurately.

``
costs = Ei(CFP * FPi + CFN(i) * FNi + CTP * TP + CTN * TN)
Loss cs = Ytrue * (CFN * log(Ypred) + CTP * log(1 - Ypred)) + (1 - Ytrue) * (CFP * log(1 - Ypred) + CTN log(Ypred))
``
# Tech Stack 
```
| Pandas | NumPy | ScikitLearn | MatplotLib |
| Seaborn | Tkinter | Streamlit |
```

