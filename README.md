# Chess_Piece_Image_Classification_With_CNN

Project for detection of the chess piece type from images. 
Image Set is received from Kaggle Chess Piece Dataset --> https://www.kaggle.com/anshulmehtakaggl/chess-pieces-detection-images-dataset

Image classes are 'knight', 'bishop', 'queen', 'rook' and 'pawn'.

Dataset size is small for the network to run on, therefore first step is to create new image data with augmentation. 
Once the augmented images are ready, a deep neural network is created with Convolutional Layers and trained on this image set. 
Finally, the trained network is evaluated on test data. 

### Tools Used
*  OpenCV, Scikit-Image, PIL for image augmentation
*  Pytorch for framework for Neural Network
*  Torchvision to manage image dataset
