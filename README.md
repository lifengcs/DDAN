# DDAN
## Introduction
This is the implementation of [*Learning a Deep Dual Attention Network
for Video Super-Resolution*](https://ieeexplore.ieee.org/document/8995790). This repository contains the trained model and the code to conduct the video SR and train a new model based on the provide models. In this work, we propose a deep dual attention network (DDAN), including a motion compensation network (MCNet) and a SR reconstruction network (ReconNet), to fully exploit the spatio-temporal informative features for accurate video SR. The MCNet progressively learns the optical flow representations to synthesize the motion information across adjacent frames in a pyramid fashion. To decrease the mis-registration errors caused by the optical flow based motion compensation, we extract the detail components of original LR neighboring frames as complementary information for accurate feature extraction. In the ReconNet, we implement dual attention mechanisms on a residual unit and form a residual attention unit to focus on the intermediate informative features for high-frequency details recovery. Extensive experimental results on numerous datasets demonstrate the proposed method can effectively achieve superior performance in terms of quantitative and qualitative assessments compared with state-of-the-art methods.
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/DDAN.png)
## Environment
python==3.6 \
Tensorflow==1.13.1
## Installations
scipy==1.2.1
## Testing

## Training

## Visual results
Here are the results from different dataset.
The frame is from [*Myanmar*](https://ieeexplore.ieee.org/document/7444187).
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/vis1.png)
The frame is from [*calendar*](https://openaccess.thecvf.com/content_cvpr_2017/papers/Caballero_Real-Time_Video_Super-Resolution_CVPR_2017_paper.pdf). 
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/vis2.png)
The frame is from real-world LR videos we captured.
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/vis3.png)
