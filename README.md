# Comparison of UKF and EKF for an example system

Python notebook written to compare the EKF and the UKF in an example simulated system. 

True trajectory is loaded from *.mat* file which includes nonlinear turn motions. The measurements are simulated from this true trajectory for Radar sensor.

In the filters the state motion equations are assummed to be constant velocity(CV) model which is not the perfect model for the true trajectory obviously. The measurement equations are nonlinear becaouse of the Radar sensor's polar coordinate measurements. 

The UKF and the EKF are utilzed at the same conditons and their outputs are compared. 

