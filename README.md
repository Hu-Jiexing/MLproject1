# MLproject1

Can start from my template and make changes or download to work on it  
Use the cleaneddata.csv file in this repository to run the code  
Create new branch if you want to commit your changes

Currently includes:

Initial decision tree (DT)  
DT after Feature Selection (RFE)  
DT after GridSearch  
DT after RandomSearch

Linear Support Vector Classifier (SVC)  
Polynomial SVC  
RBF SVC  
Each SVC model (linear, poly, RBF) after RFE  
Currently unsure about GridSearch and RandomizedSearch for SVC models since both take a long time  
If able to run, will put best performing SVC model with parameters from GridSearch and RandomizedSearch

Random Forest (RF)  
RF after RFE  
RF after GridSearch (Didn't let it run to completion yet)  
RF after RandomSearch




New proposed structure:


Initial decision tree (DT)  
Tuned DT (GridSearch and/or RandomSearch)  
DT after Feature Selection (RFE)  
Tuned DT (RFE)

Best initial SVC model (either linear, poly, rbf)  
Tuned SVC model (probably using GridSearch)  
SVC model (after Feature Selection + GridSearch)


Initial Random Forest (RF)  
Tuned RF (GridSearch and/or RandomSearch)  
RF after Feature Selection (RFE)  
Tuned RF (RFE)
