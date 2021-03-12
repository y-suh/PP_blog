---
layout: single
classes: wide
title:  "Image Annotation"



header:
  teaser: /assets/images/annotation2.png
  overlay_image: /assets/images/annotation2.png

excerpt: "Creating Datasets"

permalink: /computer-vision/annotation/
---

## Image Annotation ##

<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/annotation.png" alt="">
  <figcaption></figcaption>
</figure> 

Image annotation is an essential task in computer vision involving the process of creating ground truths or "answers" for images used in the process of training a model. For example, we've learned that Mask R-CNN is an [**instance segmentation module**](http://localhost:4000/pyphase/Machine-Learning/object-detector/), meaning that it generates pixel-wise masks for every object in the image. Being a [**supervised learning**](http://localhost:4000/pyphase/Machine-Learning/what-is-machine-learning/) model, Mask R-CNN requires labelled data in forms of pixel-wise image annotations in order to learn. These annotated datasets are so important to the training process, that prediction results can drastically change depending on the quality of annotation. The image above is an example of an annotated image for pool boiling experiments. The annotated masks are each created by a human annotator. 



## How Does Image Annotation Work? ##

For image annotation, we need three things:



1. `Images` - We generally need lots of images. Usually, it would make sense to collect diverse sets for better generalizability. 
2. `An annotator` - When working with large datasets, we usually recruit members to work as teams for the labor-intensive annotation process. It is crucial for annotators to communicate with each other and establish specific guidelines for each annotation project. The machine learns what it is taught, and therefore annotations lacking united quality or style may substantially reduce the learning capability of the machine. 
3. `An image annotation platform` - There are many commercial platforms that one can choose from. Note each platform may have different output styles that must be considered. Other factors include: accessibility, project management, and labeling technology. Our group uses Supervisely for our annotation projects.



## Resource ##

Below is an example walkthrough of image annotations using Supervisely.

{% include video id="1q0HGsF6KbkihQkUkbTmXe4db2Kbfsj1A" provider="google-drive" %}



