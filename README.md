# Cdiscount-s-Image-Classification-Challenge
## Description
This code was used to train Xception model for Kaggle competition Cdiscount’s Image Classification Challenge. In principle, the competition was about standard image classification, however following points made it difficult:

* Large number of categories (5720)

* Big training data (58.2 GB, 7 million products each having up to 4 images)

* A lot of difficult categories (different styles of books and CDs)

* Variable number of images (1-4) for each product

1. Training using keras generator <a href="https://github.com/neilrathod1997/Cdiscount-s-Image-Classification-Challenge/blob/main/keras_generator_for_reading_directly_from_bson%20(1).ipynb">here</a>

2. Training using Keras flow_from_directory method <a href="https://github.com/neilrathod1997/Cdiscount-s-Image-Classification-Challenge/blob/main/Final_training.ipynb">here</a>

3. BLog on above work <a href="https://medium.com/@neilnaik/cdiscounts-image-classification-challenge-a6818298b6c2">Link</a>
