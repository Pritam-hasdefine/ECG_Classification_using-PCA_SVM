# ECG_Classification_using-PCA_SVM
 Basic Working Algorithm
1. Load the data and annotations
2. For Using PCA on the data we first scale the data
	this is done using StandardScaler function of SKLEARN.
3. Once the Scaling is done we apply PCA we normalize our features by subtracting the mean and scale it to unit variance, using StandardScaler. 
	So, we start of by selecting 3 orthogonal components. 
4. After PCA is applied we split it data in train and test set.
5. We then put or data in SVM model to generate our classifier. SVM's C_value = 1 generates the best result.
6. Then we use our test data to test our classifier.
7. We plot the confusion matrix.
