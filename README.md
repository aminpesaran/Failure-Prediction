# Failure-Prediction
The main goal of the project is to improve the maintenance planning  by applying data analysis and machine learning algorithms on the available data from sensors in a jet engine.

Observing engine's health and condition through sensors and data is assumed to facilitate this type of maintenance by predicting Time-To-Failure (TTF).

## Data:
Jet engine text files contain engine run-to-failure data, included operational settings and 21 measurements from sensors.

- Performance_train Data: The jet engine run-to-failure data.
- Performance_test Data: The aircraft engine operating data without failure events recorded. 
- Performance_truth Data: The true remaining cycles for each engine in the testing data.
## Approach:
By evaluating the jet engine’s sensor values, the machine learning algorithm can learn the relationship between the sensor values in order to predict failures in the future.
- Regression Modeling is applied to predict the remaining cycles before engine failure.
- Binary Classification algorithms are applied in order to predict, if engine will fail after specific number of cycles.
