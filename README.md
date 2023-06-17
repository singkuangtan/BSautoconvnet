# BSautoconvnet

Boolean Structured Autoencoder Convolutional Deep Learning Network (BSautoconvnet)

# Main Takeaways

- Our model has only 44000+ parameters instead of millions parameters in U-net
- Use monotone Boolean algebra convolutional layers, so it does not overfit
- Achieved near perfect result of masked image reconstruction on CIFAR10 dataset 
- Able to be trained on online using Google Colab with GPU
- No data augmentations, no regularization such as weight decay and dropout 

# How to Run

Download the jupyter notebook

Open using Google Colab
[Colab](https://colab.research.google.com/)
It can also be run using a jupyter notebook

Follow the steps in the notebook, run each block of codes starting from the top to the bottom
Model can be trained in 50 epoches.

If you do not want to train the model, you can load the pretrained model (1 megabytes only).

# Model

![Network design](https://github.com/singkuangtan/BSautoconvnet/blob/main/model0.png)

# Experiment Results 

Input
![Input](https://github.com/singkuangtan/BSautoconvnet/blob/main/in.png)

Ground Truth
![Groundtruth](https://github.com/singkuangtan/BSautoconvnet/blob/main/gt.png)

Reconstructured Output
![Reconstructured Output](https://github.com/singkuangtan/BSautoconvnet/blob/main/out.png)

# Links
[BSnet paper link](https://vixra.org/abs/2212.0193)

[BSautonet paper link](https://vixra.org/abs/2212.0208)

[BSconvnet paper link](https://vixra.org/abs/2305.0166)

[BSnet GitHub](https://github.com/singkuangtan/BSnet)

[Discrete Markov Random Field Relaxation](https://vixra.org/abs/2112.0151)

[Slideshare](https://www.slideshare.net/SingKuangTan)

That's it. 
Have a Nice Day!!!
