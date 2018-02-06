# MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN

For DCGANs, they are implemented nearly the same as mentioned in the DCGAN paper. https://arxiv.org/pdf/1511.06434.pdf

According to Ian Goodfellow in NIPS2016, convergence doesn't mean the good generating performance. DCGANs showed it.

The parameters and model of Conditional-DCGAN were saved in the folder "Conditional-DCGAN_Generator". They are in zip with segmentations because of the upload limit in GitHub, just extract "model_parameters_ckpt.zip". Afterthat, run the the Jupyter Notebook "MNIST_Conditioinal-DCGAN_Generator.ipynb" and it will retrieve the parameters. The demo of using the generator is shown in the notebook. Feel free to alter the code and generate what you want.

Trained Conditional-DCGAN output demo:
![](https://raw.githubusercontent.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/master/img_for_readme/trained_generator.jpg)

## Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/GAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/GAN.png?raw=true)

## Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cGAN.png?raw=true)

## Deep Convolutioinal Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/DCGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/DCGAN.png?raw=true)

## Deep Convolutioinal Conditional Generative Adversarial Networks
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cDCGAN.gif?raw=true)
![](https://github.com/DHKLeung/MNIST_GAN_DCGAN_Conditional-GAN_Conditional-DCGAN/blob/master/img_for_readme/cDCGAN.png?raw=true)

## Development Environment
* Ubuntu 14
* Jupyter Notebook
* TensorFlow(GPU) 1.4.1
* NumPy 1.14.0
* Pandas 0.21.1
* SciPy 1.0.0
* ImageIO 2.2.0
* Matplotlib 2.1.1

## Tricks
* Adjusting learning rate seperately for Discriminator and Generator
* Label Smoothing
