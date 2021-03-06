# Removing Noise from Images Using Autoencoders

### This notebook consists of 5 parts:<br>
Autoencoder image compression using MINST dataset<br>
Autoencoder to denoise MINST dataset<br>
Convolutional autoencoder to denoise documents from Noisy office dataset<br>
Convolutional autoencoder to denoise MINST dataset<br>
Deep Convolutional autoencoder to denoise documents from Noisy office dataset<br>


### Technoogy Stack:<br>
Python<br>
Keras - TensorFlow<br>
matplotlib<br>
Numpy<br>


### Dataset:<br>
Here, 3 of the notebooks use MINST dataset and two notebooks use the Noisy office dataset provided by the UCI Machine Learning Repository at: https://archive.ics.uci.edu/ml/datasets/NoisyOffice <br>


### Notebooks:<br>
1. Autoencoder image compression using MINST dataset:<br>
This notebook creates 6 different autoencoders with hidden layer size varying from 1 to 32 hidden units and plots the outputs to compare the results.<br>
![5Autoencoder_results](/images/5autoencoders.png)
<br>


2. Autoencoder to denoise MINST dataset<br>
This notebook consists of a single autoencoder with 1 hidden layer of 16 hidden units and relu activation with adam optimizer.<br>
![Basic_MINST](/images/Basic_MINST.png)
<br>


3. Convolutional autoencoder to denoise documents from Noisy Office dataset<br>
This notebook consists of 3 Conv2D layers with relu activation for the first two layers (8 filters each) and sigmoid for the last layer (an output layer with 1 filter) with adam optimizer.<br>
![MINST_Autoencoder](/images/3.png)
<br>


4. Convolutional autoencoder to denoise MINST dataset<br>
This notebook consists of 5 2DConv layers (1st and 4th layer: 16 filters, 2nd and 3rd layer: 8 filters and an output layer with 1 filter) with relu activation except for the last one with sigmoid activation using adam optimizer.<br>
![Conv_MINST](/images/4.png)
<br>


5. Deep Convolutional autoencoder to denoise documents from Noisy office dataset<br>
This notebook consists of 7 2Dconv layers (1st and 6th layer: 32 filters, 2nd and 5th layer: 16 filters, 3rd and 4th layer: 8 filters and 1 output layer with 1 filter) with relu activation except for the last one with sigmoid activation using adam optimizer.<br>
![DeepConv](/images/5.png)
<br>
