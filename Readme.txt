Building complex model on Pytorch that is able to classify CIPHAR10 dataset. 

What is CIPHAR-10 dataset?

The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes. The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. There are 6,000 images of each class.

In this project I have created a CNN model on Pytorch that can classify between 10 different classes.

The model I created is a Convolution Neural N/w LeNet model with 3 convolutional layers, one dropout layer and 2 fully connected layers. The accuracy this model yield is around 74% which is amazing considering that it is hand coded model and the dataset is complex. Some changes can be made in the hyper parameters to get better accuracy but it would be more benificial to use Transfer Learning to solve this issue.



requirements:-

pip install torch===1.5.0 torchvision===0.6.0 -f https://download.pytorch.org/whl/torch_stable.html