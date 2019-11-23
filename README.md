# Recommendation System with a Restricted Boltzmann Machine 

In this notebook, we study and go over the usage of a Restricted Boltzmann Machine (RBM) in a Collaborative Filtering based recommendation system. This system is an algorithm that recommends items by trying to find users that are similar to each other based on their item ratings. 


Table of Contents

   1. Acquiring the Data
   2. Loading in the Data
   3. The Restricted Boltzmann Machine model
   4. Setting the Model's Parameters
   5. Recommendation
   
   

Acquiring the Data

To start, we need to download the data we are going to use for our system. The datasets we are going to use were acquired by GroupLens and contain movies, users and movie ratings by these users.

After downloading the data, we will extract the datasets to a directory that is easily accessible.


