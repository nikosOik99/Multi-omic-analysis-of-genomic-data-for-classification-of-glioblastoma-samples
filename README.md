# Multi-omic-analysis-of-genomic-data-for-classification-of-glioblastoma-samples
This repository represents my Thesis

<h1> Introduction </h1>
 Clustering of individual omic datasets has proven invaluable for biological and medical research. Decreasing costs and the development of next-generation sequencing (NGS) methods now have the measurement of multi-omic data. Clustering multiple omics data has the potential to reveal further systems-level insights, but raises computational and biological challenges. <br>
 This thesis examines algorithms for clustering multiple omic data as well as methodologies from the area of machine learning for joint clustering of multiple data types. The first part of this study deals with the description of glioblastoma as a type of cancer and includes concepts from the field of biology which are considered important. Then, a reference is made to the field of machine learning by analyzing categories of algorithms such as supervised learning, unsupervised learning, reinforcement learning and applications of machine learning in today's era.<br>
 In addition to the aforementioned concepts, the results of the algorithms and techniques used are presented, such as the use of the SMOTE algorithm and the final conclusions obtained.<br>
 More specifically, SVM and Decision Tree machine learning algorithms were used on omic data, Gene expression, DNA Methylation, miRNA and clinical data extracted from the TCGA genomic database and related to patients with glioblastoma. The necessary pre-processing of the data was done and the patients were categorized based on their status (alive or deceased). Note that the SMOTE oversampling algorithm was used as the data was unbalanced. The models were applied to each omic set separately and to the unified representation resulting from the use of the strategy for very small data, early integration. It turned out that this strategy gave better results compared to analyzing each omic level separately, resulting in a decision tree with features from all omic levels. In particular, the SVM algorithm presented an accuracy of 88.23% and the Decision Tree 72.54%. Finally, this strategy was also used in other cancer data to show its effectiveness in other data beyond glioblastoma.<br>

<h2>Includes</h2>
-Glioblastoma Sample Analysis Jubyter notebook <br>
-Another Cancer Types Jubyter notebook<br>
-Report (in Greek Language)<br>
-PPTX Presentation<br>

<h2>Extra info</h2>
Programming Language used: Python
