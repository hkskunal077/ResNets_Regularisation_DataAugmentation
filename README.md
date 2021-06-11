# ResNets-Regularisation_DataAugmentation
#This project is created by following the similar project on Jovain.AI website
#Thanks to Jovian.AI for providing awesome content

Data Augmentation - We will pad each image with 4px, and then take a random crop of size 32 x 32 px, then flip image horizontally with a 50% probability of this happening. These are random transformations while loading images from the training datasets


Step 1 - Preparing the CIFAR10 Dataset
Step 2 - Use test set for validation, then normalise the data
Step 3 - Randomized Data Augmentation
Step 4 - We add Residual block to the CNN model, which adds the original input back to output feature map by passing input through one or more convolutional layers
Step 5 - ![image](https://user-images.githubusercontent.com/79495351/109665816-93348100-7b94-11eb-8f0c-7d23dee70134.png)
Step 6 - Training the model (Learning Rate Schedular will change the learning rate after every batch of learning)
Step 7 - We can also test with individual images
Step 8 - Adam optimiser is used for momentum and adaptive learning rates for faster training on train data
