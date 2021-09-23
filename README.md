# Big_Data_ASL_Recognition
Used Big Data and AI for ASL Recognition

### For Python(PyTorch)

## Introduction
American Sign Language (ASL) is the primary language utilized by many hard of hearing, almost deaf and hearing people in North America. It is communicated utilizing signs made with their hands, along with facial motions. It has all the necessary features of a language, with its own principles for word development and word order.

A lot of progress has been made towards developing computer vision systems that translate sign language into spoken language. As per WHO, 466 million individuals experience the ill effects of handicapping hearing loss. They gauge that by 2050, this number will increase to 900 million. A yearly worldwide expense of US $750billion is brought about because of unaddressed hearing loss. 1.1 billion youngsters (matured between 12–35 years) are in danger of hearing misfortune because of presentation to clamor in recreational settings. We need to contribute towards overcoming any barrier between the distinctive client sections inside the populace by building up a model that makes an interpretation of gesture-based communication into English letters in order. Having educated various ideas in profound learning, we concluded it would be an incredible learning experience for us as we actualize our learnings for this reason.

Hence, for our project, we have created a deep learning model by training convolutional neural networks to classify images of American Sign Language letters.


## Proposed Model:

### Network Structure:
* Input Layer: (3 ,64, 64)
* Number of convolution Layers: 5
* Number of Pooling Layers: 3
* Dropout Layers: 5
* Activation Functions: ReLU
* Linear Layer: (512, 29)

**Results:**

We were able to successfully achieve similar results as that of the pre-trained models. Our model used lesser inference time due to lesser parameters used. We fine tuned our parameters such as kernel size, stride, padding, number of neurons in each layer using hit and trial method to achieve high accuracy.

**Conclusion:**

In our project, we were successful in planning, executing, and evaluating Deep Learning Networks to enable interpretation of ASL gesture-based communication into the English language. Our custom CNN model was able to perform at par with the existing pre-trained models to accomplish test accuracy of 96.77% and test loss of 0.18%. Given the promising execution, we believe that our custom CNN model makes a critical contribution towards interpreting ASL. Going forward, we would like to further work on extending our custom model to enable translating ASL videos to English texts.

## References:

* [Resnet-18-pytorch - OpenVINO™ toolkit. (n.d.).](https://docs.openvinotoolkit.org/latest/omz_models_public_resnet_18_pytorch_resnet_18_pytorch.html)
* [Ruiz, P. (2019, April 23). Understanding and visualizing ResNets. Medium.](https://towardsdatascience.com/understanding-and-visualizing-resnets-442284831be8)
* [GoogLeNet convolutional neural network - MATLAB googlenet. (n.d.). MathWorks - Makers of MATLAB and Simulink - MATLAB & Simulink](https://www.mathworks.com/help/deeplearning/ref/googlenet.html)
* [Convolutional neural network architecture: Forging pathways to the future. (n.d.). MissingLink.ai.](https://missinglink.ai/guides/convolutional-neural networks/convolutional-neural-network-architecture-forging-pathways-future/)
* [Liuzhuang13/DenseNet. (n.d.). GitHub. ](https://github.com/liuzhuang13/DenseNet)
* [Ruiz, P. (2018, October 18). Understanding and visualizing DenseNets. Medium.](https://towardsdatascience.com/understanding-and-visualizing-densenets-7f688092391a)
* [Ogayo, P. (2019, November 14). CUDA error: Device-side assert triggered. Medium](https://towardsdatascience.com/cuda-error-device-side-assert-triggered-c6ae1c8fa4c3)
* [WHO | World Health Organization](https://www.who.int/news-room/fact-sheets/detail/deafness-and-hearing-loss#:~:text=Over%205%2 5%20of%20the%20world's,will%20have%20disabling%20hearing%20los)
