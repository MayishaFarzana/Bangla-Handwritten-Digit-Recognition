# Bangla-Handwritten-Digit-Recognition
**Introduction:** Automatic recognition of Bengali handwritten characters and numeral digits needs to be digitized to make the communication smoother. Many research works and models
have been proposed to recognize Bengali handwritten characters and numeral digits so far, but a huge scope is still there to improve this task in terms of accuracy and 
applicability. <br>
Images of handwritten digits are different from natural images as the orientation of a digit and the similarity of features of different digits make confusion. 
Here we have used this experiment using logistic regression. However, after that, we have used a deep neural network. Using this model will increase the accuracy.
It provides better performance.

**All results showing in the table using Deep Neural Network:-**

|                | First Try     | Second Try    | Third Try | Fourth Try |
| :------------- | :----------: | -----------: |-----------: |-----------: |
|  Batch Size | 220  | 210    |220| 225|
| Num of Iters   | 10000 | 9000 |9000 | 10000|
|Number of hidden layer| 250|250|250|250|
|Optimizer|Adamax|Adamax|Adamax|Adamax|Adamax|
|  Learning Rate | 0.001   | 0.001    |0.001| 0.001|
|  Accuracy | 79.59%  | 77.22% | 77.37% | 78.76%|
| Loss| 0.68 | 0.59 | 0.69| 0.51|

**Results:**
From the above table, we can see that we can get a good accuracy by fixing all the hyperparameters and increasing the batch size and number of iterations.
We have used the Adamax optimizer here, which provides better performance. Using a deep neural network, we can secure 79.59% accuracy, which is quite good.
Before using logistic regression, we could not get much accuracy then. We use a deep neural network, where there are multiple hidden layers and activation functions
improve accuracy.


**Conclusion:** We presented a deep neural network-based Bangla digit recognition method for a typical and challenging dataset in this issue. 
Compared to other unbiased datasets, we obtained 79.59% percent research precision, which is a positive outcome for the massive and impartial NumtaDB dataset.
We discovered that using only a deep classification model to improve efficiency is ineffective. Before preparation, all types of image preprocessing are essential. 
We use some preprocessing techniques for blurry and noisy videos, but they are insufficient for high efficiency. Using the CNN model, we can get better performance.
.
