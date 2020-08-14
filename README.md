# KalmanFilter
Several different tests of creating a Kalman Filter in Python
Extended Kalman Filter and Unscented Kalman Filter do not work properly
The rest of the codes should work but have not been extensively tested
If you have any questions about any of these codes please email me at joaquinmatticoli@gmail.com and I will try to explain more
## Description of Codes:
* OldCode: Older version of codes I've made. There shouldn't be much that's useful in here.
* 1D_EKF_EXCLAIM: Currently does not work properly. This is my attempt at the Extended Kalman Filter code.
* 1D_KF_EXCLAIM: Univariate Kalman filter for one sensor. Set up for a poistion sensor but can be easily modified for a velocity sensor
* 1D_KF_EXCLAIM_2: Interpolating Kalman filter that makes predictions in between the sensor measurements. The prediction step and the data measurements have different rates.
* 1D_KF_EXCLAIM_2_DifferentRates: Hybrid Kalman filter that handles two sensors with different data rates as well as interpolating between sensor measurements.
* 1D_KF_EXCLAIM_DifferentRates: Different Data Rates Kalman Filter that can handle two sensors that output data at different rates.
* 1D_Multivariate_KF_EXCLAIM: Multivariate Kalman filter using two sensors. One position and one velocity sensor.
* 1D_UKF_EXCLAIM:Currently does not work properly. This is my attempt at the Unscented Kalman Filter code.
* KalmanFilterDocumentation: Nice little code that lets you see the documentation for the three different Kalman filter functions I use (KalmanFilter, ExtendedKalmanFilter, and UnscentedKalmanFilter).
