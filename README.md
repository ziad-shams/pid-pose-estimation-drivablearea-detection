# Pedestrian Intention Detection Model
Code for my bachelor thesis titled 'Enhanced Pedestrian Intention Detection for ADAS and Autonomous Vehicles.'

# Setup
To get started with training or evaluating the model, open **'train_eval.ipynb'** on Google Colab and follow the provided instructions.

To demo the Pedestrian Intention Detection (PID) system, open **'demo.ipynb'** on Google Colab and follow the provided instructions.

# PID System
![pid](https://github.com/ziad-shams/pid-pose-estimation-drivablearea-detection/assets/17318746/44438ebc-b306-4a17-964a-0822cb8db073)

# Components and Libraries
The PID system is built using the following components and libraries:

**YOLO-NAS-Pose**: Implements pose estimation using the SuperGradients library.
**Deep OC-SORT**: Implements pedestrian tracking using the BoxMot library.
**YOLOP**: For detecting the drivable area and lane segmentation.
**Spatiotemporal DenseNet**: For predicting whether a pedestrian is crossing or not.

# Credit

The following repositories provided foundational code that was adapted for this project:


The code for YOLOP was adapted from the GitHub repository: [https://github.com/hustvl/YOLOP](https://github.com/hustvl/YOLOP)

The code for ST-DenseNet was adapted from the GitHub repository: [https://github.com/GalDude33/DenseNetFCN-3D](https://github.com/GalDude33/DenseNetFCN-3D)

The code for rolling data was adapted from the GitHub repository: [https://github.com/mjpramirez/Volvo-DataX](https://github.com/mjpramirez/Volvo-DataX)


Special thanks to the authors of these repositories for their contributions.




