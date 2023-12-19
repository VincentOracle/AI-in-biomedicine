This project contains the implementation of a deep neural network for automatic collection of new traits based on genomic data. The model is implemented using Python 3 and PyTorch library.

Requirements:

Python 3
PyTorch library (version 1.8.1 or higher)
numpy library
pandas library
matplotlib library
Dataset:
	The dataset used for this project is the genomic data dataset and associated traits, such as milk production, 
feed efficiency, and disease resistance. The dataset can be downloaded from [insert dataset source link here]. 
The dataset contains genomic data and associated traits for a set of animals.

Code Files:

	data_preprocessing.py: This file contains the code for preprocessing the dataset. It loads the dataset, 
	converts the genomic data to numerical features, and splits the dataset into training and testing sets.
	model.py: This file contains the code for the deep neural network model architecture.
	train.py: This file contains the code for training the deep neural network model on the training set.
	evaluate.py: This file contains the code for evaluating the performance of the trained model on the testing set.
How to Run:

1) Download and extract the dataset to a folder.
2) Clone the repository to your local machine.
3) Open a terminal/command prompt and navigate to the project folder.
4) Run the data preprocessing script using the following command:
       python data_preprocessing.py --data_path <path to dataset folder>   
       This will preprocess the dataset and save the preprocessed data to a file named 'preprocessed_data.npy' in the project folder
5) Run the training script using the following command:    
    python train.py
    This will train the deep neural network model on the preprocessed training data and save the trained model weights to a file named 'model.pth' in the project folder.
6) Run the evaluation script using the following command:
    python evaluate.py
  
This will load the trained model weights from 'model.pth' file, evaluate the model performance on the preprocessed testing data, and display the evaluation metrics.
Note: You can also modify the hyperparameters of the model and training process by changing the values of the constants in the 'model.py' and 'train.py' files.
      

  