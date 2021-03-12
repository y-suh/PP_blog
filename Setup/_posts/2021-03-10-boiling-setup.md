---
layout: single
classes: wide

title: "Pool Boiling Setup"
date:   2021-1-1 18:28:25 -0800

header:
  teaser: /assets/images/boiling.jpg
  overlay_image: /assets/images/boiling.jpg
excerpt: "Boiling is arguably Nature’s most effective thermal management mechanism that cools submersed matter through bubble-induced advective transport."

path: ""

---

<br/>

# Setup

<figure style="width: 600px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/boiling-setup.png" alt="">
  <figcaption>Pool boiling setup.</figcaption>
</figure> 



**Experimental Setup.** The pool boiling rig mainly consists of the boiling surface, a heating block, a data acquisition device connected to thermocouples, and a high-speed camera. The boiling surface is a 1 cm X 1 cm plain copper sample, which is soldered and left attached on a custom-built copper heating block in all measurements to ensure consistent thermal contact resistance. The heating block consists of four cylindrical cartridge heaters, which are heated by AV voltage regulator (Variac Transformer), where an insulating glass wool thoroughly encloses the copper block to promote one-dimensional thermal conduction. The generated heat flux is calculated by taking the average heat flux *q*” = *kΔT/L* measured from four K-type thermocouples positioned incrementally along the copper heating block where *k* is the thermal conductivity and *ΔT* is the temperature difference measured between a prescribed distance *L.* The uncertainty of thermocouple measurements is ±1^oC, which leads to an estimated uncertainty of 2.2% at the maximum heat flux by using the law of propagation of uncertainty. A data acquisition device (Labjack U6) records temperatures. Above the boiling surface, a transparent guard heater-installed boiling chamber maintains degassed DI water in saturation conditions by receiving signals from a PID controller. 
{: style="text-align: justify;"}



**Real-time Data Acquisition.** Pool boiling images and videos are obtained via a high-speed camera (FASTCAM Mini AX50). Since high resolution images convey important bubble statistics in relation to the boiling heat flux, we set the image resolution to 1024 X 1024 pixels in this study. To improve the imaging quality, a light diffuser is placed opposite from the camera to evenly distribute background lighting. High speed imaging of 2,000 fps improves the image quality even further by reducing motion blurs. On the other hand, high-speed imaging can produce overly correlated image datasets if captured in high frame sequences. Highly sequential image datasets, in turn, risk being biased towards only a few numbers of bubbles and requires unnecessarily many images to increase the dataset diversity. 
{: style="text-align: justify;"}