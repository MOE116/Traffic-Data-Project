# Motor-Vehicle Accident Severity 
This project focused on the severity of motor vehicle accidents and the factors that significantly affect them.
A large variety of factors are at play when driving on public roads. Which factors(environmental or driver-specific) most heavily contribute to severity of accidents on the road?

The goal was to build a model that can classify and predict accident causes, help informing policy decisions and improve overall traffic safety.

The hypothesis to test was; "Driver related factors(Age, over speeding status, Traveling speed) have a significant effect on the severity level of an accident"

Motor vehicle accidents data in the USA was sourced from NHTSA(National HighwayTraffic safety Administration) for the year 2018.
The "Data set" folder  contains the following files:
acc_18.csv
pers_18.csv
veh_18.csv
merged_accident_data_18.csv
filtered_accident_data_1.csv
filtered_accident_data_updated.csv

The 3 data sets were merged to get "merged_accident_data_18.csv"
The data set was further trimmed down in column size after performing some analysis towards attribute selection.
The manual folder contains the NHTSA user manual for information on the column names, description and the data type.

A classification model was used in this project:
Random forest

The Max_Sev attribute was eventually binned in an attempt to reduce the skewness of the data set
An 80/20 split was used for training data and testing data.
The trainng data was oversampled and undersampled, both versions were used to train the model separately.

Conclusions:
The RandomForest Classifer did not perform as well as expected, low accuracy, precision and F1 scores.

The Model can benefit from real time data if intended to be used for crash prediction.

