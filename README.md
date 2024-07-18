NAME:SANDHYA S
COMPANY:CODTECH IT SOLUTIONS
ID:CT4DS3410
DURATION:JULY TO AUGUST
DOMAIN:DATA SCIENCE





Load and Preprocess Data:
CIFAR-10 dataset is loaded and normalized.

Data Augmentation:
Augmentation techniques like rotation, width/height shift, and horizontal flip are applied.

CNN Architecture:
A VGG16 pretrained model is used as the base model. It is then extended with additional layers for our specific task.

Compile and Train:
The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss.
The model is trained using the augmented data.
