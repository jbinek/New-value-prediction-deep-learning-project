## *Next Value Prediction*

The project is focused on prediction of the next value for each of the three time series (X, Y,  Z). Every time series is recorded each 10 seconds.
Provided data consists of two *.csv* files, the first one contains training data and the second one contains data that will be used for testing of the created deep learning model. Both files contain information about accelerometer readings In the three axes (x, y, z).

The goal is to predict the next value of the sequence for each time series.
The task is an example of supervised machine learning according to the need of data conversion that involves rolling window technique.
Additionally, the task is also about checking how the rolling window parameters affect the result based on one of the provided time series (X, Y, Z).



### *About the project*
Healthware Group is a global health innovation and technology leader providing transformational advisory and technology services for commercial, medical, and R&D operations of life-sciences and digital health companies, combined with design and development of digital medicines and digital therapeutics products.

In the company's vision digital technology & innovation are the driving forces behind the transformation in  healthcare, leading to a world of increasingly relevant, human-sized, solutions to health challenges.

a) Subject of the project

  The main subject of the project is Parkinson disease. Parkinson disease, the second most common neurological disorder that causes significant disability, reduces the quality     of life and has no cure.

b) Information about the data

  The dataset contains information about 40 examined patients. They can be grouped as follows: 
  - 24 with Parkinson's Disease
  - 3 with advanced Parkinson's Disease
  - 13 without Parkinson's Disease

  Obtained data comes from wearable activity trackers. It provides information such as:
  - accelerometer readings In the three axes (x, y, z)
  - identification of a patient
  - heart rate
  - date and timestamp


The data is fully in a time series format. It contains information about the time of the measurements. Its characteristic is an uniform granularity - aggregation by mean at 1 second and resampling by mean at 10 seconds.
The data is also noisy and it contains missing values in a significant amount of records.

