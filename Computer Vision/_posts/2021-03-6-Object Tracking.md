---
layout: single
classes: wide
title:  "Object Tracking"


header:
  teaser: /assets/images/convnet-art.png
  overlay_image: /assets/images/convnet-art.png
excerpt: "Extracting Spatiotemporal Features"

permalink: /computer-vision/object-tracking/
---

## Object Tracking ##

In our previous posts, we've learned what [**instance segmentation**](http://localhost:4000/pyphase/computer-vision/object-detector/) is and that these object detecting modules can extract crucial information from images such as the object location, shape, and size. While these features are extremely valuable, we can learn so much more by linking these features throughout *time*. That is essentially what object tracking does. 

Object tracking primarily operates based on two main subtasks: object detection and object linkage. Depending on the application and the provided dataset, different object detection modules can be chosen, varying from [**bounding box detection**](https://pjreddie.com/darknet/yolo/), [**semantic segmentation**](https://heartbeat.fritz.ai/a-2019-guide-to-semantic-segmentation-ca8242f5a7fc), and [**instance segmentation**](http://localhost:4000/pyphase/computer-vision/object-detector/), where instance segmentation is the high-end pixel-level object detection method. Linking algorithms enable spatiotemporal feature acquisition by connecting principal features (i.e., centroids, bounding box coordinates, intensity, and morphology) of the detected objects with respect to time.

<figure style="width: 500px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/tracking-framework2.png" alt="">
  <figcaption>Object tracking framework</figcaption>
</figure> 


Above is an example of a modular framework that we recently developed which consists of AI-enabled object detection, object tracking, and data processing modules to extract meaningful features from imaging datasets. 1) Object detection module: As illustrated in the figure above, high-resolution droplet images first pass through a custom-trained instance segmentation module (Mask R-CNN) where droplet masks assigned with unique IDs are generated. At this stage, the model records primitive spatial features (e.g., equivalent diameter, pixel-wise area, eccentricity, orientation, solidity, and location). 2) Object tracking module: The detected masks then pass through a tracking module where the IDed spatial features are used as parameters for tracking via the k-dimensional (k-d) tree algorithm. During the droplet tracking process, potential errors are manually identified and corrected using a documented graphical user interface (GUI).