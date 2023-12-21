Vehicle re-identification is an active research area in
intelligent transportation systems (ITS) that involves
identifying a specific vehicle across non-overlapping
images in a multi-camera network. This task is challenging
due to multiple factors, including similarity between
classes, variations within classes, and changes in
viewpoint, and spatiotemporal ambiguity. The
development of effective vehicle re-id technologies has the
potential to provide valuable insights into traffic flow
patterns and vehicle behavior in urban environments.
There have been several research efforts to address the
challenges associated with vehicle re-id. Deep learningbased methods such as convolutional neural networks
(CNNs), recurrent neural networks (RNNs), and Siamese
networks are commonly used in vehicle re-identification
tasks. These methods have been shown to be effective in
capturing and learning relevant features from images and
improving the performance of the vehicle re-identification
task. This report is a study of various CNN architecture
being used for vehicle re-identification.

1. CNN architetcures used in this study are: mobilenet_v3_small, resnet18, regnet_x_400mf
2. Explored different data augmentation techniques,optimizers like Adam, RMSprop, SGD Hyperparameters like learning rate, batch size, learning rate scheduler, step size.
3. Also experimented with modification in ResNet-18 architecture by adding a 5th convolution layer and also changing the activation to LeakyReLU.
4. The evalution parameter used to evaluate the model was mean avaerage precision- mAp.
