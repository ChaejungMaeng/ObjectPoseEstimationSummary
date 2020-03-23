# Awesome Object Pose Estimation

A curated list of challenges and papers pertaining to object pose estimation

## Challenges :space_invader:
* [ECCV 2020: Recovering Object Pose](http://cmp.felk.cvut.cz/sixd/workshop_2020/)
* [ICCV 2019: Recovering Object Pose](http://cmp.felk.cvut.cz/sixd/workshop_2019/)
* [ECCV 2018: Recovering Object Pose](http://cmp.felk.cvut.cz/sixd/workshop_2018/)
* [ICCV 2017: Recovering Object Pose](http://cmp.felk.cvut.cz/sixd/workshop_2017/)
* [ECCV 2016: Recovering Object Pose](https://labicvl.github.io/R6D)
* [ICCV 2015: Recovering Object Pose](https://labicvl.github.io/3DPose-2015.html)
* [ICCV 2015: Occluded Object Challenge](https://hci.iwr.uni-heidelberg.de/vislearn/iccv2015-occlusion-challenge/) 


## Papers :ghost:

### ArXiv

* **CPS**: Fabian Manhardt, Manuel Nickel, Sven Meier, Luca Minciullo, Nassir Navab.\
"CPS: Class-level 6D Pose and Shape Estimation From Monocular Images."\
[pdf](https://arxiv.org/abs/2003.05848)

* **HybridPose**: Chen Song, Jiaru Song, Qixing Huang.\
"HybridPose: 6D Object Pose Estimation under Hybrid Representations."\
[code](https://github.com/chensong1995/HybridPose) | [pdf](https://arxiv.org/abs/2001.01869)

* **Multi-path**: Martin Sundermeyer, Maximilian Durner, En Yen Puang, Zoltan-Csaba Marton, Rudolph Triebel.\
"Multi-path Learning for Object Pose Estimation Across Domains."\
[pdf](https://arxiv.org/abs/1908.00151)

---

### 2020

* **LatentFusion**: Keunhong Park, Arsalan Mousavian, Yu Xiang, Dieter Fox.\
"LatentFusion: End-to-End Differentiable Reconstruction and Rendering for Unseen Object Pose Estimation." CVPR (2020)\
[pdf](https://arxiv.org/abs/1912.00416)

* **BPnP**: Bo Chen, Tat-Jun Chin, Alvaro Parra, Jiewei Cao, Nan Li.\
"End-to-End Learnable Geometric Vision by Backpropagating PnP Optimization." CVPR (2020)\
[code](https://github.com/BoChenYS/BPnP) | [pdf](https://arxiv.org/abs/1909.06043)

* **PVN3D**: Yisheng He, Wei Sun, Haibin Huang, Jianran Liu, Haoqiang Fan, Jian Sun.\
"PVN3D: A Deep Point-wise 3D Keypoints Voting Network for 6DoF Pose Estimation." CVPR (2020)\
[code](https://github.com/ethnhe/PVN3D) | [pdf](https://arxiv.org/abs/1911.04231)

* **Single-Stage 6D Pose**: Yinlin Hu, Pascal Fua, Wei Wang, Mathieu Salzmann.\
"Single-Stage 6D Object Pose Estimation." CVPR (2020)\
[pdf](https://arxiv.org/pdf/1911.08324.pdf)

####

* **6-PACK**: Chen Wang, Roberto Martín-Martín, Danfei Xu, Jun Lv, Cewu Lu, Li Fei-Fei, Silvio Savarese, Yuke Zhu.\
"6-PACK: Category-level 6D Pose Tracker with Anchor-Based Keypoints." ICRA (2020)\
[code](https://github.com/j96w/6-PACK) | [pdf](https://arxiv.org/abs/1910.10750)

* **Self-Supervised 6D**: Xinke Deng, Yu Xiang, Arsalan Mousavian, Clemens Eppner, Timothy Bretl and Dieter Fox.\
"Self-supervised 6D Object Pose Estimation for Robot Manipulation." ICRA (2020)\
[pdf](https://arxiv.org/abs/1909.10159)

* **DirectShape**: Rui Wang, Nan Yang, Joerg Stueckler, Daniel Cremers.\
"DirectShape: Direct Photometric Alignment of Shape Priors for Visual Vehicle Pose and Shape Estimation." ICRA (2020)\
[pdf](https://arxiv.org/abs/1904.10097)


### 2019

* **PoseRBPF**: Xinke Deng, Arsalan Mousavian, Yu Xiang, Fei Xia, Timothy Bretl and Dieter Fox.\
"PoseRBPF: A Rao-Blackwellized Particle Filter for 6D Object Pose Tracking." RSS (2019)\
[pdf](https://arxiv.org/abs/1905.09304)

---

* **GP2C**: Alexander Grabner, Peter M. Roth and Vincent Lepetit.\
"GP2C: Geometric Projection Parameter Consensus for Joint 3D Pose and Focal Length Estimation in the Wild." ICCV (2019)\
[pdf](https://arxiv.org/abs/1908.02809)

* **RGB-CAD**: Georgios Georgakis, Srikrishna Karanam, Ziyan Wu, Jana Kosecka.\
"Learning Local RGB-to-CAD Correspondences for Object Pose Estimation." ICCV (2019)\
[pdf](https://arxiv.org/abs/1811.07249)

* **Wasserstein Training**: Xiaofeng Liu, Yang Zou, Tong Che, Peng Ding, Ping Jia, Jane You, B.V.K. Vijaya Kumar.\
"Conservative Wasserstein Training for Pose Estimation." ICCV (2019)\
[pdf](http://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_Conservative_Wasserstein_Training_for_Pose_Estimation_ICCV_2019_paper.pdf)

* **Pix2Pose**: Kiru Park, Timothy Patten, Markus Vincze.\
"Pix2Pose: Pixel-Wise Coordinate Regression of Objects for 6D Pose Estimation." ICCV (2019)\
[code](https://github.com/kirumang/Pix2Pose) | [pdf](https://arxiv.org/abs/1908.07433)

* **DPOD**: Sergey Zakharov, Ivan Shugurov, Slobodan Ilic.\
"DPOD: 6D Pose Object Detector and Refiner." ICCV (2019)\
[pdf](https://arxiv.org/abs/1902.11020)

* **CDPN**: Zhigang Li, Gu Wang, Xiangyang Ji.\
"CDPN: Coordinates-Based Disentangled Pose Network for Real-Time RGB-Based 6-DoF Object Pose Estimation." ICCV (2019)\
[code](https://github.com/LZGMatrix/BOP19_CDPN_2019ICCV) | [pdf](http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_CDPN_Coordinates-Based_Disentangled_Pose_Network_for_Real-Time_RGB-Based_6-DoF_Object_ICCV_2019_paper.pdf)

* **Pose Ambiguity**: Fabian Manhardt, Diego Martin Arroyo, Christian Rupprecht, Benjamin Busam, Tolga Birdal, Nassir Navab, Federico Tombari.\
"Explaining the Ambiguity of Object Detection and 6D Pose From Visual Data." ICCV (2019)\
[pdf](https://arxiv.org/abs/1812.00287)

* **CorNet**: Giorgia Pitteri, Slobodan Ilic, Vincent Lepetit.\
"CorNet: Generic 3D Corners for 6D Pose Estimation of New Objects without Retraining." ICCV workshop (2019)\
[pdf](https://arxiv.org/abs/1908.11457)

* **CullNet**: Kartik Gupta, Lars Petersson, Richard Hartley.\
"CullNet: Calibrated and Pose Aware Confidence Scores for Object Pose Estimation." ICCV workshop (2019)\
[pdf](https://arxiv.org/abs/1909.13476)

---

* **PoseFromShape**: Yang Xiao, Xuchong Qiu, Pierre-Alain Langlois, Mathieu Aubry, Renaud Marlet.\
"Pose from Shape: Deep Pose Estimation for Arbitrary 3D Objects." BMVC (2019)\
[code](https://github.com/YoungXIAO13/PoseFromShape) | [pdf](https://arxiv.org/abs/1906.05105) 

* **Few-Shot Viewpoint**: Hung-Yu Tseng, Shalini De Mello, Jonathan Tremblay, Sifei Liu, Stan Birchfield, Ming-Hsuan Yang, Jan Kautz.\
"Few-Shot Viewpoint Estimation." BMVC (2019)\
[pdf](https://arxiv.org/abs/1905.04957)

---

* **PVNet**: Sida Peng, Yuan Liu, Qixing Huang, Xiaowei Zhou, Hujun Bao. \
"PVNet: Pixel-wise Voting Network for 6DoF Pose Estimation" CVPR (2019)\
[code](https://github.com/zju3dv/pvnet) | [pdf](https://arxiv.org/abs/1812.11788)

* **DesnseFusion**: Chen Wang, Danfei Xu, Yuke Zhu, Roberto Martín-Martín, Cewu Lu, Li Fei-Fei, Silvio Savarese. \
"DenseFusion: 6D Object Pose Estimation by Iterative Dense Fusion." CVPR (2019) \
[code](https://github.com/j96w/DenseFusion) | [pdf](https://arxiv.org/abs/1901.04780)

* **NOCS**: He Wang, Srinath Sridhar, Jingwei Huang, Julien Valentin, Shuran Song, Leonidas J. Guibas. \
"Normalized Object Coordinate Space for Category-Level 6D Object Pose and Size Estimation." CVPR (2019)\
[code](https://github.com/hughw19/NOCS_CVPR2019) | [pdf](https://arxiv.org/abs/1901.02970)

* **SegDriven**: Yinlin Hu, Joachim Hugonot, Pascal Fua, Mathieu Salzmann. \
"Segmentation-driven 6D Object Pose Estimation." CVPR (2019)\
[code](https://github.com/cvlab-epfl/segmentation-driven-pose) | [pdf](https://arxiv.org/abs/1812.02541)

* **ROI-10D**: Fabian Manhardt, Wadim Kehl, Adrien Gaidon.\
"ROI-10D: Monocular Lifting of 2D Detection to 6D Pose and Metric Shape." CVPR (2019)\
[pdf](https://arxiv.org/abs/1812.02781)

* **Spherical Regression**: Shuai Liao, Efstratios Gavves, Cees G. M. Snoek.\
"Spherical Regression: Learning Viewpoints, Surface Normals and 3D Rotations on n-Spheres." CVPR (2019)\
[code](https://github.com/leoshine/Spherical_Regression) | [pdf](https://arxiv.org/abs/1904.05404)


### 2018

* **PoseCNN**: Yu Xiang, Tanner Schmidt, Venkatraman Narayanan, Dieter Fox.\
"PoseCNN: A Convolutional Neural Network for 6D Object Pose Estimation in Cluttered Scenes." RSS (2018)\
[code](https://github.com/yuxng/PoseCNN) | [pdf](https://arxiv.org/abs/1711.00199)

* **DOPE**: Jonathan Tremblay, Thang To, Balakumar Sundaralingam, Yu Xiang, Dieter Fox, Stan Birchfield.\
"Deep Object Pose Estimation for Semantic Robotic Grasping of Household Objects."(CoRL 2018) \
[code](https://github.com/NVlabs/Deep_Object_Pose) | [pdf](https://arxiv.org/abs/1809.10790)

* **SilhoNet**: Gideon Billings, Matthew Johnson-Roberson.\
"SilhoNet: An RGB Method for 3D Object Pose Estimation and Grasp Planning." ICRA (2018)\
[code](https://github.com/gidobot/SilhoNet) | [pdf](https://arxiv.org/abs/1809.06893)

* **Rotational Symmetry**: Enric Corona, Kaustav Kundu, Sanja Fidler.\
"Pose Estimation for Objects with Rotational Symmetry." IROS (2018)\
[code](https://github.com/enriccorona/PoseSym) | [pdf](https://arxiv.org/abs/1810.05780)

* **Pose-Interpreter**: Jimmy Wu, Bolei Zhou, Rebecca Russell, Vincent Kee, Syler Wagner, Mitchell Hebert, Antonio Torralba, David M.S. Johnson.\
"Real-Time Object Pose Estimation with Pose Interpreter Networks." IROS (2018)\
[code](https://github.com/jimmyyhwu/pose-interpreter-networks) | [pdf](https://arxiv.org/abs/1808.01099)

---

* **iPose**: Omid Hosseini Jafari, Siva Karthik Mustikovela, Karl Pertsch, Eric Brachmann, Carsten Rother.\
"iPose: Instance-Aware 6D Pose Estimation of Partly Occluded Objects." ACCV (2018)\
[pdf](https://arxiv.org/abs/1712.01924)

* **DomainTransfer**: Mahdi Rad, Markus Oberweger, Vincent Lepetit.\
"Domain Transfer for 3D Pose Estimation from Color Images without Manual Annotations." ACCV (2018)\
[pdf](https://arxiv.org/abs/1810.03707)

---

* **AugmentedAutoencoder**: Martin Sundermeyer, Zoltan-Csaba Marton, Maximilian Durner, Manuel Brucker, Rudolph Triebel.\
"Implicit 3D Orientation Learning for 6D Object Detection from RGB Images." ECCV (2018)\
[code](https://github.com/DLR-RM/AugmentedAutoencoder) | [pdf](https://arxiv.org/abs/1902.01275)

* **DeepIM**: Yi Li, Gu Wang, Xiangyang Ji, Yu Xiang and Dieter Fox.\
"DeepIM: Deep Iterative Matching for 6D Pose Estimation." ECCV (2018)\
[code](https://github.com/liyi14/mx-DeepIM) | [pdf](https://arxiv.org/abs/1804.00175)

* **StarMap**: Xingyi Zhou, Arjun Karpur, Linjie Luo, Qixing Huang.\
"StarMap for Category-Agnostic Keypoint and Viewpoint Estimation." ECCV (2018)\
[code](https://github.com/xingyizhou/StarMap) | [pdf](https://arxiv.org/abs/1803.09331)

* **Heatmap**: Markus Oberweger, Mahdi Rad, Vincent Lepetit.\
"Making Deep Heatmaps Robust to Partial Occlusions for 3D Object Pose Estimation." ECCV (2018)\
[pdf](https://arxiv.org/abs/1804.03959)

* **Deep Directional Statistics**: Sergey Prokudin, Peter Gehler, Sebastian Nowozin.\
"Deep Directional Statistics: Pose Estimation with Uncertainty Quantification." ECCV (2018)\
[code](https://github.com/sergeyprokudin/deep_direct_stat) | [pdf](https://arxiv.org/abs/1805.03430)

* **Viewpoint Estimation**: Gilad Divon, Ayellet Tal.\
"Viewpoint Estimation-Insights & Model." ECCV (2018) \
[pdf](https://arxiv.org/abs/1807.01312)

* **Multi-View Multi-Class**: Chi Li, Jin Bai, Gregory D. Hager.\
"A Unified Framework for Multi-View Multi-Class Object Pose Estimation." ECCV (2018)\
[pdf](https://arxiv.org/abs/1803.08103)

* **Pose Refine**: Fabian Manhardt, Wadim Kehl, Nassir Navab, Federico Tombari.\
"Deep Model-Based 6D Pose Refinement in RGB." ECCV (2018)\
[code](https://github.com/fabi92/eccv18-rgb_pose_refinement) | [pdf](https://arxiv.org/abs/1810.03065)

* **Fine-Grained**: Yaming Wang, Xiao Tan, Yi Yang, Xiao Liu, Errui Ding, Feng Zhou, Larry S. Davis.\
"3D Pose Estimation for Fine-Grained Object Categories." ECCV workshop (2018)\
[pdf](https://arxiv.org/abs/1806.04314)

---

* **Classification-Regression**: Siddharth Mahendran, Haider Ali, Rene Vidal.\
"A Mixed Classification-Regression Framework for 3D Pose Estimation from 2D Images." BMVC (2018)\
[code](https://github.com/JHUVisionLab/multi-modal-regression) | [pdf](https://arxiv.org/abs/1805.03225)
  
* **Model-Matching**: Chaitanya Mitash, Abdeslam Boularias, Kostas Bekris.\
"Robust 6D Object Pose Estimation with Stochastic Congruent Sets." BMVC (2018)\
[code](https://github.com/cmitash/model_matching) | [pdf](https://arxiv.org/abs/1805.06324)

* **Multi-Task**: Juil Sock, Kwang In Kim, Caner Sahin, Tae-Kyun Kim.\
"Multi-Task Deep Networks for Depth-Based 6D Object Pose and Joint Registration in Crowd Scenarios". BMVC (2018)\
[pdf](https://arxiv.org/abs/1806.03891)


---

* **MultiView Consistency**:  Shubham Tulsiani, Alexei A. Efros, Jitendra Malik.\
"Multi-view Consistency as Supervisory Signal for Learning Shape and Pose Prediction." CVPR (2018) \
[code](https://github.com/shubhtuls/mvcSnP) | [pdf](https://arxiv.org/abs/1801.03910)

* **RotationNet**: Asako Kanezaki, Yasuyuki Matsushita, Yoshifumi Nishida.\
"RotationNet: Joint Object Categorization and Pose Estimation Using Multiviews from Unsupervised Viewpoints." CVPR (2018)\
[code](https://github.com/kanezaki/pytorch-rotationnet) | [pdf](https://arxiv.org/abs/1603.06208)

* **3D-RCNN**: Abhijit Kundu, Yin Li, James M. Rehg.\
"3D-RCNN: Instance-level 3D Object Reconstruction via Render-and-Compare." CVPR (2018)\
[pdf](http://abhijitkundu.info/Publications/3DRCNN_CVPR18.pdf)

* **Feature Mapping**: Mahdi Rad, Markus Oberweger, and Vincent Lepetit.\
"Feature Mapping for Learning Fast and Accurate 3D Pose Inference from Synthetic Images." CVPR (2018)\
[pdf](https://arxiv.org/abs/1712.03904)

* **3D Pose and 3D Model**: Alexander Grabner, Peter M. Roth, and Vincent Lepetit.\
"3D Pose Estimation and 3D Model Retrieval for Objects in the Wild." CVPR (2018)\
[pdf](https://arxiv.org/abs/1803.11493)

* **YOLO-6D**: Bugra Tekin, Sudipta N. Sinha, Pascal Fua.\
"Real-Time Seamless Single Shot 6D Object Pose Prediction." CVPR (2018)\
[code](https://github.com/Microsoft/singleshotpose) | [pdf](https://arxiv.org/abs/1711.08848)


### 2017

* **BB8**: Mahdi Rad, Vincent Lepetit.\
"BB8: A Scalable, Accurate, Robust to Partial Occlusion Method for Predicting the 3D Poses of Challenging Objects without Using Depth." ICCV (2017)\
[pdf](https://arxiv.org/abs/1703.10896)

* **SSD-6D**: Wadim Kehl, Fabian Manhardt, Federico Tombari, Slobodan Ilic, Nassir Navab.\
"SSD-6D: Making RGB-based 3D detection and 6D pose estimation great again." ICCV (2017)\
[code](https://github.com/wadimkehl/ssd-6d) | [pdf](https://arxiv.org/abs/1711.10006)

* **Pose-Guided**: V. Balntas, A. Doumanoglou, C. Sahin, J. Sock, R. Kouskouridas, T-K. Kim.\
"Pose Guided RGBD Feature Learning for 3D Object Pose Estimation." ICCV (2017)\
[pdf](https://labicvl.github.io/docs/pubs/Vassilis_ICCV_2017.pdf)

* **Rethinking Reprojection**: Rui Zhu, Hamed Kiani Galoogahi, Chaoyang Wang, Simon Lucey.\
"Rethinking Reprojection: Closing the Loop for Pose-aware Shape Reconstruction from a Single Image". ICCV (2017)\
[pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Rethinking_Reprojection_Closing_ICCV_2017_paper.pdf)

---

* **ALCN**: Mahdi Rad, Peter M. Roth, Vincent Lepetit.\
"ALCN: Meta-Learning for Contrast Normalization Applied to Robust 3D Pose Estimation." BMVC (2017)\
[pdf](https://arxiv.org/abs/1708.09633)

---

* **Global Hypothesis**: Frank Michel, Alexander Kirillov, Eric Brachmann, Alexander Krull, Stefan Gumhold, Bogdan Savchynskyy, Carsten Rother.\
"Global Hypothesis Generation for 6D Object Pose Estimation." CVPR (2017)\
[pdf](https://arxiv.org/abs/1612.02287)

* **3D Bounding Box**: Arsalan Mousavian, Dragomir Anguelov, John Flynn, Jana Kosecka.\
"3D Bounding Box Estimation Using Deep Learning and Geometry." CVPR (2017)\
[code](https://github.com/smallcorgi/3D-Deepbox) | [pdf](https://arxiv.org/abs/1612.00496)

* **3D Pose Regression**: Siddharth Mahendran, Haider Ali, Rene Vidal.\
"3D Pose Regression using Convolutional Neural Networks." CVPR workshop (2017) \
[pdf](https://arxiv.org/abs/1708.05628)


### 2016

* **Point Pair**: Stefan Hinterstoisser, Vincent Lepetit, Naresh Rajkumar, Kurt Konolige.\
"Going Further with Point Pair Features." ECCV (2016)\
[pdf](https://arxiv.org/abs/1711.04061)

* **RGB-D descriptors**: Wadim Kehl, Fausto Milletari, Federico Tombari, Slobodan Ilic, Nassir Navab.\
"Deep Learning of Local RGB-D Patches for 3D Object Detection and 6D Pose Estimation." ECCV (2016)\
[pdf](https://arxiv.org/abs/1607.06038)

---

* **Crafting Multi-Task**: Francisco Massa, Renaud Marlet, Mathieu Aubry.\
"Crafting a multi-task CNN for viewpoint estimation." BMVC (2016)\
[code](http://imagine.enpc.fr/~suzano-f/bmvc2016-pose/) | [pdf](https://arxiv.org/abs/1609.03894)

---

* **Uncertainty-Driven**: Eric Brachmann, Frank Michel, Alexander Krull, Michael Ying Yang, Stefan Gumhold, Carsten Rother.\
"Uncertainty-Driven 6D Pose Estimation of Objects and Scenes from a Single RGB Image." CVPR (2016)\
[pdf](http://wwwpub.zih.tu-dresden.de/~cvweb/publications/papers/2016/rgbpose.pdf)

* **Recover 6D Pose**: Andreas Doumanoglou, Rigas Kouskouridas, Sotiris Malassiotis, Tae-Kyun Kim.\
"Recovering 6D Object Pose and Predicting Next-Best-View in the Crowd." CVPR (2016)\
[pdf](https://arxiv.org/abs/1512.07506)


### 2015

* **Render for CNN**: Hao Su, Charles R. Qi, Yangyan Li, Leonidas J. Guibas.\
"Render for CNN: Viewpoint Estimation in Images Using CNNs Trained with Rendered 3D Model Views." ICCV (2015)\
[code](https://github.com/ShapeNet/RenderForCNN) | [pdf](https://arxiv.org/abs/1505.05641)

* **Pose Induction**: Shubham Tulsiani, João Carreira, Jitendra Malik.\
"Pose Induction for Novel Object Categories." ICCV (2015)\
[code](https://github.com/shubhtuls/poseInduction) | [pdf](https://arxiv.org/abs/1505.00066)

* **Analysis by Synthesis**: Alexander Krull, Eric Brachmann, Frank Michel, Michael Ying Yang, Stefan Gumhold, Carsten Rother.\
"Learning Analysis-by-Synthesis for 6D Pose Estimation in RGB-D Images." ICCV (2015)\
[pdf](https://arxiv.org/abs/1508.04546)

* **Object Parts Representation**: 
Alberto Crivellaro, Mahdi Rad, Yannick Verdie, Kwang Moo Yi, Pascal Fua, Vincent Lepetit.\
"A Novel Representation of Parts for Accurate 3D Object Detection and Tracking in Monocular Images." ICCV (2015)\
[pdf](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Crivellaro_A_Novel_Representation_ICCV_2015_paper.pdf)

---

* **Hashmod**: Wadim Kehl, Federico Tombari, Nassir Navab, Slobodan Ilic, Vincent Lepetit.\
"Hashmod: A Hashing Method for Scalable 3D Object Detection." BMVC (2015)\
 [pdf](https://arxiv.org/abs/1607.06062)

* **Articulated Object Pose**: Frank Michel, Alexander Krull, Eric Brachmann, Michael Ying Yang, Stefan Gumhold and Carsten Rother.\
"Pose Estimation of Kinematic Chain Instances via Object Coordinate Regression." BMVC (2015)\
[pdf](http://wwwpub.zih.tu-dresden.de/~cvweb/publications/papers/2015/Pose_Estimation_of_Kinematic_Chain_Instances_via_Object_Coordinate_Regression-Michel-BMVC15.pdf)

---

* **Viewpoints & Keypoints**: Shubham Tulsiani and Jitendra Malik.\
"Viewpoints and Keypoints." CVPR (2015)\
[code](https://github.com/shubhtuls/ViewpointsAndKeypoints) | [pdf](https://arxiv.org/abs/1411.6067)

* **Learning Descriptor**: Paul Wohlhart, Vincent Lepetit.\
"Learning Descriptors for Object Recognition and 3D Pose Estimation." CVPR (2015)\
[code](https://github.com/paroj/ObjRecPoseEst) | [pdf](https://arxiv.org/abs/1502.05908)

 
### 2014

* **Latent-Class Hough Forests**: Alykhan Tejani, Danhang Tang, Rigas Kouskouridas, and Tae-Kyun Kim.\
"Latent-Class Hough Forests for 3D Object Detection and Pose Estimation." ECCV (2014)\
[pdf](https://labicvl.github.io/docs/pubs/Aly_ECCV_2014.pdf)

* **6D Pose and 3D Object Coordinates**: Eric Brachmann, Alexander Krull, Frank Michel, Stefan Gumhold, Jamie Shotton, Carsten Rother.\
"Learning 6D Object Pose Estimation using 3D Object Coordinates" ECCV (2014)\
[pdf](http://wwwpub.zih.tu-dresden.de/~cvweb/publications/papers/2014/PoseEstimationECCV2014.pdf)


### 2012

* **LINEMOD**: Stefan Hinterstoisser, Vincent Lepetit, Slobodan Ilic, Stefan Holzer, Gary Bradski, Kurt Konolige, Nassir Navab.\
"Model Based Training, Detection and Pose Estimation of Texture-Less 3D Objects in Heavily Cluttered Scenes." ACCV (2012)\
[pdf](https://icwww.epfl.ch/~lepetit/papers/hinterstoisser_accv12.pdf)


### 2010
* **Point-Pair Feature**: Bertram Drost, Markus Ulrich, Nassir Navab, Slobodan Ilic.\
"Model Globally, Match Locally: Efficient and Robust 3D Object Recognition." CVPR (2010)\
[pdf](http://campar.in.tum.de/pub/drost2010CVPR/drost2010CVPR.pdf)
 
 
## Other resources

 * [Papers with code 6d-pose-estimation](https://paperswithcode.com/task/6d-pose-estimation)
 * [Papers with code viewpoint-estimation](https://paperswithcode.com/task/viewpoint-estimation)
 * [Vision-based Robotic Grasping from Object Localization, Pose Estimation, Grasp
Detection to Motion Planning: A Review](https://arxiv.org/pdf/1905.06658v1.pdf)
 * [Instance- and Category-level 6D Object Pose Estimation](https://arxiv.org/abs/1903.04229)
