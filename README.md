# QOSF mentorship screening task 3
Aim: To create a Quantum Circuit Simulator. 

Features of the simulator: Support any single qubit Quantum gate  
                                          Support for controlling any single qubit gate with arbitrary control and target qubits  
                                          Support parametric gates and variational circuits
                                          
* The simulator supports the following single qubit gates: H, X, Y, S, S†, Z, T, I, U3  
* Controlled gate (CU) for any of the gates can be created by simply specifying the 'target' as a list containing [source, target]. The gate U should be one of the single qubit gates mentioned above and should be passed as the 'gate' parameter.  
* Any arbitrary values can be given for the parameters Theta, Phi and Lambda for the U3 gate. 

We use the Simulator to implement the Deutsch-Jozsa Algorithm and also to Find the minimum Eigenvalue using VQE (Refer my submission for QOSF task 4 of the previous cohort [here](https://github.com/anshsingal/qosf_task_4/blob/master/VQE_final.ipynb))

I used the libraries Numpy, math, cmath and scipy
