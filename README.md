## CS-867-Assignment3: Image Classification using CNN
#### Pre-requisites
1. Dataset(Upload to the Google drive)
2. Google colab(Link gogle drive with colab)
3. Dataset link(https://www.kaggle.com/puneet6060/intel-image-classification/version/2)


#### Data Augmentation

Three types of Augmentation is performed to impore the effectiveness of the network in term of rooust classification
1. HorizontalFlip
2. Shear
3. Rescaling

Data augmentaion script is embded in training notebook.

#### Training

In this study, VGG16 is imployed to eveulate the effectiveness of classification interms of accuracy with adoptive learning rate on base and augmented dataset. 
The training code is availabe in Model file along with tranined weigths or you can download it form google drive (https://drive.google.com/file/d/1GF_EwaGnx2VQMC1iolQ3Xg1QAFxzH-na/view?usp=sharing)


#### Results



The experiment showed that vgg16 acheived 0.9055 accuracy on the provied dataset

![alt text](https://github.com/HasanAli55/CS-867-Assignment3/blob/main/Capture.PNG?raw=true)

