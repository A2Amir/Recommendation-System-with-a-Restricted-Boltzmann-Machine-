# Recommendation System with a Restricted Boltzmann Machine 

In [this notebook](https://github.com/A2Amir/Recommendation-System-with-a-Restricted-Boltzmann-Machine-/blob/master/Collaborative_Filtering_with_RBM.ipynb), I study and w over the usage of a [Restricted Boltzmann Machine](https://github.com/A2Amir/Restricted-Boltzmann-Machines) (RBM) in a Collaborative Filtering based recommendation system. This system is an algorithm that recommends items by trying to find users that are similar to each other based on their item ratings.


<b>
   
Table of Contents

   1. Acquiring the Data
   2. Loading in the Data
   3. The Restricted Boltzmann Machine model
   4. Setting the Model's Parameters
   5. Recommendation
   
 </b>  
   



To start, you need to download the data you are going to use for the system. The datasets you are going to use were acquired by <a href="http://grouplens.org/datasets/movielens/">GroupLens</a> and contain movies, users and movie ratings by these users.

to download datasets you can use the below code:

~~~python
!wget -O ./data/moviedataset.zip http://files.grouplens.org/datasets/movielens/ml-1m.zip
!unzip -o ./data/moviedataset.zip -d ./data
~~~


