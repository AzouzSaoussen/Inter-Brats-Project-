# Inter-Brats-Project-
 Image Segmentation ·Python.  Django · Reinforcement Learning · Convolutional Neural Networks (CNN) · Tranformers. Attention Mechanisms · Brain network Analysis · Python
## Set up the preprocessing environnement
### Creating the preprocess-container
1. pull the preprocess-image: lastest from docker hub
   > docker pull preprocess-image:latest
2. create the container
   > docker run -it -e DISPLAY=$DISPLAYtmp/.X11-unix:/tmp/.X11-unix --name preprocess-container preprocess-image
### Run the preprocessing pipeline
