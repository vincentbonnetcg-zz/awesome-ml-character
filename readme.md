# Awesome ML Character 

> A collection of papers about characters generation with machine learning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)

## Contents

- [Parametric Model](#parametric-model)
- [Sparse Decomposition](#sparse-decomposition)
- [Avatar Creation](#avatar-creation)
- [Rigging](#rigging)
- [Deformation](#deformation)
- [Body Simulation](#body-simulation)
- [Cloth Simulation](#cloth-simulation)
- [Motion Controller](#motion-controller)
- [Motion Generation](#motion-generation)
- [Motion Inbetweening](#motion-inbetweening)
- [Motion Retargeting](#motion-retargeting)
- [Dataset Generation](#dataset-generation)
- [Datasets](#datasets)

## Parametric Model

**Learning a model of facial shape and expression from 4D scans.**<br>
*Li, Tianye, Timo Bolkart, Michael J. Black, Hao Li, and Javier Romero*<br>
2017. [[PDF](https://www.is.mpg.de/uploads_file/attachment/attachment/400/paper.pdf)]

**Building Statistical Shape Spaces for 3D Human Modeling.**<br>
*Pishchulin, Leonid, Stefanie Wuhrer, Thomas Helten, Christian Theobalt, and Bernt Schiele.*<br>
2017. [[PDF](https://arxiv.org/pdf/1503.05860)]

**SMPL: A skinned multi-person linear model.**<br>
*Loper, Matthew, Naureen Mahmood, Javier Romero, Gerard Pons-Moll, and Michael J. Black.*<br>
SIGGRAPH 2015. [[PDF](https://files.is.tue.mpg.de/black/papers/SMPL2015.pdf)][[Course](https://smpl-made-simple.is.tue.mpg.de/index.html)]

**Parametric modeling of 3D human body shape—A survey.**<br>
*Cheng, Zhi-Quan, Yin Chen, Ralph R. Martin, Tong Wu, and Zhan Song.*<br>
2015. [[Website](https://www.sciencedirect.com/science/article/abs/pii/S0097849317301929)]

**A Statistical Model of Human Pose and Body Shape.**<br>
*Hasler, Nils, Carsten Stoll, Martin Sunkel, Bodo Rosenhahn, and H‐P. Seidel.* <br>
2009. [[PDF](https://www.cs.princeton.edu/courses/archive/spr11/cos598A/pdfs/Hasler09.pdf)]

**SCAPE: Shape Completion and Animation of People.**<br>
*Anguelov, Dragomir, Praveen Srinivasan, Daphne Koller, Sebastian Thrun, Jim Rodgers, and James Davis.*<br>
SIGGRAPH 2005. [[PDF](https://ai.stanford.edu/~drago/Papers/shapecomp.pdf)]

**The space of human body shapes: reconstruction and parameterization from range scans.**<br>
*Allen, Brett, Brian Curless, and Zoran Popović.*<br>
2003. [[PDF](https://www.is.mpg.de/uploads_file/attachment/attachment/400/paper.pdf)]

**A morphable model for the synthesis of 3D faces.**<br>
*Blanz, Volker, and Thomas Vetter.*<br>
1999. [[PDF](https://www.face-rec.org/algorithms/3d_morph/morphmod2.pdf)]

## Sparse Decomposition

**Generating 3D faces using convolutional mesh autoencoders.**<br>
*Ranjan, Anurag, Timo Bolkart, Soubhik Sanyal, and Michael J. Black.*<br>
2018. [[PDF](https://arxiv.org/pdf/1807.10267.pdf)]

**Mesh-based Autoencoders for Localized Deformation Component Analysis.**<br>
*Tan, Qingyang, Lin Gao, Yu-Kun Lai, Jie Yang, and Shihong Xia*.<br>
2018.[[PDF](https://arxiv.org/pdf/1709.04304.pdf)]

**Sparse Data Driven Mesh Deformation.**<br>
*Lin Gao, Yu-Kun Lai, Jie Yang, Ling-Xiao Zhang, Leif Kobbelt, Shihong Xia.*<br>
2017. [[PDF](https://arxiv.org/pdf/1709.01250)]

**Linear Shape Deformation Models with Local Support using Graph-based Structured Matrix Factorisation.**<br>
*Bernard, Florian, Peter Gemmar, Frank Hertel, Jorge Goncalves, and Johan Thunberg.*<br>
2016. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Bernard_Linear_Shape_Deformation_CVPR_2016_paper.pdf)]

**Sparse Localized Decomposition of Deformation Gradients.**<br>
*Huang, Zhichao, Junfeng Yao, Zichun Zhong, Yang Liu, and Xiaohu Guo.*<br>
SPLOCS with deformation gradients<br>
2014. [[PDF](https://personal.utdallas.edu/~xxg061000/CGF14.pdf)]

**Sparse localized deformation components.**<br>
Introduces SPLOCS.<br>
*Neumann, Thomas, Kiran Varanasi, Stephan Wenger, Markus Wacker, Marcus Magnor, and Christian Theobalt.*<br>
2013. [[PDF](https://vcai.mpi-inf.mpg.de/files/splocs.pdf)]

## Avatar Creation

**SMPLpix: Neural Avatars from 3D Human Models.**<br>
*Prokudin, Sergey, Michael J. Black, and Javier Romero.*<br>
2021.  [[PDF](https://arxiv.org/pdf/2008.06872.pdf)][[GitHub](https://github.com/sergeyprokudin/smplpix)]

**Expressive body capture: 3d hands, face, and body from a single image.**<br>
*Pavlakos, Georgios, Vasileios Choutas, Nima Ghorbani, Timo Bolkart, Ahmed AA Osman, Dimitrios Tzionas, and Michael J. Black.*<br>
2019. [[PDF](https://arxiv.org/pdf/1904.05866.pdf)][[GitHub](https://github.com/vchoutas/smplify-x)]

## Rigging

**Learning Skeletal Articulations with Neural Blend Shapes.**<br>
*Li, Peizhuo, Kfir Aberman, Rana Hanocka, Libin Liu, Olga Sorkine-Hornung, and Baoquan Chen.*<br>
SIGGRAPH 2021. [[PDF](https://arxiv.org/pdf/2105.02451)]

**HeterSkinNet: A Heterogeneous Network for Skin Weights Prediction.**<br>
*Pan, Xiaoyu, Jiancong Huang, Jiaming Mai, He Wang, Honglin Li, Tongkui Su, Wenjun Wang, and Xiaogang Jin.*<br>
I3D 2021. [[PDF](https://arxiv.org/pdf/2103.10602)]

**Rignet: Neural rigging for articulated characters.**<br>
*Xu, Zhan, Yang Zhou, Evangelos Kalogerakis, Chris Landreth, and Karan Singh.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/pdf/2005.00559)]

**NiLBS: Neural Inverse Linear Blend Skinning.**<br>
*Jeruzalski, Timothy, David IW Levin, Alec Jacobson, Paul Lalonde, Mohammad Norouzi, and Andrea Tagliasacchi.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/pdf/2004.05980)]

## Deformation

**PBNS: Physically Based Neural Simulator for Unsupervised Garment Pose Space Deformation.**<br>
*Bertiche, Hugo, Meysam Madadi, and Sergio Escalera.*<br>
2020.[[PDF](https://arxiv.org/pdf/2012.11310)]

**Fast and deep deformation approximations.**<br>
*Bailey, Stephen W., Dave Otte, Paul Dilorenzo, and James F. O'Brien.*<br>
2018.[[PDF](https://research.dreamworks.com/wp-content/uploads/2018/08/Rig_Approximation-Edited.pdf)]

**Fast and deep facial deformations.**<br>
*Bailey, Stephen W., Dalton Omens, Paul Dilorenzo, and James F. O'Brien.*<br>
2020. [[PDF](http://graphics.berkeley.edu/papers/Bailey-FDF-2020-07/Bailey-FDF-2020-07.pdf)]

## Body Simulation

**SoftSMPL: Data-driven Modeling of Nonlinear Soft-tissue Dynamics for Parametric Humans.**<br>
*Santesteban, Igor, Elena Garces, Miguel A. Otaduy, and Dan Casas.*<br>
Eurographics 2020.[[PDF](https://arxiv.org/pdf/2004.00326)]


## Cloth Simulation

**Swish: Neural Network Cloth Simulation on Madden NFL 21.**<br>
*Lewin, Chris, James Power, and James Cobb.*<br>
2021.[[PDF](https://media.contentapi.ea.com/content/dam/ea/seed/presentations/seed-swish-cloth-simulation-madden-nfl.pdf)]

**TailorNet: Predicting Clothing in 3D as a Function of Human Pose, Shape and Garment Style.**<br>
*Patel, Chaitanya, Zhouyingcheng Liao, and Gerard Pons-Moll.*<br>
2020. [[PDF](https://arxiv.org/pdf/2003.04583)]

**Learning Mesh-Based Simulation with Graph Networks.**<br>
*Pfaff, Tobias, Meire Fortunato, Alvaro Sanchez-Gonzalez, and Peter W. Battaglia.*<br>
2020. [[PDF](https://arxiv.org/pdf/2010.03409)]

**Subspace neural physics: Fast data-driven interactive simulation.**<br>
*Holden, Daniel, Bang Chi Duong, Sayantan Datta, and Derek Nowrouzezahrai..*<br>
2020. [[PDF](http://cim.mcgill.ca/~derek/files/Deep-Cloth-paper.pdf)]

## Motion Controller

### Data-Driven Controller

**ProtoRes: Proto-Residual Architecture for Deep Modeling of Human Pose.**<br>
*Oreshkin, Boris N., Florent Bocquelet, Félix H. Harvey, Bay Raitt, and Dominic Laflamme.*<br>
2021. [[PDF](https://arxiv.org/pdf/2106.01981)][[Website](https://unity-technologies.github.io/Labs/protores.html)]

**Neural animation layering for synthesizing martial arts movements.**<br>
*Starke, Sebastian, Yiwei Zhao, Fabio Zinno, and Taku Komura.*<br>
2021. [[PDF](http://www.ipab.inf.ed.ac.uk/cgvu/starke2021.pdf)]

**AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control.**<br>
*Peng, Xue Bin, Ze Ma, Pieter Abbeel, Sergey Levine, and Angjoo Kanazawa.*<br>
2021. [[PDF](https://arxiv.org/pdf/2104.02180)]

**A GAN-Like Approach for Physics-Based Imitation Learning and Interactive Character Control.**<br>
*Xu, Pei, and Ioannis Karamouzas.*<br>
2021. [[PDF](https://arxiv.org/pdf/2105.10066)]

**Learned motion matching.**<br>
*Xu, Pei, and Ioannis Karamouzas.*<br>
2020. [[PDF](http://theorangeduck.com/media/uploads/other_stuff/Learned_Motion_Matching.pdf)]

**Local motion phases for learning multi-contact character movements.**<br>
*Starke, Sebastian, Yiwei Zhao, Taku Komura, and Kazi Zaman.*<br>
2020. [[PDF](https://www.pure.ed.ac.uk/ws/portalfiles/portal/157671564/Local_Motion_Phases_STARKE_DOA27042020_AFV.pdf)]

**Neural state machine for character-scene interactions.**<br>
*Starke, Sebastian, He Zhang, Taku Komura, and Jun Saito.*<br>
SIGGRAPH Asia 2019. [[PDF](https://www.pure.ed.ac.uk/ws/files/112627363/papers_168s4_file2.pdf)]

**Mode-adaptive neural networks for quadruped motion control .**<br>
*Zhang, He, Sebastian Starke, Taku Komura, and Jun Saito.*<br>
2018. [[PDF](https://www.pure.ed.ac.uk/ws/files/60838109/dog2.pdf)]

**Phase-functioned neural networks for character control.**<br>
*Holden, Daniel, Taku Komura, and Jun Saito.*<br>
2017. [[PDF](http://theorangeduck.com/media/uploads/other_stuff/phasefunction.pdf)]

### Physics-Based Controller

**CARL: Controllable Agent with Reinforcement Learning for Quadruped Locomotion.**<br>
*Luo, Ying-Sheng, Jonathan Hans Soeseno, Trista Pei-Chun Chen, and Wei-Chao Chen.*<br>
2020. [[PDF](https://arxiv.org/pdf/2005.03288)]

## Motion Generation

**From Motor Control to Team Play in Simulated Humanoid Football.**<br>
*Liu, Siqi, Guy Lever, Zhe Wang, Josh Merel, S. M. Eslami, Daniel Hennes, Wojciech M. Czarnecki et al.*<br>
2021.[[PDF](https://arxiv.org/pdf/2105.12196.pdf)]

**Deeploco: Dynamic locomotion skills using hierarchical deep reinforcement learning.**<br>
*Peng, Xue Bin, Glen Berseth, KangKang Yin, and Michiel Van De Panne.*<br>
2017.[[PDF](https://www.cs.ubc.ca/~van/papers/2017-TOG-deepLoco/2017-TOG-deepLoco.pdf)]

**Emergence of locomotion behaviours in rich environments.**<br>
*Heess, Nicolas, Dhruva TB, Srinivasan Sriram, Jay Lemmon, Josh Merel, Greg Wayne, Yuval Tassa et al..*<br>
2017.[[PDF](https://arxiv.org/pdf/1707.02286)]

**Flexible muscle-based locomotion for bipedal creatures.**<br>
*Geijtenbeek, Thomas, Michiel Van De Panne, and A. Frank Van Der Stappen*<br>
2013.[[PDF](https://www.cs.ubc.ca/~van/papers/2013-TOG-MuscleBasedBipeds/2013-TOG-MuscleBasedBipeds.pdf)]

## Motion Inbetweening

**Recurrent transition networks for character locomotion.**<br>
*Harvey, Félix G., and Christopher Pal*<br>
SIGGRAPH Asia 2018.[[PDF](https://arxiv.org/pdf/1810.02363)]

**Robust motion in-betweening.**<br>
*Harvey, Félix G., Mike Yurick, Derek Nowrouzezahrai, and Christopher Pal*<br>
SIGGRAPH 2020.[[PDF](https://arxiv.org/pdf/2102.04942)]

## Motion Retargeting

**Skeleton-Aware Networks for Deep Motion Retargeting.**<br>
*Aberman, Kfir, Peizhuo Li, Dani Lischinski, Olga Sorkine-Hornung, Daniel Cohen-Or, and Baoquan Chen*<br>
SIGGRAPH 2020.[[PDF](https://arxiv.org/pdf/2005.05732)]

## Dataset Generation

**Learning from Synthetic Humans.**<br>
*Varol, Gul, Javier Romero, Xavier Martin, Naureen Mahmood, Michael J. Black, Ivan Laptev, and Cordelia Schmid.*<br>
2017. [[PDF](https://arxiv.org/pdf/1701.01370.pdf)]

## Datasets

**LAFAN1 - Ubisoft La Forge Animation Dataset.**<br>
*Félix G. Harvey and Mike Yurick and Derek Nowrouzezahrai and Christopher Pal.*<br>
2020. [[Website](https://github.com/ubisoft/ubisoft-laforge-animation-dataset)]

**MPII Human Pose - 2D Human Pose Estimation: New Benchmark and State of the Art Analysis.**<br>
*Mykhaylo Andriluka and Leonid Pishchulin and Peter Gehler and Schiele, Bernt*.<br>
2014. [[Website](http://human-pose.mpi-inf.mpg.de/)]

**Human3.6M Large Scale Datasets and Predictive Methods for 3D Human Sensing in Natural Environments.**<br>
*Ionescu, Catalin, Dragos Papava, Vlad Olaru, and Cristian Sminchisescu.*<br>
2013. [[Website](http://vision.imar.ro/human3.6m/description.php)]

**HumanEva I/II**<br> 
*Ionescu, Catalin, Dragos Papava, Vlad Olaru, and Cristian Sminchisescu.*<br>
[[Website](http://humaneva.is.tue.mpg.de/)]

**Caesar**<br>
[[Website](https://humanshape.mpi-inf.mpg.de)]

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
