# Domain Adaptation for Aerial Imagery using Generative Adversarial Networks for Semantic Segmentation
This is the implementation of the master's thesis, "Domain Adaptation for Aerial Imagery using Generative Adversarial Networks for Semantic Segmentation".
## Abstract 

Segmenting aerial and satellite imagery is of great importance in many fields such as agriculture, surveillance, and city planning. With the rapid advance of deep neural networks and the rise of satellite and aerial imagery's availability, the segmenting task of aerial imagery has been intensively studied. Despite many successes of deep learning-based models, the classifier trained by data from one domain may not perform well with data from a new domain. This is called the domain adaptation problem and the main factors are various sensors, land cover, season (clear roads and covered with snow), and geography for remote sensing tasks. In this work, we deal with the domain adaptation problem of aerial imagery. We demonstrate the effectiveness of the CycleGAN-based domain adaptation method on the Inria Aerial Image Labeling Dataset, which is not tested yet to the best of our knowledge. Our method improved the segmentation performance when the model was applied to the unseen domain.

![chicago2vienna_1_6_8000](https://user-images.githubusercontent.com/37135430/199313397-2a3ecb84-3bdf-42c7-b698-2d8d7fc6cd8c.png)
![kitsap2tyrol_1_1_2300](https://user-images.githubusercontent.com/37135430/199313459-18b8287e-1b12-4a57-8f76-b7059688f8a3.png)
![chicago-styled-austin-onchicago_8](https://user-images.githubusercontent.com/37135430/199313677-becc6482-3d8c-4cf2-afe0-a39647cc19db.png)
![kitsap-styled-austin-onkitsap_1](https://user-images.githubusercontent.com/37135430/199313771-37e33ca0-455d-4b09-a9ab-0dd9e2b5066c.png)
