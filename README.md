This project is a Machine Learning algorithm that tries to predict if a customer will churn from a bank or not. The analysis was made with Spark MLLibrary.

After the results obtained, the project was intended to be conected to Kafka from input and output in order to give predictions in weekly batches, and the marketing /sales team have insights to work for and retain more customers for the bank.


import findspark
findspark.init()
import pandas as pd
pd.set_option('display.max_colwidth', None)
