##101 Food Classification using EfficientNet B0
This is a project that classifies 101 different food types using transfer learning with EfficientNet B0. The dataset used is provided by TensorFlow.

#Dataset
The dataset used is the 101 Food Dataset. It contains 101 different food types with 101,000 images in total. The images are split into a training set of 75,750 images and a validation set of 25,250 images.

#Model
The model used for this project is EfficientNet B0, which is a pre-trained model that has been shown to achieve state-of-the-art performance on a variety of image classification tasks. Transfer learning was used to fine-tune the model on the 101 Food Dataset.

#Training
The model was trained on a single NVIDIA Tesla V100 GPU with a batch size of 32 for 15 epochs. The training process took approximately 25 minutes to complete.

#Results
The model achieved an accuracy of 85% on the validation set after 15 epochs of training. The confusion matrix shows that the model was able to correctly classify most of the food types, but there were some classes where the model struggled to distinguish between similar types of food.
