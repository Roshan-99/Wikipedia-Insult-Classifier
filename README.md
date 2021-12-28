# Wikipedia-Insult-Classifier
## Project for the Foundation of AI course.

#### Github faces issues sometimes to display ipynb files (jupyter notebook files). You can clone and view it locally without any issues.

#### If you wish to view it in the browser, click this link to view it https://nbviewer.org/github/Roshan-99/Wikipedia-Insult-Classifier/tree/main/ 
#### or please paste the url of repository(https://github.com/Roshan-99/Wikipedia-Insult-Classifier) in https://nbviewer.org/. 

---------------------------------------------------------------------------------------------------------------------------------------
#### Obtained an accuracy of 87% (F1 Macro average score) and an improvement of 9% over baseline code (78% - F1 Macro Average score). 
>The Best model is LinearSVC with unigrams for tfidf transformer and classifier parameters are C:1, class_weight:{False:1,True:2}, loss:hinge.


#### Files used:

 ##### SuryaRoshan_Mugada_Project.ipynb
>This file contains the best model including the data analysis perfomed and hyperparameter tuning performed. 

##### WikipediaTalkDataGettingStartedV3.ipynb
>This file contains the experimentation of various models before choosing the best model (which was then used in SuryaRoshan_Mugada_Project.ipynb).

##### attack_annotations.tsv
>This is the data (containing the comment,ns,year,etc without the class labels

##### attack_annotations_comments.tsv
> contains the annotation for each comment given by the annotator, this is combined with attack_annotations to create the data

##### raw_comments.csv
> contains the comments in raw format prior to any preprocessing

##### comments.csv
> comments after preprocessing



