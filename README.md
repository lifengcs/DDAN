# DDAN
## Introduction
This is the implementation of [*Learning a Deep Dual Attention Network
for Video Super-Resolution*](https://ieeexplore.ieee.org/document/8995790).([*IEEE TIP*](https://ieeexplore.ieee.org/document/8995790))
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/DDAN.png)
The architecture of our proposed deep dual attentian network(DDAN).
## Environment
+ python==3.6 
+ Tensorflow==1.13.1
## models
Download trained DDAN model from [Baiduyun](https://pan.baidu.com/s/1S65vewNAShIPqbvrZLrX1w) we provide. (Access code for Baiduyun: zelr)
Unzip and place the files in the ``` DDAN_x4``` directory
## Installations
+ numpy==1.16.4
+ scipy==1.2.1
+ Pillow==8.1.2
## Testing
For testing, you can test one video or videos using function ``` testvideo()``` or ``` testvideos()```. Please change the test video directory.
```
# testvideos()
python main.py
```
## Training
You can also train your DDNL using function ``` train()```. Before you train your models, download the data for training in ``` data``` directory.
```
# model.train()
python main.py
```
## Visual results
Here are the results from different dataset.
The frame is from [*Myanmar*](https://ieeexplore.ieee.org/document/7444187).
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/vis1.png)

The frame is from [*calendar*](https://openaccess.thecvf.com/content_cvpr_2017/papers/Caballero_Real-Time_Video_Super-Resolution_CVPR_2017_paper.pdf). 
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/vis2.png)


The frame is from real-world LR videos we captured.
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/vis3.png)

## Citation
If you use our code or model in your research, please cite with:
```
@ARTICLE{8995790,
  author={F. {Li} and H. {Bai} and Y. {Zhao}},
  journal={IEEE Transactions on Image Processing},
  title={Learning a Deep Dual Attention Network for Video Super-Resolution},
  year={2020},
  volume={29},
  pages={4474-4488},
  doi={10.1109/TIP.2020.2972118}
 }
```
## ACknowledgements
This code is built on [MMCNN](https://github.com/psychopa4/MMCNN)(Tensorflow), we thank the authors for sharing their code.
