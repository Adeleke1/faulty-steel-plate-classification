# faulty-steel-plate-classification
* This project focuses on classifying the type of surface defect present in stainless steel plate.
* 7 types of defects are present in stainless steel plate  namely Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, with the last one classified as Other_Faults 
* There are 34 fields. The first 27 fields describe some kind of steel plate faults seen in images. Unfortunately, there is no other information that I know of to describe these columns.
The last seven columns are one hot encoded classes, i.e. if the plate fault is classified as "Stains" there will be a 1 in that column and 0's in the other columns
* The aim was to develop a model that predicts the response variable Other_Faults
* KNN algorithm was used, consideting a range of k-values and selecting the optimal value.
* Manhattan and Euclidean Distance were considered
* Accuracy vs K plots and matrix confusion was provided for each case
* Feature importance study was also used to extract the most important features
