# Cryptocurrencies

## Overview of Project
This project was completed to investigate cryptocurrencies available on the trading market. The client, Accountability Accounting, is considering a cryptocurrency investment portfolio for its customers. To begin understanding the market, the company wants to use a clustering algorithm with unsupervised learning to begin understanding how available cryptocurrencies could be grouped. Data visualizations will allow the information on potential groups, as well as outliers, to be presented.

## Process
The initial data was cleaned to remove limit the data to currencies currently being traded. Additional cleanup was done to remove incomplete data and adjust the format of the data to be usable by machine-learning algorithms. 
Once the cleanup was complete, analysis was done to determine what number of groupings to break into. Machine learning was used to fit the data into the groups and data visualization was used to render the groups in 3D.

## Summary

### Model
 
![3Dmodel](https://github.com/DeliaDavila/Cryptocurrencies/blob/main/Images/3Dmodel.png)
### Results and suggestions
For the initial unsupervised learning, we chose to use 4 groups. Note: These groupings do not indicate final decisions to be made by the company. These are simply shown as a means for determining potential launching points for further investigation.
One initial finding that is evident from this initial pass is a significant outlier in the data, represented in the model by a red X. This currency is BitTorrent, which is not commonly known as a cryptocurrency so might best be removed from the dataset. The points represented in the model by purple squares might also be investigated as potential outliers.
To reach the goal of understanding how the cryptocurrency market should be split, there are several additional steps that could be taken. Additional models could be run with certain segments of data removed, to determine if the number of logical groups changes. Once groups have been investigated, data analysts can examine the groups of data to come up with theories of how these groups occur and what drives the differences. They can then train and fit algorithms to run supervised machine learning. Algorithms are again trained to determine whether they accurately predict further data. Theories can be tested and proved or disproved until a working model is established. The company can then use the model to made decisions about how to select cryptocurrencies for inclusion into their crypto portfolio

