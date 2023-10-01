# Face-Recognition-PyTorch
Project made by Harshvardhan Vatsa
Face recognition using PyTorch,CNN and OpenCV
This Project requires the following dependencies
1)PyTorch Machine and Deep Learning Framework
2)Facenet_pytorch- Package that identifies Faces
3)PIL=Python Imaging Library
4)Open CV2 - Open Computer Vision Library
5)Time and OS packages(NOT COMPULSORY BUT Reccomended)

Instructions:
->In the Photos Folder, make a folder of your name and add photos of yourself
->Run The Program and a window called "Face Detection" will pop up, you can view a frame with your name and probablity on it
-> press escape button to terminate the window
-> press space bar to add the picture in your library for more  further accurate results 

Additional Notes:
This project uses prelearnt dataset called  vggface2 which contains around 3.31 million images divided into 9131 classes,each of resolution below 32 pixels.
PyTorch uses MTCNN(Multi-task Cascaded Convolutional Networks) to learn the faces in your folder and detect with the help of the vggface2 dataset.
