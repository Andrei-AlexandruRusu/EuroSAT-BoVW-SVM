# EuroSAT-BoW-SVM
EuroSAT Image Classification with Bag of Words and SVM

Group project that focuses on the performance of the Support Vector Machine (SVM) classifier on the EuroSAT dataset. To extract significant features from these images, a method based on the Bag-of-Visual-Words algorithm was implemented. The process of extracting descriptors from the images was performed using the Scale-Invariant Feature Transform (SIFT) algorithm, and then the descriptors were grouped into a dictionary using the K-Means algorithm. Following the clustering algorithm application, we managed to obtain an efficient representation of information from the images. 

The EuroSAT dataset consists of 27,000 images labeled with 10 different classes of land cover and land use, and it is made available to the public [1]. The images measure 64x64 pixels, and each class contains between 2,000 and 3,000 images.

![image](https://github.com/Andrei-AlexandruRusu/EuroSAT-BoW-SVM/assets/92977944/325d3a0b-5c36-4ee8-addb-59a31dbc4106)

  EuroSAT dataset: Land Use and Land Cover Classification with Sentinel-2 ([1])

The SVM classifier was trained on these representations to achieve accurate classification of the images into their respective classes. The best results were obtained with a classification accuracy of 91.92% for two classes, by applying the Bag of Words method, the SIFT algorithm, clustering descriptors with the K-Means algorithm, and utilizing the SVM classifier. These performances were achieved in the context of a 70% training set and a 30% test set for RGB images. In the case of classification using 3 classes, the overall accuracy on the entire test set used is 85%.

## Resources: 

  [1] Eurosat: A novel dataset and deep learning benchmark for land use and land cover classification. Patrick Helber, Benjamin Bischke, Andreas Dengel, Damian Borth. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2019.

  [2] Introducing EuroSAT: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification. Patrick Helber, Benjamin Bischke, Andreas Dengel. 2018 IEEE International Geoscience and Remote Sensing Symposium, 2018.
