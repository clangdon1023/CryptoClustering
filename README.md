# CryptoClustering

Challenge using unsupervised learning to find the best value fo "k".

* Prepare the data using Pandas DataFrams
* Find the best value for K using the original scaled DataFrame
*  Cluster Cryptocurrencies with K-means using the original scaled data
  - create elbow chart
*  Optimize clusters with principal component analysis(PCA)
*  Find the best value for K using the PCA data
  - create elbow chart
* Cluster Cryptocurrencies with K-means Using the PCA Data
* Combine elbow charts for a compartitive anaylsis


Results

![Original Data](https://github.com/clangdon1023/CryptoClustering/assets/139593626/0365f359-8bf6-4d73-87a7-7bd2d6d97c42)



* Best Value of K using the PCA data
  
<img width="714" alt="https://github.com/clangdon1023/CryptoClustering/blob/main/Resources/PCA%20Elbow.png">


* 4 was found to be the best value for K in both Elbow Curves

* Scatter Plot
  
<img width="714" alt="https://github.com/clangdon1023/CryptoClustering/blob/main/Resources/Scatter%20Plot.png">
