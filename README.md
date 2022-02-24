# MEG_state_tracking
This is the source code for the theoretical methods used in the paper "" available at . 

The Python notebook file "MEG_State_Tracking.ipynb" provides an example for using the MEG method to track a time-varying qutrit, using MUB and generalized Pauli Measurements. The code can be adpated to work with higher-dimensional systems by modifying the "generate_MUB_3()" method to return the coefficients of the MUB for that dimension if they exist, and changing the "dim" variable to reflect the new dimensions. Everythign else will adpat automaically. For using the code with experimental data, the "step 2" part of the estimation iteration loops need to be replaced by a method that returns the experimental measurements instead of the simulated ones. 
