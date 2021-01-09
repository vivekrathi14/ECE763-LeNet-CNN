# ECE763 LeNet ConvNet

**Subject** - ECE 763 Computer Vision <br>
**Project Name** - Babysitting the Convonlutional Neural Network (CNN) <br>
**Project Grade** - A+ <br>

**Architecture**
![LeNet](https://www.google.com/url?sa=i&url=https%3A%2F%2Fengmrk.com%2Flenet-5-a-classic-cnn-architecture%2F&psig=AOvVaw36hh73t2aLS_1UaB5PkzJg&ust=1610252063436000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMDqwMX-je4CFQAAAAAdAAAAABAP)

**Description** -
1. Implemented LeNet CNN architecture using PyTorch Library in Python for classification problem.
2. Performed Data Augmentation in form of horizontal, vertical flip, gamma correction (color jitter/brightness), resizing to images from 
CIFAR-10 dataset & FDDB Face dataset
3. Added and studied effects of weight initialization (Uniform Distribution), Batch Normalization in the LeNet architecture.
4. Added Regularization to penalize cost function, tuned the training with respect to learning rate and studied its effect on the validation accuracy.
5. Studied effect of ADAM & SGD optimizer on the CNN output.
6. Performed Course search followed by Fine search to get the best hyperparameter values for learning rate & regularization.

**Implementation**
LeNet_Pytorch.ipynb is extensive jupyter notebook with all comments and cell outputs to replicate & visualize the working effectively.
Google Colab GPU was used for training and monitoring the entire babysitting process.

**Dataset**
1. CIFAR-10 <br>
![cifar10](https://user-images.githubusercontent.com/25856691/104082906-0b6f6d80-5208-11eb-8d02-ae1d1083de41.png)

2. FDDF Face/Non Face <br>
![fnf](https://user-images.githubusercontent.com/25856691/104082944-6b661400-5208-11eb-9819-7eaf319d3d0e.png)
