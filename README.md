# Project motivation

In the context of the mentioned computer vision project, we are employing the YOLOv4 architecture to carry out the detection and extraction of the region of interest within converted medical images. This approach involves transforming clinical data from patient records into image format, followed by the selective identification of a specific segment of interest within these images. Particularly, YOLOv4, or "You Only Look Once version 4," is distinguished by its high precision and computational efficiency in real-time object detection. It utilizes a single convolutional neural network to predict bounding box coordinates and object classification probabilities in a single pass over the input image. In our case, the implementation of YOLOv4 enables us to search through a database housing approximately 150,000 clinical images, selectively extracting the required segment for further analysis.

best.weights location: C:\Users\Joan Camilo\Desktop\P\Python\YOLO V4

# Detected medical record

![image](https://github.com/joancamilo1/Computer_vision_YoloV4/assets/105089010/1bb54460-9209-4a58-8557-9257442336d5)

# Discarded image

![image](https://github.com/joancamilo1/Computer_vision_YoloV4/assets/105089010/5cf64a48-415b-47f6-8332-ae9362c16e42)


# YOLOv4 Darknet Object Detection Model

YOLOv4, or "You Only Look Once version 4," represents an advanced approach to object detection within computer vision. At its core, YOLOv4 utilizes convolutional neural networks (CNNs) to perform its tasks. CNNs are a class of deep neural networks particularly effective for image processing tasks due to their ability to automatically learn and extract features from raw pixel data.

A convolutional neural network consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers. In YOLOv4 specifically, these layers are designed to efficiently process input images and identify objects within them.

1. Convolutional Layers: These layers apply convolution operations to the input image, using learnable filters or kernels. These filters slide over the input image, detecting various features such as edges, textures, and patterns. Through the training process, the network learns to adapt these filters to recognize more complex features relevant to the task at hand.

2. Pooling Layers: Pooling layers downsample the feature maps produced by the convolutional layers, reducing their spatial dimensions. This helps in reducing computational complexity and controlling overfitting by extracting the most relevant information from the feature maps.

3. Fully Connected Layers: These layers, also known as dense layers, connect every neuron in one layer to every neuron in the next layer, allowing the network to make predictions based on the features extracted by the preceding layers.

In the case of YOLOv4, the architecture is optimized for real-time object detection, meaning it can process images quickly and accurately. YOLOv4 achieves this by employing a single neural network to predict bounding boxes and class probabilities directly from full images in a single evaluation. This approach contrasts with traditional methods, which typically involve region proposal networks followed by post-processing steps to refine detections.

The strength of YOLOv4 lies in its ability to efficiently process images and make predictions in real-time, making it well-suited for applications such as autonomous driving, surveillance, and medical image analysis, where quick and accurate detection of objects or features is crucial.
