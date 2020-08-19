---
layout: post
title:  "On using Focal Loss for Neural Network Calibration"
comments: false
category: Research
---

#### Here we briefly discuss our work [<font color="#3498DB">On using Focal Loss for Neural Network Calibration</font>](http://www.robots.ox.ac.uk/~tvg/publications/2020/Calibration_Focal_Loss_ICML_UDL.pdf){:target="_blank"}. This work got accepted in ICML-2020 Uncertainty and Robustness in Deep Learning (UDL) workshop, as a spotlight (top 10% of accepted papers).

#### A classification neural networks is said to be miscalibrated when there is a mismatch between the model's confidence and its correctness. Ideally, we want networks to be accurate and calibrated so that their predictions can be trusted by a downstream task. It is much more important in critical cases of healthcare and driverless cars.

#### In this work, we first try to observe the possible factors of miscalibration, e.g. the network getting overconfident on wrong predictions at test time. This may be caused by magnification of weights.

#### We then suggest using the Focal Loss to help improve the calibration. We show that it implicitly maximises entropy while minimising the KL divergence between the predicted and the target distributions.  Futhermore, we empirically observe that the NLL overfitting phenomenon is significantly reduced in case of focal loss as compared to cross-entropy and hence, it can be expected to produce more calibrated models.

#### We conduct extensive experiments on a variety of datasets and network architectures. Our results show that in almost all cases, networks trained with focal loss are more calibrated than those trained with cross-entropy loss, label smoothing, Brier score and MMCE, without affecting the accuracy. This makes their predictions much easier for downstream components to trust.
