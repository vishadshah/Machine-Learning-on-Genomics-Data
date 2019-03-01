# Machine-Learning-on-Genomics-Data
EE542 - Internet and Cloud Computing 
Laboratory 10
Machine Learning on Genomics Data - Team Project

Pre-processed National Cancer Institute data files of all disease type to generate miRNA file having 43 labels of different cancers and visualized features after feature selection with t-SNE and PCA method. 
Implemented Logistic Regression to find evaluation metrics and ROC curve for model using python on AWS EC2. 
Genomics Common Data 
1)	Run the check.py file. This file should be in the same folder as where the miRNA.csv is present. All files are compatible with Python 3 and above versions eg : $python3 check.py 
2)	Run the parse_file_case_id.py script to get the unique file id for corresponding case ids. After this get the JSON file from the genomimcs data repository. 
3)	Run the request_meta.py to get the meta data for all the cases 
4)	Run the gen_miRNA_matrix.py to get the miRNA matrix and labels for all the data 
5)	Run the test.py file for running the machine learning algorithm which is Linear Regression. The precision , accuracy , F1-score and sensitivity values can be seen in the graph. The scatterplots are also plotted for showing the variation per principal component

Team Members: 1 - Vishad Shah 2 - Pavan Athreya 3 - Ekta Trivedi

Youtube Video Link: https://www.youtube.com/watch?v=4maCzzg9zDw&t=1s


