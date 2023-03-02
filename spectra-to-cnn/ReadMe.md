# Spectra to CNN Notes
This folder contains the notes on how the mass spectra files are converted and embedded using the CNN before it is fed into the GNN.

## Data Preprocessing 
This notebook contains the code for preprocessing the mass spectra files before input into the CNN. Since MsEncoding uses
TensorFlow for its implementation I will convert the preprocessing into PyTorch. This code will be bare-bones implementation 
of the processing steps. 

## CNN Embedding
This notebook will contain the code for creating the CNN model and the resultant embeddings of the mass spectra files. 
I will also explore how T-Net and DeepNovo creates its embeddings as well. Since it is also covered in the paper.