# Support-Vector-Machine
https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones

Data & Problem Description
You will use a pre-processed dataset produced from real data originally collected by collegues from the University of Genova and the Polytechnic University of Catalonia, named "Activity Recognition Using Smart Phones Dataset". Details regarding the data collection methodology are provided in the following paper:

Anguita, D., Ghio, A., Oneto, L., Parra, X., & Reyes-Ortiz, J. L. A public domain dataset for human activity recognition using smartphones. 2013.

The experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, the reseachers captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The obtained dataset was randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

As SVMs cannot directly handle sequential data, the signals corresponding to each the different movements were pre-processed to obtain 563 features than correspond to:

1. Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
2. Triaxial Angular velocity from the gyroscope.
3. A 561-feature vector with time and frequency domain variables.

In addition, the dataset provide:
- The activity label.
- An identifier of the subject who carried out the experiment.
