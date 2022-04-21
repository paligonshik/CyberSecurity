# Machine Learning in CyberSecurity
Machine learning plays an increasingly significant role in the building of  Network Intrusion Detection Systems. However, machine learning models  trained with imbalanced cybersecurity data cannot recognize minority data  effectively.<br><br>
Some reasons causing imbalanced data<br>
- In data flow majority class tends to be benign classes, thus making  dataset imbalance.<br>
- The malicious attack approaches changes over time and very few samples can be seen or labeled

The imbalance problem is prevalent in  Cybersecurity which can significantly deteriorate the  performance of Machine Learning models.
New types of attacks are constantly developed  which could be absent from training dataset and  can be misclassified as “benign”.
Proposed Solution:<br>
- Undersampling or Oversampling.
- Merging minority classes into larger groups  using unsupervised ML approaches.

<h2>Pipeline</h2><br>

 - [Gettind Data and EDA](https://nbviewer.org/github/vaztad/CyberSecurity/blob/main/Getting_Data%28EDA%29.ipynb)
 - [Preprocessing](https://nbviewer.org/github/vaztad/CyberSecurity/blob/main/preprocessing.ipynb)
 - [Clustering](https://nbviewer.org/github/vaztad/CyberSecurity/blob/main/Clustering.ipynb#h) 
 - [Smote and Modeling](https://nbviewer.org/github/vaztad/CyberSecurity/blob/main/SMOTE_ModelEvaluation.ipynb)
