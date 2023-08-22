Detecting Anomolies in Wafer Manufacturing

- Bryan Walsh

ASIC companies spend many resources for producing quality products within the automotive and medical device industries.  Detecting issues at the Wafer level can greatly save on those resources as manufacuring levels increase.

Can we use machine learning techniques to categorize anomolies and build a model to predict future problems?

I based my studies on the following dataset found on kaggle.com:
https://www.kaggle.com/datasets/arbazkhan971/anomaly-detection

I explored using ML models such as Logistic Regress, K-Nearest Neighbors, Naive-bays and Support Vector Machines.

The dataset was challenging because only 8% were labeled as anomolies. K-Nearest Neighbors seemed to provide the best predictions.

I would like to look further into the predictions using different training and test setups.  It seemed the results were very sensitive to the split.  And stop using SVC, its too slow.

See 'data_exploration.ipynb' for more info.
