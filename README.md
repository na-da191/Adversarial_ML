# Adversarial_ML
The present report is a synthesis of the work carried out within the framework of the project of end of year
project , carried out within the ENSIAS, a big school of engineers specialized in Technologies of the Information
and the Communication. Its missions are the training of state engineers and research for the technological and
economic development of Morocco.
The mission we have been given is part of understanding attacks and defense adversarial machine .

## Generator samples from training

### GAN
For the different implementation in this section we used the MNIST dataset.
After training for about 30000 epochs. Below I’m showing
the generated images as the network was training, every 200 epochs


![Alt Text](https://github.com/na-da191/Adversarial_ML/blob/main/Defence/gan.gif)






### DCGAN
The difference between the simple GAN and the DCGAN, is the generator of the DCGAN uses the trans-
posed convolution (Fractionally-strided convolution or Deconvolution) technique to perform up-sampling of 2D
image size.
After training for about 4000 epochs. Below I’m showing the generated images as the network was training,
every 50 epochs.


![Alt Text](https://github.com/na-da191/Adversarial_ML/blob/main/Defence/dcgan.gif)







### WGAN
In WGAN, the discriminator does not classify the input as real or fake instead, it outputs a number.
After training for about 4000 epochs. Below I’m showing the generated images as the network
was training, every 50 epochs.


![Alt Text](https://github.com/na-da191/Adversarial_ML/blob/main/Defence/wdcgan.gif)
