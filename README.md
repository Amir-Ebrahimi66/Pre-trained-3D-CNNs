# Pre-trained-3D-ResNet-18
Pre-trained 3D ResNet-18

The model is available in Mathwork's file exchange. 
To transfer the learnable parameters from pre-trained 2D ResNet-18 (ImageNet) to 3D one, we duplicated 2D filters (copying them repeatedly) through the third dimension. This is possible since a video or a 3D image can be converted into a sequence of image slices. In the training process, we expect that the 3D ResNet-18 learns patterns in each frame. This model has 34 million learnable parameters.

simply, call "resnet18TL3Dfunction()" function.

Please cite as:
Ebrahimi, Amir, et al. “Introducing Transfer Leaming to 3D ResNet-18 for Alzheimer’s Disease Detection on MRI Images.” 2020 35th International Conference on Image and Vision Computing New Zealand (IVCNZ), IEEE, 2020, doi:10.1109/ivcnz51579.2020.9290616.

More details in:
[![View Pre-trained 3D ResNet-18 on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://au.mathworks.com/matlabcentral/fileexchange/82585-pre-trained-3d-resnet-18)
