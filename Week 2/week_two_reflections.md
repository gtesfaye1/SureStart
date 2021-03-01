## Day 8: 02/15/2021

 Today I learned more about Convolutional Neural Networks. For todays action item, I followed and
 extended the CNN tutorial Notebook posted on Kaggle. After extending the tutorial, I was able 
 to improve the accuracy of the model to 98.58% 

## Day 9: 02/16/2021

## Day 10: 02/17/2021

 Today I learned more about the structure of CNNs and the differences that they have with fully 
 connected neural networks. CNNs use convolution mechanisims to filter over an image scanning a few 
 pixels at a time, and creates a map to predict where each feature belongs. It then uses a Pooling layer
 to reduce the amount of information needed to predict a feature and tries to only maintain the 
 most important feature elements. Finally it then has a fully connected input layer that takes in
 the output of previous two layers, and flattens them into a single vector for which probabilies 
 are then given.
 
 Fully connected nueral networks differ beacuse its neurons connect to all the neurons in the next layer,
 which can cause ineffeciancy issues as modern computer archetechiture cannot handle a Fully connected neural 
 network with large input like 4K images (4000 pixels).
 
 ## Day 11: 02/18/2021
 
 Improved the accuracy from my CNN model from 98.58% to 98.86%. Code can be found <here>[1] 
 
 
 ## Day 12: 02/19/2021
 
 Learned about image classication more in depth today and modifyed an already built CNN to classify images. Code
 can be found <here>[1]. 
 
 Since training took a signifcant amount of time, I wasnt able to play around with the parameters as much as would have
 liked. I did notice though, that fewer epochs made the model more accurate as that led to less overfitting.

