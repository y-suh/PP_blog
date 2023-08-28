---
title: "Research"
layout: single
classes: wide
excerpt: "**Youngjoon Suh.**"
header:
  overlay_image: /assets/images/bubbles.jpg
  teaser: /assets/images/bubbles.jpg

author_profile: true

permalink: /research/
---



------

## Research Statement 

My research intersects the multidisciplinary fields of **machine learning, thermo-fluid sciences, interfacial phenomena, and energy**. The overarching goal of his research is as follows: 1) fundamental research on micro/nanostructured surfaces for phase change and interfacial phenomena, 2) development of novel thermofluidic characterization metrologies at small (micro/nano) scales, and 3) futuristic approaches leveraging deep learning to address major thermal management issues for high power density systems. 



## Computer Vision/Deep Learning

<figure style="width: 500px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/Bubbles2.png" alt="">
  <figcaption>Physics-reinforced learning framework schematic. Remotely acquired images are provided to the framework where cutting-edge convolutional neural network (CNN) architectures and advanced object detection algorithms automatically extract features. The proposed framework learns from a hierarchy of image features as well as boiling physics with the aim of predicting real-time boiling heat flux.</figcaption>
</figure> 



### Image-based Feature Regression

Image-based feature regression models autonomously predict outcomes (e.g., temperature, pressure, thermal performance) by learning to extract vital features from images and link them to output parameters via machine learning techniques. These models are powerful at identifying differences or anomalies in images that even experts might miss. In our [recent publication](https://www.nature.com/articles/s41598-021-85150-4), we develop a data-driven framework that predicts boiling heat transfer performance based on high-quality bubble images in quasi real-time (Figure). Our framework conceptualizes state-of-the-art CNNs and object detection algorithms to automatically extract hierarchical image features as well as physics-based bubble statistics to learn inherent boiling physics. By training on these features, the framework not only describes the manner in which the bubbles nucleate and depart under boiling conditions, but also predicts the boiling curves with high precision. The framework thereby provides quantitative descriptions of underlying boiling activities that can potentially help discover unknown boiling laws. 
{: style="text-align: justify;"}



### Data-driven Physics

{% include video id="11WHSGer80lJXlWJ4Y3YHCJoKkVhVhdck" provider="google-drive" %}

Data-driven physics connects heat transfer performance with statistics through physical relationships (e.g., energy balance equations). The results gained from this method is highly intuitive because it directly applies mathematically and physically sound equations for predictions. Data-driven research based on setting up enormous databases that are built and shared with the community can revolutionize how we model complex engineering systems. The successful collection of high-quality datasets benefits various applications, in particular, in the area of thermo-fluidic and energy sciences. The performance or efficiency of energy applications often rely on processes associated with phase-change phenomena, i.e., boiling and condensation. These phenomena are naturally complex, and understanding them relies on careful characterization of nucleation dynamics through bubbles or droplets, experimental and computationally. Often finding direct correlations has been challenging because of the complex nature of the phase-change phenomena, which involves multi-dimensional features. The goal of this research is to leverage the recent advancements in computer and data sciences to develop a data-driven framework in the area of thermofluidic and energy sciences.
{: style="text-align: justify;"}



## Micro/Nanoscale Engineered Surfaces

<figure style="width: 500px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/nano.png" alt="">
  <figcaption>Scalable template-based porous materials can be made to modify surface properties to enhance thermofluidic performances.</figcaption>
</figure> 

### Multifunctional Properties

Two-phase cooling devices, such as vapor chambers, capillary pumped loop heat pipes, loop heat pipes, and thermosyphon heat pipes, operate in an evaporation, liquid-transport, and condensation cycle that utilize micro/nanoscale porous media called the wick (Figure). The wick plays a vital role within the cooling devices by vaporizing, absorbing, and transporting the working fluid to maximize heat dissipation. Therefore, an optimal wick should have properties such as efficient working-fluid delivery (i.e., permeability), large surface area to volume ratios, low thermal resistance, and high effective thermal conductivity. 
{: style="text-align: justify;"}



<figure style="width: 450px" class="align-left">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/fluorescence.png" alt="">
  <figcaption>Distinctive saturation regimes during evaporative self-assembly are probed using μLIF techniques.</figcaption>
</figure> 


### Micro Laser Induced Fluorescence (μLIF) 

As an emerging technique, laser induced fluorescence (LIF) gains attention as a powerful tool to characterize thermal profiles at multiple scales with high fidelity. In general, LIF utilizes temperature-and light-sensitive molecules called fluorophores. At the macroscale, LIF has been conventionally used to analyze bulk thermofluidic physics typically over the mm scale. On the other hand, micro laser induced fluorescence (μLIF) employs fluorescent microscopes to improve spatial and thermal resolutions up to 0.1 – 0.3 μm and 0.01 K, respectively. The methods generally employ fluorescence, where temperature-sensitive fluorophores absorb photons of a specific wavelength (i.e., excitation) and emit photons of a longer wavelength (i.e., emission). The emitted fluorescence signals are selectively transmitted through an optical filter to produce fluorescence intensity-based imaging, which is then converted into temperature-based pictures. A great advantage of using μLIF is to observe temporal micro/nanoscale pixel-based fluorescent intensity profiles of the liquid-vapor interface (Figure). In other words, even some of the smallest liquid-vapor surface features are easily detected by observing fluorescence signals and can be used to assess local drying phenomena in complex structures.
{: style="text-align: justify;"}
