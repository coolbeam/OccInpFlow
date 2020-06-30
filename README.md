# OccInpFlow
This is the code for our paper: OccInpFlow: Occlusion-Inpainting Optical Flow Estimation by Unsupervised Learning

# Dataset
## KITTI
For model training on KITTI dataset we use the [raw data](http://www.cvlibs.net/datasets/kitti/raw_data.php?type=city) for our unsupervised training and evaluate our model on the official train set of [kitti 2012](http://www.cvlibs.net/datasets/kitti/eval_stereo_flow.php?benchmark=flow) and [KITTI 2015](http://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=flow) dataset. \\
Your can further finetune models on the multi-view extention data [multi-view KITTI 2012](http://www.cvlibs.net/download.php?file=data_stereo_flow_multiview.zip) and [multi-view KITTI 2015](http://www.cvlibs.net/download.php?file=data_scene_flow_multiview.zip) for better performance. Note that we have not do this finetune process in our paper. 

