# DeepFashion
A Fashion Product Recommender System

**Objective:**
    The objective of this project is to develop a two-stage deep learning framework
    that recommends fashion images based on other input images of similar style. For
    that purpose, a Convolutional neural network classifier is used as a data-driven,
    visually-aware feature extractor. The latter then serves as input for
    similarity-based recommendations using a ranking algorithm. Our approach is
    tested on the publicly available Fashion dataset.
    
**Data Files used:**
  -  styles.csv- 10 Columns describing the details such as category,type,id etc. of the images.
  -  Data : 40,000 images. 
   
    
**Code file:**
    **Fashion_Product_Recommender_Sys.ipynb.** 
    This file reads the csv data file, pre-processes the data, builds the CNN model
    and trains the model using the images data and finds the accuracy and loss of
    the built CNN model. The model, finally, classifies the query product and
    recommends similar products.
    
**Modules Used:**
  -  OpenCV
  -  TensorFlow
  -  Keras
  -  Sklearn
  -  Matplotlib
  -  Numpy,Pandas

