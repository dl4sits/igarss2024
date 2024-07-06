---
layout: page
title: Tutorial
permalink: /tutorial/
path: tutorial.md
---

#### 2024 -- IEEE International Geoscience and Remote Sensing Symposium, Athens, Greece

## Time-Series Tutorial - Understanding Dynamics with Advanced Time-Series Processing Techniques

During the last decades, the number and characteristics of imaging sensors onboard satellites have constantly increased and evolved, allowing access (often free of charge) to a large amount of Earth Observation data. Recent satellites, such as Sentinel-2 or PlanetScope Doves, frequently revisit the same regions at weekly or even daily temporal resolutions. The data cubes acquired by these modern sensors, referred to as satellite image time series (SITS), make it possible to precisely monitor landscape dynamics continuously for various applications such as land monitoring, natural resource management, and climate change studies. In these applications, the method of transformation of sequences of satellite images into meaningful information relies on a precise analysis and understanding of the temporal dynamics present in SITS.

While a growing remote sensing research community studies these inherently multi-temporal aspects of our Planet, the underlying processing techniques need to be presented to a broader community. Concretely, we aim to reduce this gap in this half-day tutorial by presenting and reflecting on the breadth of methodologies and applications that require time-series data. After a brief introduction to time series, the first section will focus on time-series segmentation, whereas the second section will be devoted to deep learning techniques that exploit the temporal structure of the data. In practice, the theoretical concepts will be complemented with one hands-on practical session using Google Colab notebooks in R or Python/PyTorch. 


**July 7 09:00 to 12:30 -- Room MC3.4**

|  | Time-Series Tutorial                  |
| ---            | :-:        |    
| 09:00 - 09:15 | [Part I.]({{site.baseurl}}/assets/pdf/opening.pdf) Introduction to time-series analysis                                         |
| 09:15 - 09:45 | [Part II.]({{site.baseurl}}/assets/pdf/breakdetection.pdf) Time-series segmentation and break detection                                      |
| 09:45 - 10:15 | [Part III.]({{site.baseurl}}/assets/pdf/deeplearning.pdf) Deep learning techniques for satellite image time series                                      | 
| 10:15 - 10:45 | Break                                                             |
| 10:45 - 11:55 | Practical session: (i) [break detection](https://colab.research.google.com/drive/1r7TtQSxvu-fKWDzn30fFL1Kp7w6nDGH8?usp=sharing), and (ii) [deep learning](https://colab.research.google.com/drive/1wO0jGANmwn-eAOLygl9g5hmFTGpZ8cMV?usp=sharing) |
| 11:55 - 12:00 | [Closing remarks]({{site.baseurl}}/assets/pdf/closing.pdf) |


<!--## Directions-->

### Location
[Megaron Athens International Conference Centre (MAICC)](https://maps.app.goo.gl/s5FEujS55CBfdGpb7)
More details can be found [here](https://www.2024.ieeeigarss.org/venue.php).

Room MC3.4 access at level -1:
<img src="https://2024.ieeeigarss.org/images/IGARSS_New%20General%20floorplan.svg" width="600">


<!--### Room 003-->

<!--<img src="https://breizhcrops.s3.eu-central-1.amazonaws.com/isprstutorial2022/map.png" width="600">-->

<!--<img src="{{site.baseurl}}/assets/img/map.png" width="600">-->

<!--- ([Google Colab Notebook 1](https://colab.research.google.com/drive/1ZJIJKvFefrrrlKgaWjUaq3_Kelnp9Wq5?usp=sharing)) 
 ([Google Colab Notebook 2](https://colab.research.google.com/drive/1DYZGgFfIA92gb7SaVi2ZPgmcIAc101rl?usp=sharing))
---!>

<!--
## General Description

### Time Series in Earth Observation
Dynamics on the Earth’s surface are governed by continuous temporal processes that can be observed in discrete intervals by Earth observation satellites that cover the same location on Earth at regular temporal intervals. An increase in data availability and the development of data-driven methods allow us to use new space-borne measurements to estimate the parameters of deep learning models for a variety of applications, such as vegetation modeling, climate forecasting, or precipitation nowcasting.
This tutorial covers the latest developments in deep learning techniques for time series classification with application to Earth observation. Time series classification is the task of determining a discrete class label for an unlabeled time series. Several mechanisms that often originated from related fields, like computer vision (e.g., convolutional neural networks) or natural language processing (e.g., recurrent neural networks) have proven to be useful for time series classification in the Earth observation domain. In this tutorial, we aim at providing a solid theoretical basis to understand these concepts. Practical sessions allow the participants to follow with hands-on code in Jupyter and Colab notebooks.

### Course Description

The full-day tutorial course will be partitioned into five parts: I: Introduction to Deep Learning and Time Series, II: Convolutional Neural Networks, III: Recurrent Neural Networks, IV: Self-Attention Networks, and V: Conclusions. We aim for longer breaks in between the parts that will help the participants to eat, reflect, recover and prepare for the upcoming content. Each part is separated in a theoretical presentation and a practical hands-on section where each participant engages with their own laptops using Jupyter and Colab notebooks.

#### Introduction

Introduction to deep learning and the concepts of jointly learned feature extraction and classification in the scope of end-to-end learning. A general introduction to time series data in Earth observation and outlines on the relevance of time series data for Earth observation.

#### Convolutional Neural Networks

<img src="{{site.baseurl}}/assets/img/cnn.png" width="400">

Convolutional Neural Networks are covered in the second part of the tutorial. After introducing the principle of convolutions for time series, we will implement and apply a simple temporal convolutional neural network to a remote sensing dataset. Then, some key components of the state-of-the-art convolutional neural network architectures including residual connections and inception modules are described and tested. The use of pooling layers and the concept of receptive fields are also discussed.

#### Recurrent Neural Networks

<img src="{{site.baseurl}}/assets/img/convlstm.gif" width="400">

Recurrent Neural Networks are covered first in theory and then following practical examples. In particular, the vanishing gradient problem is addressed and the two main architectures to solve this issue, i.e., long short-term memory networks and gated recurrent units, are introduced. Examples from remote sensing and text analysis are given to support understanding.

#### Self-Attention Networks

<img src="{{site.baseurl}}/assets/img/self-attention-1.gif" width="400">

Self-Attention Networks, as used in the Transformer, Bert, or GPT models, are covered in the fourth part. The concept of self-attention is introduced in a gentle manner. The relationship of attention scores to input and output time series is outlined. Practical examples from language and remote sensing time series close this part.

#### Conclusion

Conclusions. This tutorial finishes by some conclusions and a brief outlook on the current research for satellite image time series classification.

We provide a link to a public GitHub repository with Jupyter notebooks and slides. During the practical sessions, each participant is encouraged to utilize their own laptop to run the Jupyter notebooks either on their own devices or on a Google Colab Notebook using their respective Google accounts. We provide links and resources to start the Colab Notebooks from the GitHub repository and may gather additional questions with tools like sli.do or pringo.
-->
