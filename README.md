# File content
  train_data is the code that generates training dataset. The 0-200 dimensions of the dataset represent the number of molecules received by receiver RN, 
  while the 201 dimensions represent the signals sent by TN.
  
  git_informer and git_Transformer are the codes for training the Informer-based model and Transformer-based model on the training dataset, respectively.
  
  The data folder stores the test dataset in this paper, where the distance contains data from different microns and the noise contains data from different SNRs.
  
  The model folder contains the trained models.
# other
  The training dataset used in the code is in .CSV format, while in the data folder, .npy format is used due to data size limitations.
