# AI-ML-in-Healthcare-Workshop

This codes were written as part of workshop organized at **Department of Electronics and Commmunication** , at **National Institute of Technology, Karnataka, India**, between April 09-29, 2022

Here only codes are given, being novice in AI/ML softwares there are plenty of bugs and proper documentation is not done. The datasets used are available in public domain on Kaggle. The work was done in collaboration with other participants and I want to acknowledge Mayank(see Kaggle under Mayank Rajpurohit for his reference codes), an excellent coder, for his help during the workshop.

## First Problem
In first problem a spreadsheet with patient info such as age(number), sex(M/F), Hypertension(Y/N), Diabetes	WFNS grade(1 to 4),	CT grade Fischer(0 to 4)	Radiological Vasospasm(Y/N),	Ischemic deficits(Y/N),	Outcome at Discharge(1 to 5 i.e. Demise to Healthy)	Outcome at 3 months(1 to 5 i.e. Demise to Healthy)
It required some data cleaning initially, with some values missing and converting to binary values for Y/N and normalizing the age and outcome.
It was later found out that the dataset had class imbalance and overcame with giving the class weightage. Logistic regression, KNN and SVM models were used. Here attached is how test data was generated and it was submitted for valuation of its performance.

## Second Problem
The second problem was detection of diabetic retinopathy. The eye images of 264×264 and 512×512 resolutions were given for left and right eye of different patients with labels from 0 to 4 were given. The code for association of given patients eye and its level was given. Train data=7082, validation data=1366, test data=1394 was given. Such datasets are available in public domain on Kaggle. Resnet 50 model was implemented and model was analysied. The performance was checked after some preprocessing on the images such as change in contrast, etc. 

## Third Problem
The third problem was brain tumour segmentation, again the dataset is available on Kaggle. The MRI images were given along with their marks, green for edema and red for tumour. The Unet model was implemented.
