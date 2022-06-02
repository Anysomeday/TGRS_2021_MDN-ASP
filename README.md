Multi-direction Networks with Attentional Spectral Prior for Hyperspectral Image Classification, TGRS, 2021.
==
[Bobo Xi](https://scholar.google.com/citations?user=O4O-s4AAAAAJ&hl=zh-CN), [Jiaojiao Li](https://scholar.google.com/citations?user=Ccu3-acAAAAJ&hl=zh-CN&oi=sra), [Yunsong Li](https://dblp.uni-trier.de/pid/87/5840.html), [Rui song](https://scholar.google.com/citations?user=_SKooBYAAAAJ&hl=zh-CN), [Yuchao Xiao](https://ieeexplore.ieee.org/author/37089176254), [Yanzi Shi](https://www.researchgate.net/scientific-contributions/Yanzi-Shi-2149921066) and [Qian Du](https://scholar.google.com/citations?user=0OdKQoQAAAAJ&hl=zh-CN).

***
Code for paper: [Multi-direction Networks with Attentional Spectral Prior for Hyperspectral Image Classification.](https://ieeexplore.ieee.org/document/9325080) 

<div align=center><img src="/Image/frameworks.jpg" width="80%" height="80%"></div>
Fig. 1: The framework of our proposed MDN-ASP for HSI classification. It is composed of four components: multi-direction samples construction, multi-stream feature extraction, feature aggregation with attentional spectral prior (ASP) and a softmax-based classifier. The same color represents the layers with same operation.

Training and Test Process
--
Please firstly run the 'generate_train_val_test_gt.m' to generate the training and test maps. Then, run 'construct_multi_mat.py' to construct the multi-direction samples. Finally, run 'main_MDN_ASP.py' to reproduce the MDN-ASP results on [IndianPines](http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes#Indian_Pines) data set. The training samples distribution and the obtained classification map are shown below. We have successfully test it on Ubuntu 16.04 and Windows systems with Matlab R2017b. Part of the source code are employed from the works of [DR-CNN](https://fdss.bit.edu.cn/yjdw/js/153191.htm) and [SSRN](https://github.com/zilongzhong/SSRN).

<div align=center><p float="center">
<img src="/Image/falsecolorimage.jpg" width="200"/>
<img src="/Image/IndianP_gt.jpg" width="200"/>
<img src="/Image/trainingMap.jpg" width="200"/>
<img src="/Image/classification_map.jpg" width="200"/>
</p></div>
<div align=center>Fig. 2: The composite false-color image, groundtruth, training samples, and classification map of Indian Pines dataset.</div>
      
References
--
If you find this code helpful, please kindly cite:

[1] B. Xi, J. Li, Y. Li, R. Song, Y. Xiao, Y. Shi, Q. Du "Multi-direction Networks with Attentional Spectral Prior for Hyperspectral Image Classification," in IEEE Transactions on Geoscience and Remote Sensing, vol. 60, pp. 1-15, 2022, Art no. 5500915, doi: [10.1109/TGRS.2020.3047682](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9325080&tag=1)  
[2] B. Xi, J. Li, Y. Li, R. Song, Y. Shi, S. Liu, Q. Du "Deep Prototypical Networks With Hybrid Residual Attention for Hyperspectral Image Classification," in IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 13, pp. 3683-3700, 2020, doi: [10.1109/JSTARS.2020.3004973](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9126161).  

Citation Details
--
BibTeX entry:
```
@ARTICLE{Xi_TGRS2020_MDNASP,
  author={Xi, Bobo and Li, Jiaojiao and Li, Yunsong and Song, Rui and Xiao, Yuchao and Shi, Yanzi and Du, Qian},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Multi-Direction Networks With Attentional Spectral Prior for Hyperspectral Image Classification}, 
  year={2022},
  volume={60},
  number={},
  pages={1-15},
  doi={10.1109/TGRS.2020.3047682}}
```
```
@ARTICLE{Xi2020JSTARS,
  author={Xi, Bobo and Li, Jiaojiao and Li, Yunsong and Song, Rui and Shi, Yanzi and Liu, Songlin and Du, Qian},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Deep Prototypical Networks With Hybrid Residual Attention for Hyperspectral Image Classification}, 
  year={2020},
  volume={13},
  number={},
  pages={3683-3700},
  doi={10.1109/JSTARS.2020.3004973}}
 ```

Licensing
--
Copyright (C) 2021 Bobo Xi

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.
