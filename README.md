# K-Nearest-Neighbor

K-Nearest Neighbour is one of supervised learning other words called KNN. Supervised learning algorithm where the new label are classified based on the majority of the k-nearest neighbor category. The Nearest Neighbor method is classified as a lazy learner because this method delays the training processor does not do it at all until there is test data that the class label wants to know. When there is test data for which you want to know the class label, then the new NN method will run the algorithm.


The KNN algorithm is managed based on the concept of proximity or distance of data to other data, with the K value indicating the closest amount of data used for data class classification. The selection of the K value is one thing that greatly affects the performance of the KNN method. K-values that are too small or too large will result in the prediction results being sensitive to noise. There is some risk that the selected data is irrelevant because the majority of the data selected can be from data of different classes or too far from the data that the class label wants to recognize. Another issue related to the selection of K values is the selection of K values with odd or even values. If the K score is odd, the risk of two or more classes getting the same number of votes is very small. Meanwhile, when the K score is even, there is also a risk that two or more classes have the same number of votes.

 K-Nearest Neighbor algorithm for Classification has some steps as follows: 
1. Determine the value of K.
2. Calculating the distance between the training data and the testing data. If the data is numerical data, one of the methods can be used in calculating the distance between the training data and the test data is the euclidean distance, with the following formula:
![image](https://user-images.githubusercontent.com/10173320/97101256-7069fb80-16ce-11eb-80c9-ec338696968c.png)
3. Sort the closest distance. The data that has been calculated the value of the euclidean distance will be sorted based on the smallest value for each K, so that will obtained the closest distance value between the training data and the testing data.


Refrences:
- Prasetyo, E. (2014). Data Mining Mengolah Data Menjadi Informasi Menggunakan Matlab, Yogyakarta: Andi Publisher.
- Han, J., Kamber, M., dan Pei, J. (2012). DATA MINING. Concepts and Techniques. Third Edition. Morgan Kaufmann Publishers.
