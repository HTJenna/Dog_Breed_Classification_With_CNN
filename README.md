# Dog_Breed_Classification_With_CNN

Project Overview
This project focuses on using Convolutional Neural Networks (CNNs) to classify dog images and predict their breed. 
CNNs are machine learning models inspired by the way human neurons process information to recognize patterns and 
make decisions.They are particularly useful in tasks like image classification, facial recognition, and autonomous 
driving. In this project, the goal is to teach the CNN model to recognize dog breeds based on their characteristics, 
similar to how a human might learn to identify dog breeds.


Project Libraries
To run this project the following packages and libraries are required.

- CV2: Model used for face detection.
- glob: Used for file searching .
- keras: For the TensorFlow pre-trained models and image preprocessing.
- matplot: for creating plots
- pandas: Assists in data manipulation and model training.
- sklearn: Machine learning package used for training and enhancing the model.

Project Files
  1. Root Directory:
- bottleneck_features: The folder to store the bottleneck features is not uploaded due to their large size, but they can be downloaded
- dogImages: stores dog training, validation and testing images
- haarcascades: used face detection
- Lfw: has human images
- requirement: It contains YAML files for setting up the virtual environment
- saved_models: contains saved models from transfer learning CNNs
- Dog app: Notebook for manipulating data and creating CNNs

Project Intructions

1. Clone the repository and navigate to the downloaded folder:
  git clone https://github.com/udacity/dog-project.git
  cd dog-project

2. Download the dog dataset. Unzip the folder and place it in the repo at the following location:
  path/to/dog-project/dogImages

3. Download the human dataset. Unzip the folder and place it in the repo at this location:
  path/to/dog-project/lfw

4. Download the VGG-16 bottleneck features for the dog dataset and place it in the repo at:
     path/to/dog-project/bottleneck_features
5. Open the notebook:
     jupyter notebook dog_app.ipynb

Medium Post: [https://medium.com/p/f0a4e40f20ef/edit](https://medium.com/@hopolang.tsufu/dog-breed-classification-using-cnn-f0a4e40f20ef)
