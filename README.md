# StarGAN Reproduction and Enhancement Project

The evolution of image-to-image translation techniques has been remarkable. Prior to StarGAN, numerous research efforts achieved impressive results in this field. However, these methods had limitations, most notably the necessity to independently construct different models for each image domain pair. This approach was inherently limited in its scalability and robustness, especially when dealing with three or more multi-domains.

To tackle these challenges, StarGAN was introduced as a solution capable of performing image-to-image translation for multiple domains using a single model. In this project, we aim to reproduce and enhance the capabilities of StarGAN.

The unified model architecture of StarGAN allows simultaneous training of datasets from different domains within a single network. This translates to superior translation quality compared to pre-existing models, along with improved scalability and robustness by flexibly executing changes between domains. In our project, we reproduce and manipulate StarGAN using PyTorch. Following training using the CelebA dataset and RaFD, we examine the transformation results.

Our project also identifies and addresses areas where the performance of vanilla StarGAN could be improved. Specifically, we noticed the model struggled with generating specific classes and had difficulties in identifying geometric or structural patterns in faces. As a solution to these problems, we proposed the incorporation of self-attention mechanisms into the model. 

This project, hence, stands as a testament to the continuous evolution of StarGAN, highlighting its potential, while also proposing enhancements to further extend its application in the realm of image-to-image translations.

Please see my [Paper](./Team%2041-Paper.pdf), [Presentation](./Team%2041-PPT.pdf) for more details.
