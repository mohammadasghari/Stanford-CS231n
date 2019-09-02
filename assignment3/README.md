# Assignment 3

The goals of this assignment are as follows:

- Understand the architecture of **recurrent neural networks (RNNs)** and how they operate on sequences by sharing weights over time
- Understand and implement both **Vanilla RNNs** and **Long-Short Term Memory (LSTM)** networks.
- Understand how to combine convolutional neural nets and recurrent nets to implement an **image captioning system**
- Explore various applications of image gradients, including saliency maps, fooling images, class visualizations.
- Understand and implement techniques for **image style transfer**.
- Understand how to train and implement a **Generative Adversarial Network (GAN)** to produce images that resemble samples from a dataset.


## codes

### Q1: Image Captioning with Vanilla RNNs (25 points)

The Jupyter notebook [RNN_Captioning.ipynb](./RNN_Captioning.ipynb) will walk us through the implementation of an image captioning system on MS-COCO using vanilla recurrent networks.

### Q2: Image Captioning with LSTMs (30 points)

The Jupyter notebook [LSTM_Captioning.ipynb](./LSTM_Captioning.ipynb) will walk us through the implementation of Long-Short Term Memory (LSTM) RNNs, and apply them to image captioning on MS-COCO.

### Q3: Network Visualization: Saliency maps, Class Visualization, and Fooling Images (15 points)

The Jupyter notebook [NetworkVisualization-TensorFlow.ipynb](./NetworkVisualization-TensorFlow.ipynb) will introduce the pretrained SqueezeNet model, compute gradients with respect to images, and use them to produce saliency maps and fooling images.

### Q4: Style Transfer (15 points)

In the Jupyter notebooks [StyleTransfer-TensorFlow.ipynb](./StyleTransfer-TensorFlow.ipynb) we will learn how to create images with the content of one image but the style of another. 

### Q5: Generative Adversarial Networks (15 points)

In the Jupyter notebooks [GANS-TensorFlow.ipynb](./GANS-TensorFlow.ipynb) we will learn how to generate images that match a training dataset, and use these models to improve classifier performance when training on a large amount of unlabeled data and a small amount of labeled data. 

### Todos
 - Write what I learnt about setting this assignment (takeaway)
 - Complete Q3 to Q5 using PyTorch.
 - ...