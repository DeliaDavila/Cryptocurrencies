# Cryptocurrencies

## Overview of Project
This project was completed to investigate cryptocurrencies available on the trading market. The client, Accountability Accounting, is considering a cryptocurrency investment portfolio for its customers. To begin understanding the market, the company wants to use a clustering algorithm with unsupervised learning to begin understanding how available cryptocurrencies could be grouped. Data visualizations will allow the information on potential groups, as well as outliers, to be presented.

## Process
The initial data was cleaned to remove limit the data to currencies currently being traded. Additional cleanup was done to remove incomplete data and adjust the format of the data to be usable by machine-learning algorithms. 

Once the cleanup was complete, analysis was done to determine what number of groupings to break into. Machine learning was used to fit the data into the groups and data visualization was used to render the groups in 3D.

## Model
 
![3Dmodel](https://github.com/DeliaDavila/Cryptocurrencies/blob/main/Images/3Dmodel.png)

## Understanding the groups
These groupings do not indicate final decisions to be made by the company. These are simply shown as a means for determining potential launching points for further investigation.

The groups may represent valuable differences but may also represent incidental similarities. For example, the words "apple" and "appaloosa" may have similarities, but might end up in the same group "begins with letter A" or different groups, "food" and "horse breeds". Other groups may bring them together, "somehow related to horses", or drive them further apart.

Unsupervised learning is used to sort through data and suggest groupings, but then data analysts must examine the groups of data to come up with theories of how these groups occur and what drives the differences. They can then train and fit algorithms to run supervised machine learning. Algorithms are again trained to determine whether they accurately predict further data. Theories can be tested and proved or disproved until a working model is established. 

The company can then use the model to made decisions about how to select cryptocurrencies for inclusion into their crypto portfolio.

## Results and suggestions
One initial finding that is evident from this initial pass is a significant outlier in the data, represented in the model by a red X. This currency is BitTorrent, which is not commonly known as a cryptocurrency so might best be removed from the dataset. The points represented in the model by purple squares might also be investigated as potential outliers.

Once the suggested groupings have been looked at by analysts, they will have a sense of whether the groupings are logical or incidental, as explained above. The unsupervised learning could be run again with an increased number of groups. This may allow for some theories to be come more evident. 

Data analysts will set up theories, then run supervised machine learning to determine whether they accurately predict further data. Theories can be tested and proved or disproved until a working model is established. The company can then use the model to made decisions about how to select cryptocurrencies for inclusion into their crypto portfolio

