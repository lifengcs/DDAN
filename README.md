# DDAN
## Introduction
This is the implementation of [*Learning a Deep Dual Attention Network
for Video Super-Resolution*](https://ieeexplore.ieee.org/document/8995790).(*IEEE Trans*)
![image](https://github.com/lifengshiwo/DDAN/blob/main/figures/DDAN.png)
The architecture of our proposed deep dual attentian network(DDAN).
## Environment
+ python==3.6 
+ Tensorflow==1.13.1
## Installations
+ scipy==1.2.1
## Testing
```
python main.py
```
## Training

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
