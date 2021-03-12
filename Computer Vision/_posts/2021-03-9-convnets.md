---
layout: single
classes: wide
title:  "Convolutional Neural Networks (CNN)"


header:
  teaser: /assets/images/future.jpg
  overlay_image: /assets/images/future.jpg
excerpt: "Convnets emulate the human brain's natural visual perception mechanism by systematically learning features through multiple operational layers."

permalink: /computer-vision/convolutional-neural-networks/
---



In our [previous post]({{ site.url }}{{ site.baseurl }}/Machine-Learning/1.%20what-is-machine-learning/), we discussed what supervised learning algorithms were and how most machine learning problems can be categorized into ***classification*** or ***regression*** problems. If your task involves visual imagery (i.g., images or videos), there is a high chance that you will use a particular class of deep neural networks called **convolutional neural networks** (**CNNs**, or **ConvNets**). In this post, we'll take a closer look at what CNNs are, and how they are being used in the thermal science community today.

Current advances in deep learning and, in particular, convolutional neural networks have enabled automatic and scalable image analysis for, e.g., object detection[1-4], classification[5-10], and even image-based predictions[11-17]. Many CNN-based deep learning frameworks are effective because CNNs emulate the human brain’s natural visual perception mechanism by systematically learning features through multiple operational layers[18]. Image-based deep learning models can play a vital role in fully understanding two-phase heat transfer physics because most of our experimental images are richly embedded with statistics (e.g., bubble statistics, droplet statistics), which are quantitative measurements of the dynamic boiling and condensation phenomena.

So let's think of a scenario where we want to predict the heat flux of a boiling surface just by observing the images. This is a little trickier than it sounds. As shown in the figure below, boiling images display quite distinguishable changes when viewed in relatively large heat flux steps (~20 W/cm<sup>2</sup>). However, the images become extremely difficult to tell apart, even for the trained expert, between small (<20 W/cm<sup>2</sup>) heat flux steps. 

<figure style="width: 600px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/heat-flux.png" alt="">
  <figcaption>At the first glance, temporal bubble images captured from the high-speed camera confirm the changes in bubble appearance are quite clear when heat flux steps are relatively large. However, it becomes much more challenging to differentiate bubble changes with small heat flux steps.</figcaption>
</figure> 
This is where CNNs kick in. CNN models use hierarchical image features to recognize small and critical details in images that the human eye may not perceive. Primitive features such as edges and corners are at the lower levels of this hierarchy, whereas more abstract features (e.g., the existence of a bubble) are at the higher levels. If you want to visualize how CNN models operate, I highly recommend you to read [this](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) article, which will walk you through the four main CNN operations (Convolution, ReLu, Pooling, and Prediction) in great detail.

In our next post, we'll examine a cutting edge deep CNN architecture called VGG16, which will be the backbone of our [image-based heat flux prediction model]({{ site.url }}{{ site.baseurl }}/tutorials/ConvNet/) discussed in our tutorial section. 



### References

[1] R. Lindsey; A. Daluiski; S. Chopra; A. Lachapelle; M. Mozer; S. Sicular; D. Hanel; M. Gardner; A. Gupta; R. Hotchkiss; H. Potter, *P Natl Acad Sci USA* **2018,** *115*, 11591.

[2] D. Shen; G. Wu; H.-I. Suk, *Annual review of biomedical engineering* **2017,** *19*, 221.

[3] J. M. Newby; A. M. Schaefer; P. T. Lee; M. G. Forest; S. K. Lai, *P Natl Acad Sci USA* **2018,** *115*, 9026.

[4] G. Lio; R. Fadda; G. Doneddu; J. R. Duhamel; A. Sirigu, *Nat Commun* **2019,** *10*.

[5] M. S. Norouzzadeh; A. Nguyen; M. Kosmala; A. Swanson; M. S. Palmer; C. Packer; J. Clune, *P Natl Acad Sci USA* **2018,** *115*, E5716.

[6] Y. Qu; H. Zhu; Y. Shen; J. Zhang; C. Tao; P. Ghosh; M. Qiu, *Science Bulletin* **2020**.

[7] S. M. Mousavi; W. L. Ellsworth; W. Zhu; L. Y. Chuang; G. C. Beroza, *Nat Commun* **2020,** *11*, 1.

[8] A. Ziletti; D. Kumar; M. Scheffler; L. M. Ghiringhelli, *Nat Commun* **2018,** *9*.

[9] Z. Geng; Y. F. Wang, *Nat Commun* **2020,** *11*.

[10] Z. Q. Tang; K. V. Chuang; C. DeCarli; L. W. Jin; L. Beckett; M. J. Keiser; B. N. Dugger, *Nat Commun* **2019,** *10*.

[11] B. Huval; T. Wang; S. Tandon; J. Kiske; W. Song; J. Pazhayampallil; M. Andriluka; P. Rajpurkar; T. Migimatsu; R. Cheng-Yue, *arXiv preprint arXiv:1504.01716* **2015**.

[12] F. Milletari; N. Navab; S. A. Ahmadi, *Int Conf 3d Vision* **2016**, 565.

[13] D. M. Pelt; J. A. Sethian, *P Natl Acad Sci USA* **2018,** *115*, 254.

[14] J. Wu; X. Yin; H. Xiao, *Science bulletin* **2018,** *63*, 1215.

[15] F. Wang; J.-F. Yang; M.-Y. Wang; C.-Y. Jia; X.-X. Shi; G.-F. Hao; G.-F. Yang, *Science Bulletin* **2020**.

[16] S. Grossman; G. Gaziv; E. M. Yeagle; M. Harel; P. Megevand; D. M. Groppe; S. Khuvis; J. L. Herrero; M. Irani; A. D. Mehta; R. Malach, *Nat Commun* **2019,** *10*.

[17] A. A. K. Nielsen; C. A. Voigt, *Nat Commun* **2018,** *9*.

[18] Y. Oktar; D. Karakaya; O. Ulucan; M. Turkan, *arXiv preprint arXiv:1912.10201* **2019**.