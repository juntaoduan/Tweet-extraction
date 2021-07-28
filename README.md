# Tweet sentiment text extraction
This is a [kaggle competetion](https://www.kaggle.com/c/tweet-sentiment-extraction) I entered. I was interested in using transformer models for questions other than classfication. The difficulty was mainly in the data preprocessing part. There are several things one need to be careful. 
*1. There are errors in the label, roughly 5-10%.
*2. Three sentiment classes are significantly different. See the following.
![TSE1](./figures/TSE_1.jpeg 'TSE1')
![TSE2](./figures/TSE_2.jpeg 'TSE1')
![TSE3](./figures/TSE_3.jpeg 'TSE1')
*3. Expected high noise ratio in the labels which requires ensembling of lots of models. This is due to large variation in human labeling.

I stopped after finding a resonablly good single [model](https://www.kaggle.com/djtere/tweet-sentiment-extraction) which achievess 0.7098 in Jaccard similarity. At the end the winner achieved 0.7362 which requires heavy ensembling.

## Reference
* [Kaggle](https://www.kaggle.com/c/tweet-sentiment-extraction)
