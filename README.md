# GoogePlay_TextCleaning_NaiveBayesClassifier
This project has several parts. The first part invovles scraping GooglePlay for review comments. The second part involves creating a library of positive and negative reviews based on star ratings, and the third part invovles text cleaning and  applying a NaiveBayes classifier. The current Naive Bayse model has an uneven number of positive and negative classes.  But still, the model was able to predict review comments with a 70% accuracy. 

Next steps for improving the model:
1) Improve the model by turning text into lower case 
2) Using selenium to get more comments 
3) Becuase games on GooglePlay tend to have positive ratings, I would need to apply more weight to the negative texts to balance the model
