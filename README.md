# Image-Caption-Genarator

This project is all about generating caption of images. Flickr_8k dataset was used in this project. All the necessary instructions you will find on the notebook file. You can use this notebook as reference and can build and try new models. 

## Dataset Description
To understand this code, we need to have idea about how the dataset is organized. I have used Flickr8k dataset which can be found on [this](https://www.kaggle.com/ming666/flicker8k-dataset) link. You have to keep the folders Flicker8k_Dataset and Flickr_Text inside the dataset folder.<br>
The Flicker8k_Dataset has all the images - train,test,validation, with unique id. The Flickr_Text folder has some txt file , We need four text files.<br>
Flickr8k.token.txt  --- Contains 4 captions for every image id<br>
Flickr_8k.trainImages.txt --- Contains The names of train images<br>
Flickr_8k.devImages.txt --- Contains the names of dev images<br>
Flickr_8k.testImages.txt --- Contains the names of test images<br>

## References
1. https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/
