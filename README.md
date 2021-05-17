# LINEAR_CLASSIFIER (ASSOCIATION-IMAGE-CAPTION)    
The task of this project is to recognize if an image-text couple matches.
In order to achieve this task we created two RNNs and one classifier.
We used Glove pre-trained embeddings for text and the output of an object detection operation for images in pytorch format (.pt).
Precision and accuracy are both around 88% after fifty epochs of training.

# SETUP
* google Colaboratory (colab)    
* google drive    
# DATA    
* “2014 Train/Val annotations”     
* Glove 6b.zip    
* images features and classes    
# ILLUSTRATION    
An example on how it works:
![Example](https://user-images.githubusercontent.com/84068726/118475014-06698000-b70c-11eb-9437-c1a167229848.png)
# ISSUES AND IMPROVEMENTS
* speed up the elaboration process by using two dictionaries, one containing images id and vectors, the other containing captions id and embeddings
* use a flexible padding
