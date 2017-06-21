## OSPABP: UAV flight data anomaly detection based on oversampling projection approximation basis pursuit
Aiming at the low accuracy problem of flight data online anomaly detection caused by flight mode switching of UAV,  an online anomaly detection method is proposed based on OverSampling Projection Approximation Basis Pursuit (OSPABP)

## Subspace learning problem
To be continued..

## Result
To be continued..

## Code Details
A standalone implementation of the algorithm is available in `OSPABP.m`.
Demos illustrating OSPABP for flightdata are provided in:
* `OSPABP_demo1.m`

The code in Matlab will be open soon.
We implement OSPABP with Matlab 2015b and perform all experiments on a laptop computer equipped with an Intel core i7-4710HQ@2.50-GHz CPU and 8 GB of memory.

## References
OSPABP was introduced in the journal paper:

Y. F. He, S. J. Wang, W. J. Wang,  "UAV anomaly detection based on oversampling projection approximation basis pursuit,"
Chinese Journal of Scientific instrument., vol. 37, no. 7, pp.1468-1476, Jul. 2016.

Abstract：Aiming at the low accuracy problem of flight data online anomaly detection caused by flight mode switching of UAV, an online anomaly detection method is proposed based on OverSampling Projection Approximation Basis Pursuit (OSPABP). Firstly, the dimension of flight data stream is eliminated with sliding window and Z-score transformation, and correlated flight data subset is extracted from sliding window. Secondly, the multivariate data of the subset in current time is oversampled to amplify the influence of abnormal data on data subspace. Through online estimation and pursuing match of the direction change of the projection approximation basis of the data subspace after oversampling, the anomaly of the real time input data of the subset is determined. Meanwhile, the method can also suppress the influence of flight mode switching on anomaly detection result. The experiments on the simulated flight data from Flight Gear and the real UAV flight data from University of Minnesota were conducted; the experiment results show that the proposed OSPABP method can reduce the false positive rate of anomaly detection significantly and improve the accuracy of anomaly detection effectively as its sensitivity to flight mode switching is low. In addition, the computational and storage complexity of the OSPABP method meets the requirement of flight data real-time processing.
