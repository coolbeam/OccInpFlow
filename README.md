# OccInpFlow: Occlusion-Inpainting Optical Flow Estimation by Unsupervised Learning

By Kunming Luo, [Chuan Wang](http://wangchuan.github.io/index.html), Nianjin Ye, [Shuaicheng Liu](http://www.liushuaicheng.org/), [Jue Wang](http://www.juew.org/)

Megvii Technology, University of Electronic Science and Technology of China

[[Preprint](https://arxiv.org/abs/2006.16637)]

    @article{luo2020occinpflow,
      title={OccInpFlow: Occlusion-Inpainting Optical Flow Estimation by Unsupervised Learning},
      author={Luo, Kunming and Wang, Chuan and Ye, Nianjin and Liu, Shuaicheng and Wang, Jue},
      journal={arXiv preprint arXiv:2006.16637},
      year={2020}
    }

## Introduction
![inpainting_visualization](./images/gif_v2_1.gif)
Occlusion is an inevitable and critical problem in unsupervised optical flow learning. Existing methods either treat occlusions equally as non-occluded regions or simply remove them to avoid incorrectness. However, the occlusion regions can provide effective information for optical flow learning. In this paper, we present OccInpFlow, an occlusion-inpainting framework to make full use of occlusion regions. Specifically, a new appearance-flow network is proposed to inpaint occluded flows based on the image content. Moreover, a boundary warp is proposed to deal with occlusions caused by displacement beyond image border. We conduct experiments on multiple leading flow benchmark data sets such as Flying Chairs, KITTI and MPI-Sintel, which demonstrate that the performance is significantly improved by our proposed occlusion handling framework. 

This repository includes(is coming):

- Training scripts based on Python and PyTorch; and
- inferring scripts for several benchmarks; and 
- pretrain models. 


    
## Acknowledgement
Part of our codes are adapted from [IRR-PWC](https://github.com/visinf/irr) and [UnFlow](https://github.com/simonmeister/UnFlow), we thank the authors for their contributions.
