### Module objectives:
 - Convert non-tabular data sources into arrays as neural network inputs
 - Construct neural networks, tune hyperparameters, and evaluate NN models.
 - Apply transfer learning to neural networks


# Predict drug MoA from cell images

Applied a convolutional neural network to images of several cell lines treated with different small molecule drugs. Tweaked hyperparameters, including depth, activation functions, and pre-trained models. Cox, et al. 2020 (https://www.nature.com/articles/s41598-020-69354-8). 

Figure 1: Accuracy of representative CNN model in predicting whether cells were treated GPCR agonist. Prediction accuracy is plotted for training and validation data as the number of epochs increase.    

![](best_loss.png)

Figure 2: Loss (or error) of representative CNN model for training and validation data as the number of epochs increase.   

### Tools

 - Pandas, seaborn, matplotlib
 - Omero and IDR to connect to IDR, retrieve images and metadata
- Keras/Tensorflow for neural network training
- Scikit-learn for model evaluation 
- Tensorboard to visualize CNN experimentation

### Databases
 - Image data repository (IDR)
 - Uniprot