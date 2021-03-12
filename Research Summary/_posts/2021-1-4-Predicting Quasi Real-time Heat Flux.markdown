---
layout: single
classes: wide
title:  "Predicting Quasi Real-Time Boiling Heat Transfer"
date:   2020-12-19 18:28:25 -0800

header:
  teaser: /assets/images/boiling.jpg
  overlay_image: /assets/images/boiling.jpg

excerpt: "Viewing Boiling With AI"

---



## Outcome ##

<br/>

Research ['Deep Learning Predicts Boiling Heat Transfer'](https://www.nature.com/articles/s41598-021-85150-4) published  in the journal Scientific Reports.

<br/>

## Abstract ##

Boiling is arguably Nature’s most effective thermal management mechanism that cools submersed matter through bubble-induced advective transport. Central to the boiling process is the development of bubbles. Connecting boiling physics with bubble dynamics is an important, yet daunting challenge because of the intrinsically complex and high dimensional of bubble dynamics. Here, we introduce a data-driven learning framework that correlates high-quality imaging on dynamic bubbles with associated boiling curves. The framework leverages cutting-edge deep learning models including convolutional neural networks and object detection algorithms to automatically extract both hierarchical and physics-based features. By training on these features, our model learns physical boiling laws that statistically describe the manner in which bubbles nucleate, coalesce, and depart under boiling conditions, enabling in situ boiling curve prediction with a mean error of 6%. Our framework offers an automated, learning-based, alternative to conventional boiling heat transfer metrology

<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/scirep/Figure 1.jpg" alt="">
  <figcaption>Physics-reinforced learning framework schematic. Remotely acquired images are provided to the framework where cutting-edge convolutional neural network (CNN) architectures and advanced object detection algorithms automatically extract features. The proposed framework learns from a hierarchy of image features as well as physical boiling patterns with the aim of predicting real-time boiling heat flux. </figcaption>
</figure> 

## Main Findings ##

Our framework conceptualizes state-of-the-art CNNs and object detection algorithms to automatically extract hierarchical image features as well as physics-based bubble statistics to learn inherent boiling physics. By training on these features, the framework not only describes the manner in which the bubbles nucleate and depart under boiling conditions, but also predicts the boiling curves with a mean error of 6% using a small dataset. The framework thereby provides quantitative descriptions of underlying boiling activities that can potentially help discover unknown boiling laws.

Perhaps more importantly, the use of deep learning framework can be resource effective, in experimental and computational manners. For instance, visualization-based methods are remote, which means that the measurements can be conducted over multiple boiling setups with minimum space requirements. Furthermore, the presented method is cost-effective. Conventional methods using thermocouple and electrical power input setups require wired attachments (i.e., probes and multimeters) while IR cameras need dichroic mirror fixture stages and can only conduct bottom-to-top imaging. In many cases, these attachments substantially increase the costs of boiling devices at both lab and commercial scales. In addition to the space and cost considerations, the learning framework through the image automation significantly saves computational time to analyze large-size datasets by synchronizing image data with the measured values. While high-resolution images are extremely memory-expensive, the transfer learning and data augmentation techniques can reduce the required image dataset size and model training time. The resource-effective framework demonstrated here will help describe other types of image-based transport phenomena to impact the heat transfer community.

<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/scirep/Figure 3.jpg" alt="">
  <figcaption>Bubble statistics with varying heat flux. (a) The average bubble size and boiling heat flux display a linear relationship. The error bars represent the standard deviation. The inset shows that the bubbles sizes are originally extracted as pixel values. The pixel values are converted to mm2 bubble sizes using a commercial program ImageJ and then averaged over the corresponding heat flux. (b) The bubble size standard deviation, in turn, characterizes bubble size differences of a given step and also exhibits a near-linear trend. Low heat fluxes have small standard deviations, which means bubbles sizes are relatively uniform. As heat flux increases, the difference becomes small and large bubbles become increasingly noticeable and is reflected in the plot. The bubble size differences for low and high heat fluxes are illustrated in the inset. (c) The average bubble count decreases exponentially due to vigorous bubble coalescence as boiling heat flux increases. The inset portrays individual bubbles that are identified and counted. </figcaption>
</figure> 



<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/scirep/Figure 5.jpg" alt="">
  <figcaption>Real-time prediction of boiling heat flux using trained deep learning models. The training results for the (a) HyPR, (b) CNN, and (c) MLP models show all three models can learn well from the teaching dataset with a testing loss of 2.49, 7.11, and 5.36, respectively. The losses are plotted in log scales to show the exponential decay. (d) The trained models predict real-time steady state (S1-5) and transient state (T1-4) heat fluxes. The HyPR and MLP models respond well to the increasing and decreasing boiling curves, demonstrating minimal deviations. In contrast, the CNN models follow the general trend of the varying heat flux; however, overpredicts mid-range heat fluxes from 40 to 60 W/cmy. Error bars represent the standard deviation of the predictions of all 500 images for each heat flux step. (e) Mean absolute percentage errors (MAPE) characterize the realistic prediction accuracy, where the HyPR, CNN, and MLP models report 6%, 15%, and 8% mean error, respectively. The error bars show the standard deviation of MAPE.</figcaption>
</figure> 