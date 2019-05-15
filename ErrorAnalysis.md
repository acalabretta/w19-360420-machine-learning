Sebastian Cobuzzi, Alessandro Calabretta

Classification report

1)	We get a different level of accuracy due to the randomness involved in the concept. The data taken into consideration (in this case the breast cancer data), is shuffled causing the accuracy levels to vary. 

2)	The Euclidean distance plays a big role in this portion. The frequency at which the Euclidean distance is small will give us a good baseline to compare our results to, the higher the frequency of small distances, the more we could be sure of our answers.

3)	False positive: When looking at the data as a whole, the selected data will be split into false positives and true positives. False positives are the data points where the data is taken in as following the baseline however should not be. In other words, the condition was accepted when it should not have been. 

False negative: The false negatives are in the portion of that data that is relevant. False negatives are the data points where the data taken as not following the baseline when it was. In other words, the condition was rejected when it should have been accepted.

4)	Precision divides the true positives with the entire data taken in. The result will declare the number of selected data points that are relevant. Recall on the other hand divides the true positives with all the relevant data points. The result will declare the number of relevant data points that are selected. 

5)	A good baseline for these measures will be a large level of accuracy within each of the precision and recall measures.

6)	The algorithm will take in the hyperparameter and will learn it which will eventually cause the data to be more precise, meaning the level of accuracy will increase. 

