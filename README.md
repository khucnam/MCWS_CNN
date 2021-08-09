# MCWS_CNN

This is a repo for a paper titled "Using multiple convolutional window scanning of convolutional neural network for an efficient prediction of ATP binding sites in transport proteins" which is under submission.


Guide to use the repo
- In the Data folder, we have provided the surveyd datasets in both fasta and pssm format.

- To convert from PSSM file to input features, we used the window size of 15. Please use your own script to generate the input feature from the PSSM files. (We have provided PSSM files for your convenience).

- To run the model with, i.e. with window_lengths of 4, 8, 12, and correponding number of windows of 100, 200, 100, use the following command
	python run.py --window_lengths 4 8 12 --num_windows 100 200 100 

- Change the corresponding variables in utils.py to change the hyper-parameters.

- The logs folder is automatically created.
	
