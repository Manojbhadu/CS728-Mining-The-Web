I have implemented baseline model.

Approach:
1. Take the CLS embeddings of every query
2. Train classifier model on these embeddings
3. There can be multiple embeddings so, 5 different model trained(assuming there will be atmost 5 type of one query)


Accuracy:
1. For tpye1( which is not none for every sentence):
	1) Accuracy: 0.63, Precision: 0.58, Recall 0.63, F1 score =0.57
2. For tpye2( which is  none for very rare sentences):
	1) Accuracy: 0.72, Precision: 0.65, Recall 0.72, F1 score =0.68

3. For tpye3( which is  none for 35% sentences):
	1) Accuracy: 0.74, Precision: 0.71, Recall 0.74, F1 score =0.72

4. For tpye4( which is  none for 65% sentence):
	1) Accuracy: 0.84, Precision: 0.84, Recall 0.84, F1 score =0.84

5. For tpye1( which is none for almost every sentence):
	1) Accuracy: 0.98, Precision: 0.98, Recall 0.98, F1 score =0.98



To Run the code:
1.upload 	WebQSP dataset on drive and mount the drive and change the directory according to location of dataset
2.Run code sequentially

