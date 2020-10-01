Shubham Tulsiani
================

* * * * *

+--------------------------------------+--------------------------------------+
| I will be joining the CMU School of  | ![My picture](img.jpg)               |
| Computer Science as an Assistant     |                                      |
| Professor in Fall 2021. I am         |                                      |
| currently a Research Scientist at    |                                      |
| [FAIR](https://research.fb.com/categ |                                      |
| ory/facebook-ai-research/),          |                                      |
| Pittsburgh working with [Abhinav     |                                      |
| Gupta](https://www.cs.cmu.edu/~abhin |                                      |
| avg/).                               |                                      |
| I previously graduated from UC,      |                                      |
| Berkeley where I was advised by      |                                      |
| [Jitendra                            |                                      |
| Malik](http://www.eecs.berkeley.edu/ |                                      |
| ~malik),                             |                                      |
| and also frequently collaborated     |                                      |
| with [Alyosha                        |                                      |
| Efros](http://www.eecs.berkeley.edu/ |                                      |
| ~efros).                             |                                      |
| \                                    |                                      |
|                                      |                                      |
| I am interested in building          |                                      |
| perception systems that can infer    |                                      |
| the spatial and physical structure   |                                      |
| of the world they observe. Please    |                                      |
| see [this recent                     |                                      |
| talk](https://youtu.be/lAZyzI-_omM?t |                                      |
| =108)                                |                                      |
| for an overview.                     |                                      |
| \                                    |                                      |
|                                      |                                      |
| [email](javascript:toggleblock('emai |                                      |
| l'))                                 |                                      |
| |                                    |                                      |
| [github](https://github.com/shubhtul |                                      |
| s)                                   |                                      |
| |                                    |                                      |
| [thesis](https://www2.eecs.berkeley. |                                      |
| edu/Pubs/TechRpts/2018/EECS-2018-93. |                                      |
| html)                                |                                      |
| | [google                            |                                      |
| scholar](https://scholar.google.com/ |                                      |
| citations?user=06rffEkAAAAJ&hl=en)   |                                      |
|                                      |                                      |
| ``` {#email xml:space="preserve" sty |                                      |
| le="font-size: 12px"}                |                                      |
|                                      |                                      |
| shubhtuls AT {cmu.edu (preferred), f |                                      |
| b.com}                               |                                      |
|                                      |                                      |
| ```                                  |                                      |
+--------------------------------------+--------------------------------------+

Publications
------------

\

\
2020

* * * * *

![](figures/cvpr20acsm.png)

**[New]** **Articulation-aware Canonical Surface Mapping** \
 Nilesh Kulkarni, Abhinav Gupta, David Fouhey, **Shubham Tulsiani** \
 CVPR, 2020 \
 [pdf](https://arxiv.org/pdf/2004.00614.pdf)   [project
page](https://nileshkulkarni.github.io/acsm/)  
[abstract](javascript:toggleblock('cvpr20acsmAbs'))  
[bibtex](javascript:toggleblock('cvpr20acsmBib'))  
[video](https://youtu.be/qgVwjkO2ltw)  
[code](http://www.github.com/nileshkulkarni/acsm/)

*We tackle the tasks of: 1) predicting a Canonical Surface Mapping (CSM)
that indicates the mapping from 2D pixels to corresponding points on a
canonical template shape , and 2) inferring the articulation and pose of
the template corresponding to the input image. While previous approaches
rely on leveraging keypoint supervision for learning, we present an
approach that can learn without such annotations. Our key insight is
that these tasks are geometrically related, and we can obtain
supervisory signal via enforcing consistency among the predictions. We
present results across a diverse set of animate object categories,
showing that our method can learn articulation and CSM prediction from
image collections using only foreground mask labels for training. We
empirically show that allowing articulation helps learn more accurate
CSM prediction, and that enforcing the consistency with predicted CSM is
similarly critical for learning meaningful articulation.*

``` {#cvpr20acsmBib xml:space="preserve"}

@inProceedings{kulkarni2020acsm,
  title={Articulation-aware Canonical Surface Mapping},
  author={Kulkarni, Nilesh and Gupta, Abhinav and Fouhey, David and Tulsiani, Shubham},
  year={2020},
  booktitle={Computer Vision and Pattern Recognition (CVPR)}
}
```

![](figures/cvpr20force.png)

**[New]** **Use the Force, Luke! Learning to Predict Physical Forces by
Simulating Effects** \
 Kiana Ehsani, **Shubham Tulsiani**, Saurabh Gupta, Ali Farhadi, Abhinav
Gupta \
 CVPR, 2020 \
 [pdf](https://arxiv.org/pdf/2003.12045.pdf)   [project
page](https://ehsanik.github.io/forcecvpr2020/)  
[abstract](javascript:toggleblock('cvpr20forceAbs'))  
[bibtex](javascript:toggleblock('cvpr20forceBib'))

*When we humans look at a video of human-object interaction, we can not
only infer what is happening but we can even extract actionable
information and imitate those interactions. On the other hand, current
recognition or geometric approaches lack the physicality of action
representation. In this paper, we take a step towards more physical
understanding of actions. We address the problem of inferring contact
points and the physical forces from videos of humans interacting with
objects. One of the main challenges in tackling this problem is
obtaining ground-truth labels for forces. We sidestep this problem by
instead using a physics simulator for supervision. Specifically, we use
a simulator to predict effects, and enforce that estimated forces must
lead to same effect as depicted in the video. Our quantitative and
qualitative results show that (a) we can predict meaningful forces from
videos whose effects lead to accurate imitation of the motions observed,
(b) by jointly optimizing for contact point and force prediction, we can
improve the performance on both tasks in comparison to independent
training, and (c) we can learn a representation from this model that
generalizes to novel objects using few shot examples.*

``` {#cvpr20forceBib xml:space="preserve"}

@inProceedings{ehsani2020force,
  title={Use the Force, Luke! Learning to Predict Physical Forces by Simulating Effects},
  author={Ehsani, Kiana and  Tulsiani, Shubham and Gupta, Saurabh and Farhadi, Ali and Gupta, Abhinav},
  year={2020},
  booktitle={Computer Vision and Pattern Recognition (CVPR)}
}
```

![](figures/iclr20synergy.png)

**[New]** **Intrinsic Motivation for Encouraging Synergistic Behavior**
\
 Rohan Chitnis, **Shubham Tulsiani**, Saurabh Gupta, Abhinav Gupta \
 ICLR, 2020 \
 [pdf](https://openreview.net/pdf?id=SJleNCNtDH)   [project
page](https://sites.google.com/view/iclr2020-synergistic)  
[abstract](javascript:toggleblock('iclr20synergyAbs'))  
[bibtex](javascript:toggleblock('iclr20synergyBib'))

*We study the role of intrinsic motivation as an exploration bias for
reinforcement learning in sparse-reward synergistic tasks, which are
tasks where multiple agents must work together to achieve a goal they
could not individually. Our key idea is that a good guiding principle
for intrinsic motivation in synergistic tasks is to take actions which
affect the world in ways that would not be achieved if the agents were
acting on their own. Thus, we propose to incentivize agents to take
(joint) actions whose effects cannot be predicted via a composition of
the predicted effect for each individual agent. We study two
instantiations of this idea, one based on the true states encountered,
and another based on a dynamics model trained concurrently with the
policy. While the former is simpler, the latter has the benefit of being
analytically differentiable with respect to the action taken. We
validate our approach in robotic bimanual manipulation tasks with sparse
rewards; we find that our approach yields more efficient learning than
both 1) training with only the sparse reward and 2) using the typical
surprise-based formulation of intrinsic motivation, which does not bias
toward synergistic behavior.*

``` {#iclr20synergyBib xml:space="preserve"}

@inproceedings{chitnis20synergy,
  title={Intrinsic Motivation for Encouraging Synergistic Behavior},
  author={Chitnis, Rohan and Tulsiani, Shubham and Gupta, Saurabh and Gupta, Abhinav},
  booktitle={ICLR},
  year={2020}
}
```

![](figures/iclr20motor.png)

**[New]** **Discovering Motor Programs by Recomposing Demonstrations** \
 Tanmay Shankar, **Shubham Tulsiani**, Lerrel Pinto, Abhinav Gupta \
 ICLR, 2020 \
 [pdf](https://openreview.net/pdf?id=rkgHY0NYwr)  
[abstract](javascript:toggleblock('iclr20motorAbs'))  
[bibtex](javascript:toggleblock('iclr20motorBib'))

*We learn a space of motor primitives from unannotated robot
demonstrations, and show these primitives are semantically meaningful
and can be composed for new robot tasks. Abstract: In this paper, we
present an approach to learn recomposable motor primitives across
large-scale and diverse manipulation demonstrations. Current approaches
to decomposing demonstrations into primitives often assume manually
defined primitives and bypass the difficulty of discovering these
primitives. On the other hand, approaches in primitive discovery put
restrictive assumptions on the complexity of a primitive, which limit
applicability to narrow tasks. Our approach attempts to circumvent these
challenges by jointly learning both the underlying motor primitives and
recomposing these primitives to form the original demonstration. Through
constraints on both the parsimony of primitive decomposition and the
simplicity of a given primitive, we are able to learn a diverse set of
motor primitives, as well as a coherent latent representation for these
primitives. We demonstrate, both qualitatively and quantitatively, that
our learned primitives capture semantically meaningful aspects of a
demonstration. This allows us to compose these primitives in a
hierarchical reinforcement learning setup to efficiently solve robotic
manipulation tasks like reaching and pushing.*

``` {#iclr20motorBib xml:space="preserve"}

@inproceedings{shankar20motor,
  title={Discovering Motor Programs by Recomposing Demonstrations},
  author={Shankar, Tanmay and Tulsiani, Shubham and Pinto, Lerrel and Gupta, Abhinav},
  booktitle={ICLR},
  year={2020}
}
```

![](figures/icra20schema.png)

**[New]** **Efficient Bimanual Manipulation using Learned Task Schemas**
\
 Rohan Chitnis, **Shubham Tulsiani**, Saurabh Gupta, Abhinav Gupta \
 ICRA, 2020 \
 [preprint](https://arxiv.org/pdf/1909.13874.pdf)  
[abstract](javascript:toggleblock('icra20schemaAbs'))  
[bibtex](javascript:toggleblock('icra20schemaBib'))  
[video](https://www.youtube.com/watch?v=TBUEHk37a64)

*We address the problem of effectively composing skills to solve
sparse-reward tasks in the real world. Given a set of parameterized
skills (such as exerting a force or doing a top grasp at a location),
our goal is to learn policies that invoke these skills to efficiently
solve such tasks. Our insight is that for many tasks, the learning
process can be decomposed into learning a state-independent task schema
(a sequence of skills to execute) and a policy to choose the
parameterizations of the skills in a state-dependent manner. For such
tasks, we show that explicitly modeling the schema's state-independence
can yield significant improvements in sample efficiency for model-free
reinforcement learning algorithms. Furthermore, these schemas can be
transferred to solve related tasks, by simply re-learning the
parameterizations with which the skills are invoked. We find that doing
so enables learning to solve sparse-reward tasks on real-world robotic
systems very efficiently. We validate our approach experimentally over a
suite of robotic bimanual manipulation tasks, both in simulation and on
real hardware.*

``` {#icra20schemaBib xml:space="preserve"}

@inproceedings{chitnis20schema,
  title={Efficient Bimanual Manipulation Using Learned Task Schemas},
  author={Chitnis, Rohan and Tulsiani, Shubham and Gupta, Saurabh and Gupta, Abhinav},
  booktitle={ICRA},
  year={2020}
}
```

\
2019

* * * * *

![](figures/corl19ocm.png)

**Object-centric Forward Modeling for Model Predictive Control** \
 Yufei Ye, Dhiraj Gandhi, Abhinav Gupta, **Shubham Tulsiani** \
 CORL, 2019 \
 [pdf](https://arxiv.org/pdf/1910.03568.pdf)   [project
page](https://judyye.github.io/ocmpc/)  
[abstract](javascript:toggleblock('corl19ocmAbs'))  
[bibtex](javascript:toggleblock('corl19ocmBib'))

*We present an approach to learn an object-centric forward model, and
show that this allows us to plan for sequences of actions to achieve
distant desired goals. We propose to model a scene as a collection of
objects, each with an explicit spatial location and implicit visual
feature, and learn to model the effects of actions using random
interaction data. Our model allows capturing the robot-object and
object-object interactions, and leads to more sample-efficient and
accurate predictions. We show that this learned model can be leveraged
to search for action sequences that lead to desired goal configurations,
and that in conjunction with a learned correction module, this allows
for robust closed loop execution. We present experiments both in
simulation and the real world, and show that our approach improves over
alternate implicit or pixel-space forward models.*

``` {#corl19ocmBib xml:space="preserve"}

@inProceedings{ye2019ocm,
  title={Object-centric Forward Modeling for Model Predictive Control},
  author={Ye, Yufei and Gandhi, Dhiraj and Gupta, Abhinav and Tulsiani, Shubham},
  year={2019},
  booktitle={Conference on Robot Learning (CORL)}
}
```

![](figures/iccv19csm.png)

**Canonical Surface Mapping via Geometric Cycle Consistency** \
 Nilesh Kulkarni, Abhinav Gupta\*, **Shubham Tulsiani**\* \
 ICCV, 2019 \
 [pdf](https://arxiv.org/pdf/1907.10043.pdf)   [project
page](https://nileshkulkarni.github.io/csm/)  
[abstract](javascript:toggleblock('iccv19csmAbs'))  
[bibtex](javascript:toggleblock('iccv19csmBib'))  
[video](https://www.youtube.com/watch?v=93M3ou4mg-w)  
[code](https://github.com/nileshkulkarni/csm)

*We explore the task of Canonical Surface Mapping (CSM). Specifically,
given an image, we learn to map pixels on the object to their
corresponding locations on an abstract 3D model of the category. But how
do we learn such a mapping? A supervised approach would require
extensive manual labeling which is not scalable beyond a few hand-picked
categories. Our key insight is that the CSM task (pixel to 3D), when
combined with 3D projection (3D to pixel), completes a cycle. Hence, we
can exploit a geometric cycle consistency loss, thereby allowing us to
forgo the dense manual supervision. Our approach allows us to train a
CSM model for a diverse set of classes, without sparse or dense keypoint
annotation, by leveraging only foreground mask labels for training. We
show that our predictions also allow us to infer dense correspondence
between two images, and compare the performance of our approach against
several methods that predict correspondence by leveraging varying amount
of supervision.*

``` {#iccv19csmBib xml:space="preserve"}

@inProceedings{kulkarni2019csm,
  title={Canonical Surface Mapping via Geometric Cycle Consistency},
  author={Kulkarni, Nilesh and Gupta, Abhinav and Tulsiani, Shubham},
  year={2019},
  booktitle={International Conference on Computer Vision (ICCV)}
}
```

![](figures/iccv19cvp_static.png)

**Compositional Video Prediction** \
 Yufei Ye, Maneesh Singh, Abhinav Gupta\*, **Shubham Tulsiani**\* \
 ICCV, 2019 \
 [pdf](https://arxiv.org/pdf/1908.08522.pdf)   [project
page](https://judyye.github.io/CVP/)  
[abstract](javascript:toggleblock('iccv19cvpAbs'))  
[bibtex](javascript:toggleblock('iccv19cvpBib'))  
[code](https://github.com/JudyYe/CVP)

*We present an approach for pixel-level future prediction given an input
image of a scene. We observe that a scene is comprised of distinct
entities that undergo motion and present an approach that
operationalizes this insight. We implicitly predict future states of
independent entities while reasoning about their interactions, and
compose future video frames using these predicted states. We overcome
the inherent multi-modality of the task using a global trajectory-level
latent random variable, and show that this allows us to sample diverse
and plausible futures. We empirically validate our approach against
alternate representations and ways of incorporating multi-modality. We
examine two datasets, one comprising of stacked objects that may fall,
and the other containing videos of humans performing activities in a
gym, and show that our approach allows realistic stochastic video
prediction across these diverse settings.*

``` {#iccv19cvpBib xml:space="preserve"}

@inProceedings{ye2019cvp,
  title={Compositional Video Prediction},
  author={Ye, Yufei and Singh, Maneesh and Gupta, Abhinav and Tulsiani, Shubham},
  year={2019},
  booktitle={International Conference on Computer Vision (ICCV)}
}
```

![](figures/iccv19relnet.png)

**3D-RelNet: Joint Object and Relational Network for 3D Prediction** \
 Nilesh Kulkarni, Ishan Misra, **Shubham Tulsiani**, Abhinav Gupta \
 ICCV, 2019 \
 [pdf](https://arxiv.org/pdf/1906.02729)   [project
page](https://nileshkulkarni.github.io/relative3d/)  
[abstract](javascript:toggleblock('iccv19relnetAbs'))  
[bibtex](javascript:toggleblock('iccv19relnetBib'))  
[code](https://github.com/nileshkulkarni/relative3d)

*We propose an approach to predict the 3D shape and pose for the objects
present in a scene. Existing learning based methods that pursue this
goal make independent predictions per object, and do not leverage the
relationships amongst them. We argue that reasoning about these
relationships is crucial, and present an approach to incorporate these
in a 3D prediction framework. In addition to independent per-object
predictions, we predict pairwise relations in the form of relative 3D
pose, and demonstrate that these can be easily incorporated to improve
object level estimates. We report performance across different datasets
(SUNCG, NYUv2), and show that our approach significantly improves over
independent prediction approaches while also outperforming alternate
implicit reasoning methods.*

``` {#iccv19relnetBib xml:space="preserve"}

@inProceedings{kulkarni2019relnet,
  title={3D-RelNet: Joint Object and Relational Network for 3D Prediction},
  author={Nilesh Kulkarni, Ishan Misra, Shubham Tulsiani, Abhinav Gupta},
  booktitle={ICCV},
  year={2019}
}
```

![](figures/iccv19craft.png)

**Order-Aware Generative Modeling Using the 3D-Craft Dataset** \
 Zhuoyuan Chen\*, Demi Guo\*, Tong Xiao\*, et. al. \
 ICCV, 2019 \

[pdf](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Order-Aware_Generative_Modeling_Using_the_3D-Craft_Dataset_ICCV_2019_paper.pdf)
  [abstract](javascript:toggleblock('iccv19craftAbs'))  
[bibtex](javascript:toggleblock('iccv19craftBib'))

*In this paper, we study the problem of sequentially building houses in
the game of Minecraft, and demonstrate that learning the ordering can
make for more effective autoregressive models. Given a partially built
house made by a human player, our system tries to place additional
blocks in a human-like manner to complete the house. We introduce a new
dataset, HouseCraft, for this new task. HouseCraft contains the
sequential order in which 2,500 Minecraft houses were built from scratch
by humans. The human action sequences enable us to learn an order-aware
generative model called Voxel-CNN. In contrast to many generative models
where the sequential generation ordering either does not matter (e.g.
holistic generation with GANs), or is manually/arbitrarily set by simple
rules (e.g. raster-scan order), our focus is on an ordered generation
that imitates humans. To evaluate if a generative model can accurately
predict human-like actions, we propose several novel quantitative
metrics. We demonstrate that our Voxel-CNN model is simple and effective
at this creative task, and can serve as a strong baseline for future
research in this direction.*

``` {#iccv19craftBib xml:space="preserve"}

@inProceedings{chen2019craft,
  title={Order-Aware Generative Modeling Using the 3D-Craft Dataset},
  author={Zhuoyuan Chen, Demi Guo, Tong Xiao, Saining Xie, Xinlei Chen, Haonan Yu, Jonathan Gray, Kavya Srinet, Haoqi Fan, Jerry Ma, Charles R. Qi, Shubham Tulsiani, Arthur Szlam, and C. Lawrence Zitnick},
  booktitle={ICCV},
  year={2019}
}
```

![](figures/pami19drc.png)

**Multi-view Supervision for Single-view Reconstruction via
Differentiable Ray Consistency** \
 **Shubham Tulsiani**, Tinghui Zhou, Alexei A. Efros, Jitendra Malik \
 TPAMI, 2019 (journal version combining
[DRC](https://shubhtuls.github.io/drc/) and
[MVC](https://shubhtuls.github.io/mvcSnP/)) \
 [pdf](papers/pami19drc.pdf)  
[abstract](javascript:toggleblock('pami19drcAbs'))  
[bibtex](javascript:toggleblock('pami19drcBib'))  
[code](https://github.com/shubhtuls/drc)

*We study the notion of consistency between a 3D shape and a 2D
observation and propose a differentiable formulation which allows
computing gradients of the 3D shape given an observation from an
arbitrary view. We do so by reformulating view consistency using a
differentiable ray consistency (DRC) term. We show that this formulation
can be incorporated in a learning framework to leverage different types
of multi-view observations e.g. foreground masks, depth, color images,
semantics etc. as supervision for learning single-view 3D prediction. We
present empirical analysis of our technique in a controlled setting. We
also show that this approach allows us to improve over existing
techniques for single-view reconstruction of objects from the PASCAL VOC
dataset.*

``` {#pami19drcBib xml:space="preserve"}

@article{drcTulsiani19,
  title={Multi-view Supervision for Single-view Reconstruction
  via Differentiable Ray Consistency},
  author = {Shubham Tulsiani
  and Tinghui Zhou
  and Alexei A. Efros
  and Jitendra Malik},
  journal = {TPAMI},
  year = {2019},
}
```

![](figures/pami19hsp.png)

**Hierarchical Surface Prediction** \
 Christian Häne, **Shubham Tulsiani**, Jitendra Malik \
 TPAMI, 2019 (journal version of
[HSP](https://arxiv.org/pdf/1704.00710.pdf)) \
 [pdf](papers/pami19hsp.pdf)  
[abstract](javascript:toggleblock('pami19hspAbs'))  
[bibtex](javascript:toggleblock('pami19hspBib'))  
[code](https://github.com/chaene/hsp)

*Recently, Convolutional Neural Networks have shown promising results
for 3D geometry prediction. They can make predictions from very little
input data such as a single color image. A major limitation of such
approaches is that they only predict a coarse resolution voxel grid,
which does not capture the surface of the objects well. We propose a
general framework, called hierarchical surface prediction (HSP), which
facilitates prediction of high resolution voxel grids. The main insight
is that it is sufficient to predict high resolution voxels around the
predicted surfaces. The exterior and interior of the objects can be
represented with coarse resolution voxels. This allows us to predict
significantly higher resolution voxel grids around the surface, from
which triangle meshes can be extracted. Additionally it allows us to
predict properties such as surface color which are only defined on the
surface. Our approach is not dependent on a specific input type. We show
results for geometry prediction from color images and depth images. Our
analysis shows that our high resolution predictions are more accurate
than low resolution predictions.*

``` {#pami19hspBib xml:space="preserve"}

@article{hspHane19,
  author = {Christian H{\"a}ne and
  Shubham Tulsiani and
  Jitendra Malik},
  title = {Hierarchical Surface Prediction},
  journal = {TPAMI},
  year = {2019},
}
```

\
2018

* * * * *

![](https://shubhtuls.github.io/lsi/resources/images/teaser.png)

**Layer-structured 3D Scene Inference via View Synthesis** \
 **Shubham Tulsiani**, Richard Tucker, Noah Snavely \
 ECCV, 2018 \
 [pdf](https://arxiv.org/pdf/1807.10264.pdf)   [project
page](https://shubhtuls.github.io/lsi/)  
[abstract](javascript:toggleblock('eccv18lsiAbs'))  
[bibtex](javascript:toggleblock('eccv18lsiBib'))  
[code](https://github.com/google/layered-scene-inference)

*We present an approach to infer a layer-structured 3D representation of
a scene from a single input image. This allows us to infer not only the
depth of the visible pixels, but also capture the texture and depth for
content in the scene that is not directly visible. We overcome the
challenge posed by the lack of direct supervision by instead leveraging
a more naturally available multi-view supervisory signal. Our insight is
to use view synthesis as a proxy task: we enforce that our
representation (inferred via a single image), when rendered from a novel
perspective, matches the true observation. We present a learning
framework that operationalizes this insight using a new, differentiable
novel view renderer. We provide qualitative and quantitative validation
of our approach in two different settings, and demonstrate that we can
learn to capture the hidden aspects of a scene.*

``` {#eccv18lsiBib xml:space="preserve"}

@inProceedings{lsiTulsiani18,
  title={Layer-structured 3D Scene Inference via View Synthesis},
  author = {Shubham Tulsiani
  and Richard Tucker
  and Noah Snavely},
  booktitle={ECCV},
  year={2018}
}
```

![](figures/arxiv18cmr.png)

**Learning Category-Specific Mesh Reconstruction from Image
Collections** \
 Angjoo Kanazawa\*, **Shubham Tulsiani**\*, Alexei A. Efros, Jitendra
Malik \
 ECCV, 2018 \
 [pdf](https://arxiv.org/pdf/1803.07549.pdf)   [project
page](https://akanazawa.github.io/cmr/)  
[abstract](javascript:toggleblock('eccv18cmrAbs'))  
[bibtex](javascript:toggleblock('eccv18cmrBib'))  
[video](https://youtu.be/cYHQKtBLI3Q)  
[code](https://github.com/akanazawa/cmr)

*We present a learning framework for recovering the 3D shape, camera,
and texture of an object from a single image. The shape is represented
as a deformable 3D mesh model of an object category where a shape is
parameterized by a learned mean shape and per-instance predicted
deformation. Our approach allows leveraging an annotated image
collection for training, where the deformable model and the 3D
prediction mechanism are learned without relying on ground-truth 3D or
multi-view supervision. Our representation enables us to go beyond
existing 3D prediction approaches by incorporating texture inference as
prediction of an image in a canonical appearance space. Additionally, we
show that semantic keypoints can be easily associated with the predicted
shapes. We present qualitative and quantitative results of our approach
on the CUB dataset, and show that we can learn to predict the diverse
shapes and textures across birds using only an annotated image
collection. We also demonstrate the the applicability of our method for
learning the 3D structure of other generic categories.*

``` {#eccv18cmrBib xml:space="preserve"}

@inProceedings{cmrKanazawa18,
  title={Learning Category-Specific Mesh Reconstruction
  from Image Collections},
  author = {Angjoo Kanazawa and
  Shubham Tulsiani
  and Alexei A. Efros
  and Jitendra Malik},
  booktitle={ECCV},
  year={2018}
}
```

![](figures/arxiv18mvc.png)

**Multi-view Consistency as Supervisory Signal for Learning Shape and
Pose Prediction** \
 **Shubham Tulsiani**, Alexei A. Efros, Jitendra Malik \
 CVPR, 2018 \
 [pdf](https://arxiv.org/pdf/1801.03910.pdf)   [project
page](https://shubhtuls.github.io/mvcSnP/)  
[abstract](javascript:toggleblock('cvpr18mvcAbs'))  
[bibtex](javascript:toggleblock('cvpr18mvcBib'))  
[code](https://github.com/shubhtuls/mvcSnP)

*We present a framework for learning single-view shape and pose
prediction without using direct supervision for either. Our approach
allows leveraging multi-view observations from unknown poses as
supervisory signal during training. Our proposed training setup enforces
geometric consistency between the independently predicted shape and pose
from two views of the same instance. We consequently learn to predict
shape in an emergent canonical (view-agnostic) frame along with a
corresponding pose predictor. We show empirical and qualitative results
using the ShapeNet dataset and observe encouragingly competitive
performance to previous techniques which rely on stronger forms of
supervision. We also demonstrate the applicability of our framework in a
realistic setting which is beyond the scope of existing techniques:
using a training dataset comprised of online product images where the
underlying shape and pose are unknown.*

``` {#cvpr18mvcBib xml:space="preserve"}

@inProceedings{mvcTulsiani18,
  title={Multi-view Consistency as Supervisory Signal
  for Learning Shape and Pose Prediction},
  author = {Shubham Tulsiani
  and Alexei A. Efros
  and Jitendra Malik},
  booktitle={Computer Vision and Pattern Recognition (CVPR)},
  year={2018}
}
```

![](https://shubhtuls.github.io/factored3d/resources/images/teaser.png)

**Factoring Shape, Pose, and Layout from the 2D Image of a 3D Scene** \
 **Shubham Tulsiani**, Saurabh Gupta, David Fouhey, Alexei A. Efros,
Jitendra Malik \
 CVPR, 2018 \
 [pdf](https://arxiv.org/pdf/1712.01812.pdf)   [project
page](https://shubhtuls.github.io/factored3d/)  
[abstract](javascript:toggleblock('cvpr18f3dAbs'))  
[bibtex](javascript:toggleblock('cvpr18f3dBib'))  
[code](https://github.com/shubhtuls/factored3d)

*The goal of this work is to take a single 2D image of a scene and
recover the 3D structure in terms of a small set of factors: a layout
representing the enclosing surfaces as well as a set of objects
represented in terms of shape and pose. We propose a convolutional
neural network-based approach to predict this representation and
benchmark it on a large dataset of indoor scenes. Our experiments
evaluate a number of practical design questions, demonstrate that we can
infer this representation, and quantitatively and qualitatively
demonstrate its merits compared to alternate representations.*

``` {#cvpr18f3dBib xml:space="preserve"}

@inProceedings{factored3dTulsiani17,
  title={Factoring Shape, Pose, and Layout from the 2D Image of a 3D Scene},
  author = {Shubham Tulsiani
  and Saurabh Gupta
  and David Fouhey
  and Alexei A. Efros
  and Jitendra Malik},
  booktitle={Computer Vision and Pattern Recognition (CVPR)},
  year={2018}
}
```

\
2017

* * * * *

![](figures/cvpr17drc.png)

**Multi-view Supervision for Single-view Reconstruction via
Differentiable Ray Consistency** \
 **Shubham Tulsiani**, Tinghui Zhou, Alexei A. Efros, Jitendra Malik \
 CVPR, 2017 \
 [pdf](https://arxiv.org/pdf/1704.06254.pdf)   [project
page](https://shubhtuls.github.io/drc/)  
[abstract](javascript:toggleblock('cvpr17drcAbs'))  
[bibtex](javascript:toggleblock('cvpr17drcBib'))  
[slides](https://people.eecs.berkeley.edu/~shubhtuls/slides/cvpr17drc.pdf)
  [talk](https://www.youtube.com/watch?v=i--alz5-lTc)  
[code](https://github.com/shubhtuls/drc)   [blog
post](http://bair.berkeley.edu/blog/2017/07/11/confluence-of-geometry-and-learning/)

*We study the notion of consistency between a 3D shape and a 2D
observation and propose a differentiable formulation which allows
computing gradients of the 3D shape given an observation from an
arbitrary view. We do so by reformulating view consistency using a
differentiable ray consistency (DRC) term. We show that this formulation
can be incorporated in a learning framework to leverage different types
of multi-view observations e.g. foreground masks, depth, color images,
semantics etc. as supervision for learning single-view 3D prediction. We
present empirical analysis of our technique in a controlled setting. We
also show that this approach allows us to improve over existing
techniques for single-view reconstruction of objects from the PASCAL VOC
dataset.*

``` {#cvpr17drcBib xml:space="preserve"}

@inProceedings{drcTulsiani17,
  title={Multi-view Supervision for Single-view Reconstruction
  via Differentiable Ray Consistency},
  author = {Shubham Tulsiani
  and Tinghui Zhou
  and Alexei A. Efros
  and Jitendra Malik},
  booktitle={Computer Vision and Pattern Recognition (CVPR)},
  year={2017}
}
```

![](https://shubhtuls.github.io/volumetricPrimitives/resources/images/teaser.png)

**Learning Shape Abstractions by Assembling Volumetric Primitives** \
 **Shubham Tulsiani**, Hao Su, Leonidas J. Guibas, Alexei A. Efros,
Jitendra Malik \
 CVPR, 2017 \
 [pdf](https://arxiv.org/pdf/1612.00404.pdf)   [project
page](https://shubhtuls.github.io/volumetricPrimitives/)  
[abstract](javascript:toggleblock('cvpr17abstractionAbs'))  
[bibtex](javascript:toggleblock('cvpr17abstractionBib'))   [code
(torch)](https://github.com/shubhtuls/volumetricPrimitives)   [code
(pytorch -
unofficial)](https://github.com/nileshkulkarni/volumetricPrimitivesPytorch)

*We present a learning framework for abstracting complex shapes by
learning to assemble objects using 3D volumetric primitives. In addition
to generating simple and geometrically interpretable explanations of 3D
objects, our framework also allows us to automatically discover and
exploit consistent structure in the data. We demonstrate that using our
method allows predicting shape representations which can be leveraged
for obtaining a consistent parsing across the instances of a shape
collection and constructing an interpretable shape similarity measure.
We also examine applications for image-based prediction as well as shape
manipulation.*

``` {#cvpr17abstractionBib xml:space="preserve"}

@inProceedings{abstractionTulsiani17,
  title={Learning Shape Abstractions by Assembling Volumetric Primitives},
  author = {Shubham Tulsiani
  and Hao Su
  and Leonidas J. Guibas
  and Alexei A. Efros
  and Jitendra Malik},
  booktitle={Computer Vision and Pattern Recognition (CVPR)},
  year={2017}
}
```

![](figures/iccv17hsp.png)

**Hierarchical Surface Prediction for 3D Object Reconstruction** \
 Christian Häne, **Shubham Tulsiani**, Jitendra Malik \
 3DV, 2017 \
 [pdf](https://arxiv.org/pdf/1704.00710.pdf)  
[abstract](javascript:toggleblock('3dv17hspAbs'))  
[bibtex](javascript:toggleblock('3dv17hspBib'))  
[slides](https://people.eecs.berkeley.edu/~chaene/publications/haene2017hspICCVTalk.pdf)
  [code](https://github.com/chaene/hsp)

*Recently, Convolutional Neural Networks have shown promising results
for 3D geometry prediction. They can make predictions from very little
input data such as for example a single color image, depth map or a
partial 3D volume. A major limitation of such approaches is that they
only predict a coarse resolution voxel grid, which does not capture the
surface of the objects well. We propose a general framework, called
hierarchical surface prediction (HSP), which facilitates prediction of
high resolution voxel grids. The main insight is that it is sufficient
to predict high resolution voxels around the predicted surfaces. The
exterior and interior of the objects can be represented with coarse
resolution voxels. This allows us to predict significantly higher
resolution voxel grids around the surface, from which triangle meshes
can be extracted. Our approach is general and not dependent on a
specific input type. In our experiments we show results for geometry
prediction from color images, depth images and shape completion from
partial voxel grids. Our analysis shows that the network is able to
predict the surface more accurately than a low resolution prediction.*

``` {#3dv17hspBib xml:space="preserve"}

@incollection{hspHane17,
  author = {Christian H{\"a}ne and
  Shubham Tulsiani and
  Jitendra Malik},
  title = {Hierarchical Surface Prediction for 3D Object Reconstruction},
  booktitle = {arXiv preprint arXiv:1704.00710},
  year = {2017}
}
```

\
2016

* * * * *

![](figures/pami16reconstruction.png)

**Learning Category-Specific Deformable 3D Models for Object
Reconstruction** \
 **Shubham Tulsiani**\*, Abhishek Kar\*, João Carreira, Jitendra Malik \
 TPAMI, 2016 \
 [pdf](papers/pami16reconstruction.pdf)  
[abstract](javascript:toggleblock('pami16reconstructionAbs'))  
[bibtex](javascript:toggleblock('pami16reconstructionBib'))  
[code](https://github.com/akar43/CategoryShapes)

*We address the problem of fully automatic object localization and
reconstruction from a single image. This is both a very challenging and
very important problem which has, until recently, received limited
attention due to difficulties in segmenting objects and predicting their
poses. Here we leverage recent advances in learning convolutional
networks for object detection and segmentation and introduce a
complementary network for the task of camera viewpoint prediction. These
predictors are very powerful, but still not perfect given the stringent
requirements of shape reconstruction. Our main contribution is a new
class of deformable 3D models that can be robustly fitted to images
based on noisy pose and silhouette estimates computed upstream and that
can be learned directly from 2D annotations available in object
detection datasets. Our models capture top-down information about the
main global modes of shape variation within a class providing a
\`\`low-frequency'' shape. In order to capture fine instance-specific
shape details, we fuse it with a high-frequency component recovered from
shading cues. A comprehensive quantitative analysis and ablation study
on the PASCAL 3D+ dataset validates the approach as we show fully
automatic reconstructions on PASCAL VOC as well as large improvements on
the task of viewpoint prediction.*

``` {#pami16reconstructionBib xml:space="preserve"}

@article{pamishapeTulsianiKCM15,
  author = {Shubham Tulsiani and
  Abhishek Kar and
  Jo{\~{a}}o Carreira and
  Jitendra Malik},
  title = {Learning Category-Specific Deformable 3D
  Models for Object Reconstruction},
  journal = {TPAMI},
  year = {2016},
}
```

![](figures/arxiv16flow.png)

**View Synthesis by Appearance Flow** \
 Tinghui Zhou, **Shubham Tulsiani**, Weilun Sun, Jitendra Malik, Alexei
A. Efros \
 ECCV, 2016 \
 [pdf](http://arxiv.org/pdf/1605.03557v2.pdf)  
[abstract](javascript:toggleblock('eccv16flowAbs'))  
[bibtex](javascript:toggleblock('eccv16flowBib'))  
[code](https://github.com/tinghuiz/appearance-flow)

*Given one or more images of an object (or a scene), is it possible to
synthesize a new image of the same instance observed from an arbitrary
viewpoint? In this paper, we attempt to tackle this problem, known as
novel view synthesis, by re-formulating it as a pixel copying task that
avoids the notorious difficulties of generating pixels from scratch. Our
approach is built on the observation that the visual appearance of
different views of the same instance is highly correlated. Such
correlation could be explicitly learned by training a convolutional
neural network (CNN) to predict \\emph{appearance flows} -- 2-D
coordinate vectors specifying which pixels in the input view could be
used to reconstruct the target view. We show that for both objects and
scenes, our approach is able to generate higher-quality synthesized
views with crisp texture and boundaries than previous CNN-based
techniques.*

``` {#eccv16flowBib xml:space="preserve"}

@incollection{appFlowZhou16,
author = {Tinghui Zhou and
Shubham Tulsiani and
Weilun Sun and
Jitendra Malik and
Alexei A. Efros},
title = {View Synthesis by Appearance Flow},
booktitle = {ECCV},
year = {2016}
}
```

\
2015

* * * * *

![](figures/iccv15poseInd.png)

**Pose Induction for Novel Object Categories** \
 **Shubham Tulsiani**, João Carreira, Jitendra Malik \
 ICCV, 2015 \
 [pdf](https://arxiv.org/pdf/1505.00066.pdf)  
[abstract](javascript:toggleblock('iccv15poseAbs'))  
[bibtex](javascript:toggleblock('iccv15poseBib'))  
[code](https://github.com/shubhtuls/poseInduction)

*We address the task of predicting pose for objects of unannotated
object categories from a small seed set of annotated object classes. We
present a generalized classifier that can reliably induce pose given a
single instance of a novel category. In case of availability of a large
collection of novel instances, our approach then jointly reasons over
all instances to improve the initial estimates. We empirically validate
the various components of our algorithm and quantitatively show that our
method produces reliable pose estimates. We also show qualitative
results on a diverse set of classes and further demonstrate the
applicability of our system for learning shape models of novel object
classes.*

``` {#iccv15poseBib xml:space="preserve"}

@inProceedings{poseInductionTCM15,
  author    = {Shubham Tulsiani and
               Jo{\~{a}}o Carreira and
               Jitendra Malik},
  title     = {Pose Induction for Novel Object Categories},
  year={2015},
  booktitle={International Conference on Computer Vision (ICCV)}
}
```

![](figures/iccv15amodal.png)

**Amodal Completion and Size Constancy in Natural Scenes** \
 Abhishek Kar, **Shubham Tulsiani**, João Carreira, Jitendra Malik \
 ICCV, 2015 \
 [pdf](https://arxiv.org/pdf/1509.08147.pdf)  
[abstract](javascript:toggleblock('iccv15amodalAbs'))  
[bibtex](javascript:toggleblock('iccv15amodalBib'))

*We consider the problem of enriching current object detection systems
with veridical object sizes and relative depth estimates from a single
image. There are several technical challenges to this, such as
occlusions, lack of calibration data and the scale ambiguity between
object size and distance. These have not been addressed in full
generality in previous work. Here we propose to tackle these issues by
building upon advances in object recognition and using recently created
large-scale datasets. We first introduce the task of amodal bounding box
completion, which aims to infer the the full extent of the object
instances in the image. We then propose a probabilistic framework for
learning category-specific object size distributions from available
annotations and leverage these in conjunction with amodal completions to
infer veridical sizes of objects in novel images. Finally, we introduce
a focal length prediction approach that exploits scene recognition to
overcome inherent scale ambiguities and demonstrate qualitative results
on challenging real-world scenes.*

``` {#iccv15amodalBib xml:space="preserve"}

@inProceedings{amodalKTCM15,
  author    = {Abhishek Kar and
               Shubham Tulsiani and
               Jo{\~{a}}o Carreira and
               Jitendra Malik},
  title     = {Amodal Completion and Size Constancy in Natural Scenes},
  year={2015},
  booktitle={International Conference on Computer Vision (ICCV)}
 }
```

![](figures/cvpr15vpsKps.png)

**Viewpoints and Keypoints** \
 **Shubham Tulsiani**, Jitendra Malik \
 CVPR, 2015 \
 [pdf](https://arxiv.org/pdf/1411.6067.pdf)  
[abstract](javascript:toggleblock('cvpr15vpsAbs'))  
[bibtex](javascript:toggleblock('cvpr15vpsBib'))  
[code](https://github.com/shubhtuls/ViewpointsAndKeypoints)

*We characterize the problem of pose estimation for rigid objects in
terms of determining viewpoint to explain coarse pose and keypoint
prediction to capture the finer details. We address both these tasks in
two different settings - the constrained setting with known bounding
boxes and the more challenging detection setting where the aim is to
simultaneously detect and correctly estimate pose of objects. We present
Convolutional Neural Network based architectures for these and
demonstrate that leveraging viewpoint estimates can substantially
improve local appearance based keypoint predictions. In addition to
achieving significant improvements over state-of-the-art in the above
tasks, we analyze the error modes and effect of object characteristics
on performance to guide future efforts towards this goal.*

``` {#cvpr15vpsBib xml:space="preserve"}

@inProceedings{vpsKpsTulsianiM15,
  author    = {Shubham Tulsiani and Jitendra Malik},
  title     = {Viewpoints and Keypoints},
  year={2015},
  booktitle={Computer Vision and Pattern Recognition (CVPR)}
}
```

![](figures/cvpr15reconstruction.png)

**Category-Specific Object Reconstruction from a Single Image** \
 Abhishek Kar\*, **Shubham Tulsiani**\*, João Carreira, Jitendra Malik \
 CVPR, 2015 **(Best Student Paper Award)**\
 [pdf](https://arxiv.org/pdf/1411.6069.pdf)   [project
page](http://www.cs.berkeley.edu/~akar/categoryShapes/)  
[abstract](javascript:toggleblock('cvpr15csdmAbs'))  
[bibtex](javascript:toggleblock('cvpr15csdmBib'))  
[code](https://github.com/akar43/CategoryShapes)  
[note](Best%20Student%20Paper%20Award)

*Object reconstruction from a single image - in the wild - is a problem
where we can make progress and get meaningful results today. This is the
main message of this paper, which introduces an automated pipeline with
pixels as inputs and 3D surfaces of various rigid categories as outputs
in images of realistic scenes. At the core of our approach are
deformable 3D models that can be learned from 2D annotations available
in existing object detection datasets, that can be driven by noisy
automatic object segmentations and which we complement with a bottom-up
module for recovering high-frequency shape details. We perform a
comprehensive quantitative analysis and ablation study of our approach
using the recently introduced PASCAL 3D+ dataset and show very
encouraging automatic reconstructions on PASCAL VOC.*

``` {#cvpr15csdmBib xml:space="preserve"}

@inProceedings{shapesKarTCM15,
  author    = {Abhishek Kar and
               Shubham Tulsiani and
               Jo{\~{a}}o Carreira and
               Jitendra Malik},
  title     = {Category-Specific Object Reconstruction from a Single Image},
  year={2015},
  booktitle={Computer Vision and Pattern Recognition (CVPR)}
}
```

![](figures/cvpr15vvn.png)

**Virtual View Networks for Object Reconstruction** \
 João Carreira, Abhishek Kar, **Shubham Tulsiani**, Jitendra Malik \
 CVPR, 2015 \
 [pdf](https://arxiv.org/pdf/1411.6091.pdf)  
[abstract](javascript:toggleblock('cvpr15vvnAbs'))  
[bibtex](javascript:toggleblock('cvpr15vvnBib'))  
[video](https://www.youtube.com/watch?v=JfDJji5sYXE&feature=youtu.be)  
[code](http://www.cs.berkeley.edu/~carreira/vvn/)

*All that structure from motion algorithms "see" are sets of 2D points.
We show that these impoverished views of the world can be faked for the
purpose of reconstructing objects in challenging settings, such as from
a single image, or from a few ones far apart, by recognizing the object
and getting help from a collection of images of other objects from the
same class. We synthesize virtual views by computing geodesics on novel
networks connecting objects with similar viewpoints, and introduce
techniques to increase the specificity and robustness of
factorization-based object reconstruction in this setting. We report
accurate object shape reconstruction from a single image on challenging
PASCAL VOC data, which suggests that the current domain of applications
of rigid structure-from-motion techniques may be significantly
extended.*

``` {#cvpr15vvnBib xml:space="preserve"}

@inProceedings{vvnCarreiraKTM15,
  author    = {Jo{\~{a}}o Carreira and
               Abhishek Kar and
               Shubham Tulsiani and
               Jitendra Malik},
  title     = {Virtual View Networks for Object Reconstruction},
  year={2015},
  booktitle={Computer Vision and Pattern Recognition (CVPR)}
}
```

\
2013

* * * * *

![](figures/uist13.png)

**A colorful approach to text processing by example** \
 Kuat Yessenov, **Shubham Tulsiani**, Aditya Menon, Robert C Miller,
Sumit Gulwani, Butler Lampson, Adam Kalai \
 UIST, 2013 \
 [pdf](papers/uist13colors.pdf)  
[abstract](javascript:toggleblock('uist13colorsAbs'))  
[bibtex](javascript:toggleblock('uist13colorsBib'))

*Text processing, tedious and error-prone even for programmers, remains
one of the most alluring targets of Programming by Example. An
examination of real-world text processing tasks found on help forums
reveals that many such tasks, beyond simple string manipulation, involve
latent hierarchical structures. We present STEPS, a programming system
for processing structured and semi-structured text by example. STEPS
users create and manipulate hierarchical structure by example. In a
between-subject user study on fourteen computer scientists, STEPS
compares favorably to traditional programming.*

``` {#uist13colorsBib xml:space="preserve"}

@inproceedings{yessenov2013colorful,
  title={A colorful approach to text processing by example},
  author={Yessenov, Kuat and
  Tulsiani, Shubham and
  Menon, Aditya and
  Miller, Robert C and
  Gulwani,Sumit and
  Lampson, Butler and
  Kalai, Adam},
  booktitle={UIST},
  pages={495--504},
  year={2013},
  organization={ACM}
}
```

Teaching
--------

+--------------------------------------+--------------------------------------+
| ![](figures/compPhoto.jpg)![](figure | [](http://inst.eecs.berkeley.edu/~cs |
| s/cs188.png)                         | 188/fa10/announcements.html)[**Image |
|                                      | Manipulation and Computational       |
|                                      | Photography                          |
|                                      | (CS194-26)**](http://inst.eecs.berke |
|                                      | ley.edu/~cs194-26/fa14/)\            |
|                                      |  Fall 2014 (GSI)                     |
|                                      |                                      |
|                                      | \                                    |
|                                      |                                      |
|                                      | [**Introduction to Artificial        |
|                                      | Intelligence                         |
|                                      | (CS188)**](https://edge.edx.org/cour |
|                                      | ses/BerkeleyX/CS188x-SP15/SP15/info) |
|                                      | \                                    |
|                                      |  Spring 2015 (GSI)                   |
|                                      |                                      |
|                                      | \                                    |
+--------------------------------------+--------------------------------------+


