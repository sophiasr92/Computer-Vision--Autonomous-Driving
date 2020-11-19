# Computer-Vision--Autonomous-Driving
Based on the Kaggle Competition Peking University/Baidu - Autonomous Driving
Dataset from https://www.kaggle.com/c/pku-autonomous-driving/data

Predicting vehicle angle in different settings for the autonomous driving system. 
Developed an algorithm to estimate the absolute pose of vehicles from a single image in a real-world traffic environment using CenterNet as a baseline model which models an object as a single point which is the center
point of a bounding box.
Implemented various regularization methods such as data augmentation, early stopping, image preprocessing
technique, GCN and tuned the various hyperparameters to improve the performance and reduce overfitting.

## References
@misc{song2018apollocar3d,
      title={ApolloCar3D: A Large 3D Car Instance Understanding Benchmark for Autonomous Driving}, 
      author={Xibin Song and Peng Wang and Dingfu Zhou and Rui Zhu and Chenye Guan and Yuchao Dai and Hao Su and Hongdong Li and Ruigang Yang},
      year={2018},
      eprint={1811.12222},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

CenterNet paper : https://arxiv.org/pdf/1904.07850.pdf
Repository : https://github.com/xingyizhou/CenterNet
