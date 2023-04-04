Chess Piece Image Classification with CNN
=========================================

This project uses convolutional neural networks (CNNs) to classify images of six different types of chess pieces: king, queen, rook, bishop, knight, and pawn. The project demonstrates the effectiveness of CNNs in image classification tasks and provides a useful resource for machine learning practitioners interested in this field.

Dataset size is small for the network to run on, therefore new image data is produced with augmentation techniques.  
Once the augmented images are ready, a deep neural network is created with Convolutional Layers and trained on this image set. 
Finally, the trained network is evaluated on test data. 

Dataset
-------
Image Set is received from [Kaggle Chess Piece Dataset](https://www.kaggle.com/anshulmehtakaggl/chess-pieces-detection-images-dataset)<br>
The dataset includes over 7,000 images of six different types of chess pieces. The images were collected from various sources and were preprocessed before being used in the project. The images were resized and reshaped to 64x64 pixels, and various image augmentation techniques were applied to increase the size of the training dataset.

Tools Used
-------
*  OpenCV, Scikit-Image, PIL for image augmentation
*  Pytorch for framework for Neural Network
*  Torchvision to manage image dataset

Deep Learning Network
-----------------------

A simple CNN 4 convolution layers and 2 linear layers were used in this project. The network was trained and evaluated using various performance metrics, including accuracy, precision, recall, and F1 score.

Results
-------

The best-performing model in this project was CNN with four convolutional layers, which achieved an overall F1-score of 75% on the test set. The project demonstrates the effectiveness of CNNs in image classification tasks and provides a useful resource for machine learning practitioners interested in this field.

License
-------

This project is licensed under the MIT License. See the LICENSE file for more information.
