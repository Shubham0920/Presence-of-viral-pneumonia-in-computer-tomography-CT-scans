
# 3D image classification from CT scans

This example will show the steps needed to build a 3D convolutional neural network (CNN) to predict the presence of viral pneumonia in computer tomography (CT) scans. 2D CNNs are commonly used to process RGB images (3 channels). A 3D CNN is simply the 3D equivalent: it takes as input a 3D volume or a sequence of 2D frames (e.g. slices in a CT scan), 3D CNNs are a powerful model for learning representations for volumetric data.
## References

 - [A survey on Deep Learning Advances on Different 3D DataRepresentations](https://arxiv.org/pdf/1808.01462.pdf)
 - [VoxNet: A 3D Convolutional Neural Network for Real-Time Object Recognition](http://3ddl.cs.princeton.edu/2016/papers/Hegde_Zadeh.pdf    )
 - [Uniformizing Techniques to Process CT scans with 3D CNNs for Tuberculosis Prediction](https://arxiv.org/abs/2007.13224)

  
## Screenshots
#### Example of normal 

This model is 99.61 percent confident that CT scan is normal

This model is 0.39 percent confident that CT scan is abnormal

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

  
#### Example of abnormal

This model is 0.49 percent confident that CT scan is normal

This model is 99.51 percent confident that CT scan is abnormal

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
