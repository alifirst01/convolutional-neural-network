# convulutional-neural-network
Deep learning CNN models comparisons using tensorFlow on MNIST dataset

### Datasets
Training set consists of 200000. Each image is of size 28x28  
Validation set consists of 10000 images   
Test set consists of 18724 images  

### Model
Four different models of CNN are used. Each consisting of different set of layers and learning rate value  
- Model1 consists of 1 convolutional layer and 2 fully connected layers. The learning rate is E-03
- Model2 consists of 2 convolutional layer and 2 fully connected layers. The learning rate is E-03
- Model3 consists of 1 convolutional layer and 2 fully connected layers. The learning rate is E-04
- Model4 consists of 2 convolutional layer and 2 fully connected layers. The learning rate is E-04

The following graph shows how layers are connected in model4  
<img src="/CNN%20Model/png.png" width = "600px" hieght="400px">  


### Models Performance Comparisons
The time taken and the accuracy acheived by each model are used to compare the performaces on test set of images. 
Model1 achieves an accuracy of 98% in relative time 10m 44s  
Model2 achieves an accuracy of 100% in relative time 17m 24s  
Model3 achieves an accuracy of 98% in relative time 11m 4s  
Model4 achieves an accuracy of 93% in relative time 9m 29s  

The following graph shows the time taken against the accuracy for each model.  
<img src="/CNN%20Model/graphs.png" width = "600px" hieght="400px">  
<img src="/CNN%20Model/legend.png" width = "500px" hieght="400px">

