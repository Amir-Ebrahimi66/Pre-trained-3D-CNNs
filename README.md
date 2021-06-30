# Pre-trained 3D CNNs

The model is available in Mathwork's file exchange. It was initially used for Alzheimer's disease detection.

To transfer the learnable parameters from pre-trained 2D CNN (ImageNet) to 3D one, we duplicated 2D filters (copying them repeatedly) through the third dimension. This is possible since a video or a 3D image can be converted into a sequence of image slices. In the training process, we expect that the 3D CNN learns patterns in each frame. This model has 34 million learnable parameters.

Available models: ResNet-18, ResNet-50, ResNet-101, LeNet-5

simply, call "resnet18TL3Dfunction()" function or any other function.

## Please cite as:

Ebrahimi, Amir, et al. “Introducing Transfer Leaming to 3D ResNet-18 for Alzheimer’s Disease Detection on MRI Images.” 2020 35th International Conference on Image and Vision Computing New Zealand (IVCNZ), IEEE, 2020, doi:10.1109/ivcnz51579.2020.9290616.

Ebrahimi, Amir, et al. “Convolutional Neural Networks for Alzheimer’s Disease Detection on MRI Images.” Journal of Medical Imaging, vol. 8, no. 02, SPIE-Intl Soc Optical Eng, Apr. 2021, doi:10.1117/1.jmi.8.2.024503.

## Files available in:

### ResNet-18: [![View Pre-trained 3D ResNet-18 on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://au.mathworks.com/matlabcentral/fileexchange/82585-pre-trained-3d-resnet-18)

### ResNet-50: [![View Pre-trained 3D ResNet-50 on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://au.mathworks.com/matlabcentral/fileexchange/87427-pre-trained-3d-resnet-50)

### ResNet-101: [![View Pre-trained 3D ResNet-101 on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://au.mathworks.com/matlabcentral/fileexchange/87432-pre-trained-3d-resnet-101)

### LeNet-5: [![View Pre-trained 3D LeNet-5 on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://au.mathworks.com/matlabcentral/fileexchange/87442-pre-trained-3d-lenet-5)

### GUI for Alzheimer's disease detection: [![View GUI on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://au.mathworks.com/matlabcentral/fileexchange/88912-alzheimer-s-disease-detection-using-3d-resnet-18-on-mri)

![image](https://user-images.githubusercontent.com/57122652/123904577-0f5c9b00-d9b4-11eb-9058-1d64c8939c56.png)

