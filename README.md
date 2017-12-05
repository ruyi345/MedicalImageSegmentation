# Medical Image Segmentation

This repository contains part of the work we conduct at LIVIA that can be made publicly available. 

This is the current content of this repository:

## LiviaNET. 3D fully Convolutional Neural Network for semantic image segmentation [Link](https://github.com/LIVIAETS/MedicalImageSegmentation/tree/master/LiviaNET)

This repository contains the code of LiviaNET, a 3D fully convolutional neural network that was employed in our work: [3D fully convolutional networks for subcortical segmentation in MRI: A large-scale study](http://www.sciencedirect.com/science/article/pii/S1053811917303324) Neuroimage, April,17th 2017.

<br>
<img src="https://github.com/josedolz/LiviaNET/blob/master/Images/NeuroRes2.jpg" />
<br>

## SemiDenseNet. Semi-dense connectivity to segment infant brain tissue in multi-modal images [Link](https://github.com/LIVIAETS/MedicalImageSegmentation/tree/master/SemiDenseNet)
This repository contains the code of the network that we employed in the iSEG Grand MICCAI Challenge 2017, infant brain segmentation. This network extends out previous work in 3D fully convolutional neural network that was employed in our work: [3D fully convolutional networks for subcortical segmentation in MRI: A large-scale study](http://www.sciencedirect.com/science/article/pii/S1053811917303324), which can be found here : (https://github.com/josedolz/LiviaNET/).

<br>
<img src="https://github.com/josedolz/SemiDenseNet/blob/master/Images/brainModalities.png" />
<br>

IMPORTANT: This Net is not the one that best performed in the iSEG Challenge, but the one with an individual path per modality and a late fusion stage to merge learned features (See figure). In case you want to adapt this net to the best performing net, you should remove one of the paths and merge T1 and T2 modalities at the input of the network. 

<br>
<img src="https://github.com/josedolz/SemiDenseNet/blob/master/Images/SemiDenseNET.png" />
<br>
