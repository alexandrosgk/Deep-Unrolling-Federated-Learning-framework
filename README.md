## Deep-Unrolling-model-for-Lidar-Super-Resolution
Considering the high cost of high-resolution Lidar sensors, in this work, a novel Lidar super-resolution method is proposed to improve the performance on numerous autonomous vehicle perception tasks, including that of a Lidar odometer. In more detail, we propose a regularized optimization problem  employing a learnable regularizer (neural network) to capture the properties of the data. To efficiently solve this problem, a deep unrolling methodology is proposed, thus forming  an interpretable and well-justified deep architecture, where  its learnable parameters derived from the solution of
the optimization algorithm.

## Dependencies

The following Python libraries are required to run this project:
- numpy
- pytorch
- sklearn
- rosbags

## Data

The data used in this work is derived from the [Lidar Super Resolution](https://github.com/RobustFieldAutonomyLab/lidar_super_resolution/tree/master) repository on GitHub.

To download the training and testing datasets used in this work, please visit the following link: [Data Folder](https://drive.google.com/drive/folders/1oPNyeNW8yeBrWHMWRlYCT_e4tfMPzLKO)
