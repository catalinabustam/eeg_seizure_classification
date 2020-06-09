# EEG_seizure_classification

From Kaggle UPenn and Mayo Clinic's Seizure Detection Challenge

https://www.kaggle.com/c/seizure-detection/overview



#### Data set description: 

* 8 Patients

* 4 Dogs

For Each subject 
  * Different numbers of channels 
  * Different sampling rates from 500 Hz to 5,000 Hz
  * Different number of samples


#### Each data set consists of

  * 1-second EEG clips labeled "Ictal" for seizure data segments, or "Interictal" for non-seizure data segments

  * matrix of EEG sample values arranged  as [n_channel, n_time_points]
  
Results

#### Comparision with kaggle competition leaderBoard:

The winner got a value for mean AUC of 0.96287
He used:
* Combination of FFT with time and frequency correlation, taking both correlation coefficients and eigenvalues
* RandomForestClassifier

https://github.com/MichaelHills/seizure-detection
  
 
