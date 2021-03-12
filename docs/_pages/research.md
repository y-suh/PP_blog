---
title: "Research"
layout: single
classes: wide
excerpt: "**Research is what I'm doing when I don't know what I'm doing.**"
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
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/MLboiling.png" alt="">
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

Two-phase cooling devices, such as vapor chambers,[1] capillary pumped loop heat pipes,[1, 2] loop heat pipes,[1-4] and thermosyphon heat pipes,[5] operate in an evaporation, liquid-transport, and condensation cycle that utilize micro/nanoscale porous media called the wick (Figure).[1] The wick plays a vital role within the cooling devices by vaporizing, absorbing, and transporting the working fluid to maximize heat dissipation. Therefore, an optimal wick should have properties such as efficient working-fluid delivery (i.e., permeability),[3, 6] large surface area to volume ratios,[7] low thermal resistance,[5] and high effective thermal conductivity.[5] 
{: style="text-align: justify;"}



<figure style="width: 450px" class="align-left">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/fluorescence.png" alt="">
  <figcaption>Distinctive saturation regimes during evaporative self-assembly are probed using μLIF techniques.</figcaption>
</figure> 


### Micro Laser Induced Fluorescence (μLIF) 

As an emerging technique, laser induced fluorescence (LIF) gains attention as a powerful tool to characterize thermal profiles at multiple scales with high fidelity. In general, LIF utilizes temperature-and light-sensitive molecules called fluorophores. At the macroscale, LIF has been conventionally used to analyze bulk thermofluidic physics typically over the mm scale.[8-10] On the other hand, micro laser induced fluorescence (μLIF) employs fluorescent microscopes to improve spatial and thermal resolutions up to 0.1 – 0.3 μm and 0.01 K, respectively. [11-19] The methods generally employ fluorescence, where temperature-sensitive fluorophores absorb photons of a specific wavelength (i.e., excitation) and emit photons of a longer wavelength (i.e., emission). The emitted fluorescence signals are selectively transmitted through an optical filter to produce fluorescence intensity-based imaging, which is then converted into temperature-based pictures. A great advantage of using μLIF is to observe temporal micro/nanoscale pixel-based fluorescent intensity profiles of the liquid-vapor interface (Figure). In other words, even some of the smallest liquid-vapor surface features are easily detected by observing fluorescence signals and can be used to assess local drying phenomena in complex structures.
{: style="text-align: justify;"}




### References

[1] A. J. J. o. h. t. Faghri, **2012,** *134*, 123001.

[2] S. Launay; V. Sartre; J. Bonjour, *Int J Therm Sci* **2007,** *46*, 621.

[3] C. C. Yeh; C. N. Chen; Y. M. Chen, *Int J Heat Mass Tran* **2009,** *52*, 4426.

[4] B. Weisenseel; P. Greil; T. J. A. E. M. Fey, **2017,** *19*, 1600379.

[5] G. Huminic; A. Huminic; I. Morjan; F. Dumitrache, *Int J Heat Mass Tran* **2011,** *54*, 656.

[6] J. Lee; Y. Suh; P. P. Dubey; M. T. Barako; Y. Won, *Acs Appl Mater Inter* **2019,** *11*, 1546.

[7] K. K. Bodla; J. A. Weibel; S. V. Garimella, *J Heat Trans-T Asme* **2013,** *135*.

[8] H. Rochlitz; P. Scholz, *Experiments in Fluids* **2018,** *59*.

[9] R. S. Volkov; P. A. Strizhak, *Applied Thermal Engineering* **2017,** *127*, 141.

[10] W. Chaze; O. Caballina; G. Castanet; F. Lemoine, *Experiments in Fluids* **2017,** *58*.

[11] J. Feng; L. Xiong; S. Q. Wang; S. Y. Li; Y. Li; G. Q. Yang, *Adv Funct Mater* **2013,** *23*, 340.

[12] P. Low; B. Kim; N. Takama; C. Bergaud, *Small* **2008,** *4*, 908.

[13] D. Erickson; D. Sinton; D. Q. Li, *Lab on a Chip* **2003,** *3*, 141.

[14] R. Samy; T. Glawdel; C. L. Ren, *Anal Chem* **2008,** *80*, 369.

[15] T. Glawdel; Z. Almutairi; S. Wang; C. Ren, *Lab on a Chip* **2009,** *9*, 171.

[16] D. Ross; M. Gaitan; L. E. Locascio, *Analytical Chemistry* **2001,** *73*, 4117.

[17] F. Vetrone; R. Naccache; A. Zamarron; A. J. de la Fuente; F. Sanz-Rodriguez; L. M. Maestro; E. M. Rodriguez; D. Jaque; J. G. Sole; J. A. Capobianco, *Acs Nano* **2010,** *4*, 3254.

[18] J. Feng; K. J. Tian; D. H. Hu; S. Q. Wang; S. Y. Li; Y. Zeng; Y. Li; G. Q. Yang, *Angew Chem Int Edit* **2011,** *50*, 8072.

[19] Y. Suh; C.-H. Lin; H. Gowda; Y. Won In *Evaporation Rate Measurement at Multiple Scales Using Temperature-Sensitive Fluorescence Dyes*, ASME 2019 International Technical Conference and Exhibition on Packaging and Integration of Electronic and Photonic Microsystems, American Society of Mechanical Engineers Digital Collection.

[20] R. Lindsey; A. Daluiski; S. Chopra; A. Lachapelle; M. Mozer; S. Sicular; D. Hanel; M. Gardner; A. Gupta; R. Hotchkiss; H. Potter, *P Natl Acad Sci USA* **2018,** *115*, 11591.

[21] D. Shen; G. Wu; H.-I. Suk, *Annual review of biomedical engineering* **2017,** *19*, 221.

[22] J. M. Newby; A. M. Schaefer; P. T. Lee; M. G. Forest; S. K. Lai, *P Natl Acad Sci USA* **2018,** *115*, 9026.

[23] G. Lio; R. Fadda; G. Doneddu; J. R. Duhamel; A. Sirigu, *Nat Commun* **2019,** *10*.

[24] M. S. Norouzzadeh; A. Nguyen; M. Kosmala; A. Swanson; M. S. Palmer; C. Packer; J. Clune, *P Natl Acad Sci USA* **2018,** *115*, E5716.

[25] Y. Qu; H. Zhu; Y. Shen; J. Zhang; C. Tao; P. Ghosh; M. Qiu, *Science Bulletin* **2020**.

[26] S. M. Mousavi; W. L. Ellsworth; W. Zhu; L. Y. Chuang; G. C. Beroza, *Nat Commun* **2020,** *11*, 1.

[27] A. Ziletti; D. Kumar; M. Scheffler; L. M. Ghiringhelli, *Nat Commun* **2018,** *9*.

[28] Z. Geng; Y. F. Wang, *Nat Commun* **2020,** *11*.

[29] Z. Q. Tang; K. V. Chuang; C. DeCarli; L. W. Jin; L. Beckett; M. J. Keiser; B. N. Dugger, *Nat Commun* **2019,** *10*.

[30] B. Huval; T. Wang; S. Tandon; J. Kiske; W. Song; J. Pazhayampallil; M. Andriluka; P. Rajpurkar; T. Migimatsu; R. Cheng-Yue, *arXiv preprint arXiv:1504.01716* **2015**.

[31] F. Milletari; N. Navab; S. A. Ahmadi, *Int Conf 3d Vision* **2016**, 565.

[32] D. M. Pelt; J. A. Sethian, *P Natl Acad Sci USA* **2018,** *115*, 254.

[33] J. Wu; X. Yin; H. Xiao, *Science bulletin* **2018,** *63*, 1215.

[34] F. Wang; J.-F. Yang; M.-Y. Wang; C.-Y. Jia; X.-X. Shi; G.-F. Hao; G.-F. Yang, *Science Bulletin* **2020**.

[35] S. Grossman; G. Gaziv; E. M. Yeagle; M. Harel; P. Megevand; D. M. Groppe; S. Khuvis; J. L. Herrero; M. Irani; A. D. Mehta; R. Malach, *Nat Commun* **2019,** *10*.

[36] A. A. K. Nielsen; C. A. Voigt, *Nat Commun* **2018,** *9*.

[37] Y. Oktar; D. Karakaya; O. Ulucan; M. Turkan, *arXiv preprint arXiv:1912.10201* **2019**.

[38] G. M. Hobold; A. K. da Silva, *Int J Heat Mass Tran* **2018,** *125*, 1296.

[39] G. M. Hobold; A. K. da Silva, *Int J Heat Mass Tran* **2019,** *134*, 511.

[40] J. Jie; Z. Hu; G. Qian; M. Weng; S. Li; S. Li; M. Hu; D. Chen; W. Xiao; J. Zheng, *Science Bulletin* **2019,** *64*, 612.