## FAIR-Play Dataset from 2.5D Visual Sound
[[Project Page]](http://vision.cs.utexas.edu/projects/2.5D_visual_sound/)    [[arXiv]](https://arxiv.org/abs/1812.04204) [[Video]](https://www.youtube.com/watch?v=Wrx3pv_ixdI)<br/>

<img src='data_collection_rig.png' align="right" width=320>

<br/>

[2.5D Visual Sound](https://arxiv.org/abs/1812.04204)  
 [Ruohan Gao](https://www.cs.utexas.edu/~rhgao/)<sup>1</sup> and [Kristen Grauman](http://www.cs.utexas.edu/~grauman/)<sup>2</sup> <br/>
 <sup>1</sup>UT Austin, <sup>2</sup>Facebook AI Research  
 In Conference on Computer Vision and Pattern Recognition (**CVPR**), 2019  
 
<br/>
 
This repository (~100G) contains the FAIR-Play dataset we collected and used in our [CVPR 2019 paper](http://vision.cs.utexas.edu/projects/2.5D_visual_sound). It contains 1,871 video clips and their corresponding binaural audio clips recorded in a music room. The video clip and binaural clip of the same index are roughly aligned. The splits directory contains the 10 random splits used in the paper. See [PseudoBinaural](https://github.com/SheldonTsui/PseudoBinaural_CVPR2021/tree/master/new_splits) for 5 more challenging splits, where there are no or less scene overlap in the training and testing splits. The code is shared at [2.5D Visual Sound Code](https://github.com/facebookresearch/2.5D-Visual-Sound). 

### Dataset Download
1. The dataset can be downloaded by cloning the repository uisng git lfs:
```
brew install git-lfs
git lfs clone git@github.com:facebookresearch/FAIR-Play.git
git lfs install
git lfs pull
```
2. If you have trouble in downloading the dataset through GitHub, you can also download it using the following commands:
```
wget http://dl.fbaipublicfiles.com/FAIR-Play/videos.tar.gz
wget http://dl.fbaipublicfiles.com/FAIR-Play/audios.tar.gz
wget http://dl.fbaipublicfiles.com/FAIR-Play/splits.tar.gz
```
3. The dataset is also shared at [UT Box](https://utexas.box.com/s/1o0ao4chwi7roq38o8dv8t3lt1pgb24l).

If you find our data or project useful in your research, please cite:

        @inproceedings{gao2019visualsound,
          title={2.5D Visual Sound},
          author={Gao, Ruohan and Grauman, Kristen},
          booktitle={CVPR},
          year={2019}
        }

### Acknowlegements
We would like to thank Tony Miller, Jacob Donley, Pablo Hoffmann and Vladimir Tourbabin from Facebook for helpful discussions and the volunteers who participate in our data collection.

### Licence
FAIR-Play is CC BY 4.0 licensed, as found in the LICENSE file.
