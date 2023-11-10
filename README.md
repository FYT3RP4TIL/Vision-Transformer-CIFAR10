# Vision-Transformer-CIFAR10

Implementation of the ViT model

## Model Architecture

![image](https://github.com/Sudhanshu21xx/Vision-Transformer-CIFAR10/assets/113416452/69a70cfa-ec72-4030-a67a-3074d019325e)

## Project Description

### Aim

- Explore Transformer-based architectures for Computer Vision Tasks.
- Transformers have been the de-facto for NLP tasks, and CNN/Resnet-like architectures have been the state of the art for Computer Vision.
- Till date, researchers have tried using attention for Vision, but used them in conjunction with CNN.
- This project mainly discusses the strength and versatility of *vision* transformers, as it kind of approves that they can be used in recognition and can even beat the state-of-the-art CNN.


### Methodology

![image](https://github.com/Sudhanshu21xx/Vision-Transformer-CIFAR10/assets/113416452/f619907f-f452-45b8-82f2-7e0ff2a474fc)

### Transformer Encoder

![image](https://github.com/Sudhanshu21xx/Vision-Transformer-CIFAR10/assets/113416452/967a7612-d1a9-40db-9e9a-c7b83671d2a8)

## Why do we need attention mechanism?

![image](https://github.com/Sudhanshu21xx/Vision-Transformer-CIFAR10/assets/113416452/f2f90e5f-6327-4b8f-b9d8-7cc119f08f9b)

### Multi-Head Attention

![image](https://github.com/Sudhanshu21xx/Vision-Transformer-CIFAR10/assets/113416452/4d8a0f21-99ae-4222-9858-fb8dfdabca41)

## Datasets

Due to non-availability of powerful compute on Google Colab, we chose to train and test on these 2 datasets – 
- [CIFAR 10](https://www.cs.toronto.edu/~kriz/cifar.html)
- [CIFAR 100](https://www.cs.toronto.edu/~kriz/cifar.html)


### Inference from Results

- Patch size in the Vision Transformer decides the length of the sequence.
- Increasing the number of layers of the Vision Transformer should ideally lead to better results.
- Hybrid Vision Transformer performs better on small datasets compared to ViT as the initial ResNet features are able to capture the lower level features due to the locality property of Convolutions which normal ViT is not able to capture with the limited data available for training.
- PreTrained ViT performs much better than the other methods due to being trained on huge datasets and thus having learned the better representations than even ResNet since it can access much further information right from the very beginning unlike CNN.


## Future Scope

- Due to non-availability of better computing resources, the model could not be trained on large datasets which is the first and the foremost requirement of this architecture to produce very high accuracies. Due to this limitation, we could not produce accuracies as   mentioned in the project in implementation from scratch. 
- Different Attention mechanisms could be explored that take the 2D structure of images into account.

