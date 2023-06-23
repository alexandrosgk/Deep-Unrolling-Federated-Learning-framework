# Deep-Unrolling-Federated-Learning-framework
we propose a novel approach to enhance Lidar super-resolution for perception tasks in autonomous vehicles, addressing the significant cost associated with high-resolution Lidar sensors. In further detail, our method introduces a regularized optimization problem utilizing a learnable regularizer - essentially a neural network - which is adept at capturing the intricate features and attributes of the data.
To tackle this problem effectively, we propose  a deep unrolling framework, converting our solution into a well-justified deep learning architecture. The learnable parameters of this architecture are directly derived from the solution of the proposed optimization problem 
Further, we extend the capabilities of our deep unrolling technique by incorporating a federated learning strategy. Our deep unrolling federated learning model employs an innovative Adapt-then-Combine strategy, wherein each local unit optimizes its model and, subsequently, their learnable regularizers are combined to formulate a robust global regularizer, equipped to handle diverse environmental conditions.

#Dependencies:
numpy
pytorch
sklearn
rosbags
