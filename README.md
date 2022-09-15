# Cdiscount-s-Image-Classification-Challenge
## Description

Cdiscount.com generated nearly 3 billion euros last year, making it France’s largest non-food e-commerce company. While the company already sells everything from TVs to trampolines, the list of products is still rapidly growing. By the end of this year, Cdiscount.com will have over 30 million products up for sale. This is up from 10 million products only 2 years ago. Ensuring that so many products are well classified is a challenging task.

Currently, Cdiscount.com applies machine learning algorithms to the text description of the products in order to automatically predict their category. As these methods now seem close to their maximum potential, Cdiscount.com believes that the next quantitative improvement will be driven by the application of data science techniques to images.

In this challenge you will be building a model that automatically classifies the products based on their images. As a quick tour of Cdiscount.com's website can confirm, one product can have one or several images


This code was used to train Xception model for Kaggle competition Cdiscount’s Image Classification Challenge. In principle, the competition was about standard image classification, however following points made it difficult:

* Large number of categories (5720)

* Big training data (58.2 GB, 7 million products each having up to 4 images)

* A lot of difficult categories (different styles of books and CDs)

* Variable number of images (1-4) for each product

* More than 15 million images at 180x180 resolution


1. Training using keras generator <a href="https://github.com/neilrathod1997/Cdiscount-s-Image-Classification-Challenge/blob/main/keras_generator_for_reading_directly_from_bson%20(1).ipynb">here</a>

2. Training using Keras flow_from_directory method <a href="https://github.com/neilrathod1997/Cdiscount-s-Image-Classification-Challenge/blob/main/Final_training.ipynb">here</a>

3. BLog on above work <a href="https://medium.com/@neilnaik/cdiscounts-image-classification-challenge-a6818298b6c2">Link</a>
