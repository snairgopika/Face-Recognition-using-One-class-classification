# Face-Recognition-using-One-class-classification
Used one class method ( training sampes of only one class) to acheive face recognition . In the new digital/covid era face biometrics will be the most sold .


I personally used ORL, FEI database for evalustion.
For one class svm,gmm,if ,file structure should be:
Main Folder:
--------->person to be identified(training set)
--------->test set(usually a single class)
{ Here a lot of keras pretrained CNN was used for feature extraction ,includeing latest DEEPFACE }

For VAE , file structure should be :
Main Folder:
--------->Train(Normal Images)
--------->Test(Anomaly and Normal to test)


For One class Neural Networks,file structure should be :
Main folder:
----------->Train
             ----->Person to be identified 
----------->Test
             ----->Person to be identified 
             ----->Anomaly person 

{ For OC-NN , total accuracy is the average of  single accuracy of all person when considering each as single model training set }


Please Contact in case of any queries : snairgopika@cet.ac.in ( Responds within a week )
