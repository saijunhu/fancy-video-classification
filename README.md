# fancy-video-classification
Video Classifiication Paper List

## Papers 
### Recommendations!
### arXiv
- Cao, Haoyuan, Shining Yu, and Jiashi Feng.  
"Compressed Video Action Recognition with Refined Motion Vector." arXiv(2019).[[PDF](https://arxiv.org/pdf/1910.02533)]
### CVPR2020
- **TEA**:Yan Li, Bin Ji, et al.  
"TEA: Temporal Excitation and Aggregation for Action Recognition" CVPR(2020)[[PDF](https://arxiv.org/pdf/2004.01398)]
### CVPR2019
- **Dmc-net**:Shou, Zheng, et al.  
"Dmc-net: Generating discriminative motion cues for fast compressed video action recognition." CVPR(2019).[[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shou_DMC-Net_Generating_Discriminative_Motion_Cues_for_Fast_Compressed_Video_Action_CVPR_2019_paper.pdf)][[Code](https://github.com/facebookresearch/dmc-net)]
### ICCV2019
- **SlowFast**: Feichtenhofer C, Fan H, Malik J, et al.  
"Slowfast Networks for Video Recognition",ICCV(2019 **oral**).[[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Feichtenhofer_SlowFast_Networks_for_Video_Recognition_ICCV_2019_paper.pdf)][[Code](https://github.com/facebookresearch/SlowFast)]
- **TSM**: Chuang Gan, Song Han,Ji Lin   
"Temporal Shift Module for Efficient Video Understanding",ICCV(2019).[[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lin_TSM_Temporal_Shift_Module_for_Efficient_Video_Understanding_ICCV_2019_paper.pdf)][[Code](https://github.com/mit-han-lab/temporal-shift-module)]
- **STM**: Jiang, Boyuan, et al.  
"STM: SpatioTemporal and motion encoding for action recognition." ICCV(2019).[[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Jiang_STM_SpatioTemporal_and_Motion_Encoding_for_Action_Recognition_ICCV_2019_paper.pdf)]
### NIPS2019
- **bLVNet-TAM**: Quanfu Fan, Chun-Fu (Richard) Chen, Hilde Kuehne, Marco Pistoia, David Cox   
"More Is Less: Learning Efficient Video Representations by Big-Little Network and Depthwise Temporal Aggregation".NIPS(2019)[[PDF](https://papers.nips.cc/paper/8498-more-is-less-learning-efficient-video-representations-by-big-little-network-and-depthwise-temporal-aggregation.pdf)][[Code](https://github.com/IBM/bLVNet-TAM)]
### CVPR 2018
- **R(2+1)D**: Tran, Du, et al.  
"A closer look at spatiotemporal convolutions for action recognition." CVPR(2018).[[PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tran_A_Closer_Look_CVPR_2018_paper.pdf)][[Code](https://github.com/irhum/R2Plus1D-PyTorch)]
- **CoViAR**:Wu, Chao-Yuan, et al.  
"Compressed video action recognition." CVPR(2018).[[PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wu_Compressed_Video_Action_CVPR_2018_paper.pdf)][[Code](https://github.com/chaoyuaw/pytorch-coviar)]
- **Non-local**：Wang, Xiaolong, et al.  
"Non-local neural networks." CVPR(2018).[[PDF](https://arxiv.org/pdf/1711.07971.pdf)][[Code](https://github.com/facebookresearch/video-nonlocal-net)]
### NIPS 2018
- **TrajectoryNet**: Zhao, Yue, Yuanjun Xiong, and Dahua Lin.  
"Trajectory convolution for action recognition." NIPS(2018)[[PDF](http://papers.nips.cc/paper/7489-trajectory-convolution-for-action-recognition.pdf)]
### CVPR 2017
- **I3D**: Carreira Joao and Andrew Zisserman.  
"Quo vadis, action recognition? a new model and the kinetics dataset" CVPR(2017).[[PDF](http://openaccess.thecvf.com/content_cvpr_2017/papers/Carreira_Quo_Vadis_Action_CVPR_2017_paper.pdf)][[Code](https://github.com/deepmind/kinetics-i3d)]
### ECCV2016
- **TSN**:Wang, Limin, et al.  
"Temporal segment networks: Towards good practices for deep action recognition." ECCV(2016)[[PDF](https://arxiv.org/pdf/1608.00859.pdf)][[Code](https://github.com/yjxiong/temporal-segment-networks)]
### NIPS2014
- **Two Stream**: Simonyan, Karen, and Andrew Zisserman.  
"Two-stream convolutional networks for action recognition in videos." NIPS(2014).[[PDF](https://papers.nips.cc/paper/5353-two-stream-convolutional-networks-for-action-recognition-in-videos.pdf)][[Code](https://github.com/jeffreyyihuang/two-stream-action-recognition)]
### ICCV2013
- **IDT**:Wang, Heng, and Cordelia Schmid.  
"Action recognition with improved trajectories." ICCV(2013).[[PDF](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Wang_Action_Recognition_with_2013_ICCV_paper.pdf)]


## Competitions

## Datasets
- [UCF101](https://www.crcv.ucf.edu/data/UCF101.php)  
13320 videos; average time ~10s; 101 human action categories,each class has 25 groups,videos in same group share some common features; datasets are not realistic and are staged by actors.
- [HMDB51](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/)  
6849 videos; average time ~5s; 51 human action categories, each containing a minimum of 101 videos; datasets are most from movies clips, and a small proportion from other public datasets and web videos.
- [Kinetics](https://deepmind.com/research/open-source/kinetics)(due to the missing videos in kinetics source csv, the 'nolocal net' reseachers offer a pre-downloaded version of kinetics-400,here it's the [relevent issue](https://github.com/facebookresearch/video-nonlocal-net/issues/67))  
650000 videos; average time ~10s; 700/600/400 human categories, each action class has at least 600 video clips; datasets are most from youtube videos.
- [Something-something v2](https://20bn.com/datasets/something-something#download)  
220847 videos; average time 2~6s; 174 human basic action categories; datasets focus the human fine-grined actions,such as "Putting something on a surface".
- [Charades](https://prior.allenai.org/projects/charades)  
average ~30s per video, long-term video dataset.
- [Moments in Time](http://moments.csail.mit.edu/challenge.html)  
about one millon videos; average time ~3s, involving people, animals, objects or natural phenomena, that capture the gist of a dynamic scene.

## Benchmarks
## Distinguished Researchers & Teams
- [Liming,Wang](https://wanglimin.github.io/)  Nanjing University
