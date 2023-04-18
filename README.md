# Project_4
## A Comparison of Machine Learning Methods on a Medical Dataset: Predicting Diabetes 


![machine-learning_2](https://user-images.githubusercontent.com/115951034/231836799-cdd4e8bc-2e89-4d00-bb46-93ddf858c6d2.jpg)



## <a id="Introduction-header"></a><ins>Introduction</ins>



The aim of the project was to utilise a number of Machine Learning techniques on a medical dataset to determine which techniques are most successful in terms of model accuracy. The dataset chosen was that of a survey of Native American Prima Indian females. 


##  <a id="ProjectManagement-header"></a><ins>Project and Resource Management</ins>


Recognising the timesclae and finite resources at our disposal, a project timing plan was produced to ensure the team remained focussed and co-ordinated to meet the requirements of the project and the presentation date. 
(click on image)

![image](https://user-images.githubusercontent.com/113118793/232701397-f998eb11-c7c4-4643-865e-ba52314d6c84.png)


## <a id="Methodology-header"></a><ins>Methodology</ins>


* Interrogate and understand the dataset
* Show visualisations to highlight understanding of the characteristics of the dataset
* Establish a "baseline method" using logistic regression
* Use other Machine Learning techniques to compare accuracy for this data set.
* Record results of individual methods and then compare all techniques investigated.
* Summarise and conclude


## <a id="Challenges"></a><ins>Challenges</ins>

In addition to the resource and timing issues mentioned above, the biggest challenge the team encountered was understanding the data as received. The decision was made to maximise our understanding of the nature of the data before proceeding with the machine learning techniques to be applied. In this way it was felt that we would provide a more validated result set with associated conclusions.

The data itself contained a significant numbers of zeros that were possible present in place of no readings. However the challenge was to determine if there were some values that were indeed numerically equal to zero. In order to mitigate the risk it was decided to incorporate the two conditions in our analysis of the data and to evaluate modelling performance on two datasets, containing zeroes and with zeroes removed. 

 

## <a id="Results-header"></a><ins>Results</ins>


![image](https://user-images.githubusercontent.com/113118793/232717267-ee2f6b70-7c9d-41bd-ab60-484910703dcd.png)


## <a id="Database-Management"></a><ins>Database Management</ins>

The data input was in the form of a csv file. An sql file was created from the data using python code in a jupyter notebook using sqlite. The files are located in this repositry in a directory called SQL management. This will enable other researchers the option of using an SQL database to research the data.


## <a id="Conclusion-header"></a><ins>Conclusion</ins>


The examination of the two datasets (with and without zero’s) has shown that in nearly all cases removal of the zero’s gave a more accurate model, therefore indicating that it is likely they are rogue zeros.

The above highlights importance of interrogating and understanding the data before analysis.

The tuning techniques (Keras and TPOT) give improved accuracy over manually selected values.

The random forest gave the best model accuracy for the manually tested machine learning models on this dataset.

TPOT also found that the Random Forest gave the best performance on this dataset and improved the accuracy by optimising the factor settings. 

Recall is very important as we want to achieve as accurate results as possible, and the way in doing so is trying to bring the FN number down as low as possible.




