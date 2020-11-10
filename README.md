# Classifying Images of Common Clothing
### Project description
This project is to train 3 models including a three-hidden layer neural network, a CNN, a **state of the art** Wide Residual Network with 28 layers and widening factor of 10 to classify images from the MNIST Fashion Data Set. This data set contains common items of clothing across 20 different categories. It contains around 60,000 training images, and 10,000 test images. The target goal of this project is a category, however, the input consists only of 26x26 images. 

### Dataset
https://github.com/zalandoresearch/fashion-mnist

### Measurement
The best accuracy is 95.8% using WRN-28-10

### Required packages
- ipywidgets: conda install -c conda-forge ipywidgets (this package used by torch.hub to show the progress bar when we download dataset )
Note: you may close the notebook and reopen again 
- pytorch: conda install pytorch torchvision -c pytorch
- matplotlib.pyplot
- numpy
- pandas
- seaborn
- sklearn
- PIL
