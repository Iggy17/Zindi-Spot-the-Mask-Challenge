# Zindi-Spot-the-Mask-Challenge
This is my solution to the Zindi Face Mask Challenge. 

The objective of the  challenge was to create an image classification machine learning model to accurately predict the likelihood that an image contains a person wearing a face mask, or not. The total dataset contained 1,800+ images of people either wearing masks or not.  

Instead of using a pre-trained model, I decided to build a custom convolutional neural network. This is a very basic conv net and I did not spend time tuning the network to obtain the best weights and estimation parameters. My initial thinking was to compared the output from a fine-tuned network to that of a basic pre-trained model. The model model had good both train and validation accuracy 92% and 98% respectively. 
