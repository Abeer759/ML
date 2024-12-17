# ML
ML
Project Summary
This project develops a Convolutional Neural Network (CNN) to classify images of cats and dogs. The process involves training the model on 4,000 images of cats and 4,000 images of dogs. The model's performance is tested on a separate evaluation dataset containing 1,000 images of each category. Once trained, the CNN can classify new images stored in the single_prediction folder as either "cat" or "dog."

Tools and Technologies
The project uses TensorFlow and Keras. TensorFlow provides the computational power for training, while Keras simplifies the design and implementation of the neural network.

Steps Involved
Organize the dataset into training and test directories.
Preprocess the images by scaling pixel values and applying data augmentation.
Build the CNN using convolutional, pooling, and fully connected layers.
Train the model and monitor its accuracy and loss.
Test the model on the evaluation dataset.
Use the trained model to predict new images.
Folder Structure
training_dataset/: Contains training images of cats and dogs.
test_dataset/: Contains test images of cats and dogs.
single_prediction/: Holds new images for classification.
Getting Started
Install TensorFlow:
bash
Copy code
pip install tensorflow
Run the training script to train and test the model.
Place new images in the single_prediction folder and classify them.
Important Notes
Ensure the dataset is organized and images are in JPEG/PNG format.
A GPU is recommended for faster training.

# Medium article URL 
https://medium.com/@abeershuvo/convolutional-neural-network-85ce31a4bc35

# Drive URL
https://drive.google.com/drive/folders/1v8m1tpW1FR0NAg_UojKZl9ydj2VWnkHk?usp=drive_link
