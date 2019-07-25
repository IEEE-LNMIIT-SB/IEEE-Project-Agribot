# IEEE-Project-Agribot
This IEEE project involves development of a chat-bot for agriculture which can assist farmers.
Initial phase involves:
Andorid app development
Disease detection in crops
Weed detection in crops

# Resources 

* Google Doc Link :- [Leaf Detection IEEE](https://docs.google.com/document/d/1nCRV0rKZPA8pAbzRU6rEWbEFcS2zgqy8VJRXBMh19io/edit)

  This docs file has the links to the datasets found for leaf detection. It also contains details about different leaf diseases.

# Project-UI 
  [Github Link](https://github.com/Dharmesh-Poddar/IEEE-Project-Agri-Care)
  
# Table of Models

  | Sr. No.  | Model description | Link to model summary | % Trained data | Epochs |  Accuracy (Train) | Accuracy (Validation) | 
  | ---------| ----------------- | --------------------- | -------------- | -------| ----------------- | -------------------- |
  | 1 | Convolution + Pooling + Dropout + Flatten + Dense | [Model 1](https://raw.githubusercontent.com/IEEE-LNMIIT-SB/IEEE-Project-Agribot/master/images/modelv1.JPG) | 10% | 1 | 8.44 % | 8.4375 % |
  |2.0|MobileNetV4 + Dropout + Dense(ReLU) + Dropout2 + Dense2 | [Model 2_0](https://raw.githubusercontent.com/IEEE-LNMIIT-SB/IEEE-Project-Agribot/master/images/modelv2_0.JPG)| 100% | 5 | 85.69 % | 92.13 % |
  |2.1|MobileNetV4 + Dropout + Dense(LeakyReLU) + Dropout2 + Dense2 | [Model 2_1](https://raw.githubusercontent.com/IEEE-LNMIIT-SB/IEEE-Project-Agribot/master/images/modelv2_1.JPG)| 100% | 5 | 87.20 % | 92.40 % |
  
# Research Papers for reference

* [Integrated IP Approach](https://www.researchgate.net/profile/Diptesh_Majumdar/publication/282783352_REVIEW_DETECTION_DIAGNOSIS_OF_PLANT_LEAF_DISEASE_USING_INTEGRATED_IMAGE_PROCESSING_APPROACH/links/561c76f408ae6d17308b191f.pdf)

* [Plant Disease Classifiaction using CNN and Generative Adversial Networks](https://www.frontiersin.org/articles/10.3389/fpls.2016.01419/full)


* [Going Deeper with Convolutions](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf)

  *This might help to learn about CNN's mentioned in the previous paper i.e. Plant Disease Classification using CNN*
  
* [Object Detection and Bounding boxes](https://www.d2l.ai/chapter_computer-vision/bounding-box.html)

* [Stanford Research Paper for Plant Disease Detection](http://cs231n.stanford.edu/reports/2017/pdfs/325.pdf)

* [Plant Leaf Disease Detection and Classification Using Image Processing Techniques](https://pdfs.semanticscholar.org/9426/ae4ea4329521265c738e78221d1aff532537.pdf)

# Code References 

* [Tensorflow: Load Data](https://www.tensorflow.org/tutorials/load_data/images)
* [mc.ai implementation](https://mc.ai/plant-disease-classification-with-tensorflow-2-0/)

# What's next?

* Linking the model to the web application to dynamically upload images and test for disease
* Improving the model for better accuracy
