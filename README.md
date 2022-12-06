# aslrecognitionrepo
This repository contains all the source code used in the paper "Dynamic ASL Recognition using Deep Learning " by Menchavez et al., 2022.


The contents of the YoutubeDataset10 can be accessed through this link:
https://drive.google.com/drive/folders/13jFErtqzMozU__DJlioBLWK2X8DzKwYw?usp=share_link

The contents of the CustomDataset10 can be accessed through this link:
https://drive.google.com/drive/folders/1g0ay5C0M2Yi2GpxCe-Kbz8al4Q5z8ZtJ?usp=share_link


Folders:

Models folder contains all the aggregrated code used in the implementation of American Sign Language recognition using transfer learning. It was implemented using Tensorflow Keras in python.

CustomDataset10_csv_files folder contains all the dataframe for all kfold combinations of the CustomDataset10 dataset in .csv format.

YoutubeDataset10_csv_files folder contains all the dataframe for all kfold combinations of the YoutubeDataset10 dataset in .csv format.


Dependencies:

opencv-python 4.6.0.66

jupyterlab 3.3.2

python 3.9.12

keras 2.6.0

numpy 1.23.4

tensorflow 2.6.0

tensorflow-gpu 2.6.0

matplotlib 3.6.2

pandas 1.5.2

Supplement code:

Original implementation of I3D by deepmind https://github.com/deepmind/kinetics-i3d

Keras video classification framework https://github.com/netonion/keras-video-classification

