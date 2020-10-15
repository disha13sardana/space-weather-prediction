# Solar storm prediction using neural networks

In order to accurately predict the occurrence of solar storms, we exploit the
NARX neural networks to predict hourly Dst index in advance. Solar wind param-
eters such as interplanetary magnetic field (IMF), z component of magnetic field
Bz, solar wind velocity V, solar wind plasma number density n are chosen as input
parameters. The solar wind data and geomagnetic Dst index data are chosen over
the period of 2000-2015, covering 91 storms and solar cycle 23 & 24. Dst is pre-
dicted over different periods : 1 year, 5 years, 10 years and 16 years, covering the
onset, maxima and recovery phase of the solar storm cycle. For prediction, three
different training algorithms are used: Levenberg-Marquardt, Bayesian Regulariza-
tion and Scaled Conjugate Gradient. Data is randomly divided into 3 parts for
each algorithm, 70% as training set, 15% as validation set and 15% as test set. It is
found that storms of different strengths are correctly predicted and the correlation
between the predicted Dst index and the observed Dst index (2000-2016) is found
out to be 0.98. A low MSE in the range of [7,12] and a high Regression R-value of
about 0.98 has been acheived.
