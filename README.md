# Cryptocurrencies

This challenge, uses unsupervised learning to analyze data on the cryptocurrencies traded on the market.<br>

## We follow the general steps of:<br>
<b>Data Preprocessing</b><br>
Cleaned the data of "bad/unneeded" values. Ending with converting the text data to numeric using dummies<br>
![](readme_images/preprocessing.png)

<b>Reducing the data dimensions leveraing PCA</b><br>
Used Principal Component Analysis to reduce the dimensions down to the suggest (3) PCs<br>
![](readme_images/pcTable.png)

<b>Clustering the cryptocurrencies using K-means</b><br>
Using Intertia & and Elbow to determine that the approriate K=4 for clustering<br>
![](readme_images/elbow.png)

Then created a new summary Dataframe with the cryptocurrency information and the PCA values<br>
![](readme_images/summaryFrame.png)


<b>Finally creating a few visualizations</b><br>
![](readme_images/3D_scatter.png)

![](readme_images/3D_scatter_B.png)

![](readme_images/hvplotTable.png)

![](readme_images/2D_scatter.png)