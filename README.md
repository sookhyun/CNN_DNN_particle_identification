# CNN+DNN particle identification

This repository contains a jupyter-notebook that explores a hybrid method that combines Convolutional Neural Network and Deep Neural Network to enhance the particle-identification capabilities at a high-energy collider experiment, sPHENIX. An initial study was performed within the Undergraduate Research Opportunities Program (UROP). 

The initial study focused on the electromagnetic (EM) particle identification using energy signatures on an EM calorimeter. In particular, of main interest was the behavior of a pair of photons decayed from a neutral pion, where the angle between the decay photons decreases with the momentum and the energy clusters of the pair eventually become completely merged. 

Data were generated using standard sPHENIX detector simulation implemented in the coresoftware repository. A conventional approach to EM particle identification is based on fitting an expected EM shower profile to measured energy clusters. The probability of the fit serves as a cut, below which is regarded as unlikely to be an EM shower.  
