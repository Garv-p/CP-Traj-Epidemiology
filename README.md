In order to run this you must first download the code found in the CP-Traj paper here (https://arxiv.org/pdf/2508.13362) 

The notebooks goes through the process described in the report for Trajectory-Level Conformal Prediction for Epidemiological Forecasting under Scenario Shifts. We begin by instantiating our models, creating our dataset through our mechanistic SIR, and training our surrogate model. AFter this we conduct CP-Traj without calibration and then with calibration. Included functions are plotting functions, model testing function, and a custom SIR transformer Data Generator. 
