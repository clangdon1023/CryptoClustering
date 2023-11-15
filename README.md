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

* Best Value of K using the Original Scaled DataFrame
  
![Best Value of K Using the Original Scaled DataFram]("https://github.com/clangdon1023/CryptoClustering/blob/main/Resources/Original%20Data.png")


* Best Value of K using the PCA data
  
<img width="714" alt="https://github.com/clangdon1023/CryptoClustering/blob/main/Resources/PCA%20Elbow.png">


* 4 was found to be the best value for K in both Elbow Curves

* Scatter Plot
  
<img width="714" alt="https://github.com/clangdon1023/CryptoClustering/blob/main/Resources/Scatter%20Plot.png">
