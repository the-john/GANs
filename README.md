# GANs & MNIST Trained Sample Code

In this repository I've accumulated a bunch of White Papers and publications related to GANs (*Generative Adversarial Networks*).  

  - My hope is that, over time, I will be able to walk through all of these publications.  GitHub is a cool place where I should be able to gain access to these publications from wherever.

I also have some sample code in here.  It is a project that I did in my Udacity Deep Learning Nano Degree training.  It takes in hand written characters of numbers from the MNIST data set and generates its own numbers from noise.  Pretty cool.

## Publications

- [Adversarial_Feature_Learning_1705_11122.pdf](https://github.com/the-john/GANs/blob/master/Adversarial_Feature_Learning_1705_11122.pdf)
- [Augmented_CycleGAN_1802_10151.pdf](https://github.com/the-john/GANs/blob/master/Augmented_CycleGAN_1802_10151.pdf)
- [Batch_Normalization_1502_03167.pdf](https://github.com/the-john/GANs/blob/master/Batch_Normalization_1502_03167.pdf)
- [CycleGAN_Face_off_1712_03451.pdf](https://github.com/the-john/GANs/blob/master/CycleGAN_Face_off_1712_03451.pdf)
- [Cycle_GAN_1703_10593.pdf](https://github.com/the-john/GANs/blob/master/Cycle_GAN_1703_10593.pdf)
- [Deep_Convolutional_Generative_Adversarial_Networks_1511_06434.pdf](https://github.com/the-john/GANs/blob/master/Deep_Convolutional_Generative%20Adversarial%20Networks_1511_06434.pdf)
- [Deep_Residual_Learning_for_Image_Recognition_1512_03385.pdf](https://github.com/the-john/GANs/blob/master/Deep_Residual_Learning_for_Image_Recognition_1512_03385.pdf)
- [Generative_Adversarial_Nets_1406_2661.pdf](https://github.com/the-john/GANs/blob/master/Generative_Adversarial_Nets_1406_2661.pdf)
- [Generative_Visual_Manipulation_on_the_Naural_Image_Manifold_1609_03552.pdf](https://github.com/the-john/GANs/blob/master/Generative_Visual_Manipulation_on_the_Naural_Image_Manifold_1609_03552.pdf)
- [High_Resolution_Image_Synthesis_and_Semantic_Manipulation_1711_11585.pdf](https://github.com/the-john/GANs/blob/master/High_Resolution_Image_Synthesis_and_Semantic_Manipulation_1711_11585.pdf)
- [Image_to_Image_Translation_with_Conditional_Adversarial_Networks_1611_07004.pdf](https://github.com/the-john/GANs/blob/master/Image_to_Image_Translation_with_Conditional_Adversarial_Networks_1611_07004.pdf)
- [Least_Squares_GAN_1611_04076.pdf](https://github.com/the-john/GANs/blob/master/Least_Squares_GAN_1611_04076.pdf)
- [PairedCycleGAN_Chang-CVPR-2018.pdf](https://github.com/the-john/GANs/blob/master/PairedCycleGAN_Chang-CVPR-2018.pdf)
- [Recurrent_Batch_Normalization_1603_09025.pdf](https://github.com/the-john/GANs/blob/master/Recurrent_Batch_Normalization_1603_09025.pdf)
- [Skip_Connections_1608_04117.pdf](https://github.com/the-john/GANs/blob/master/Skip_Connections_1608_04117.pdf)
- [Unpaired_Image_to_Image_Translation_using_Cycle_Consistent_Adversarial_Networks_1703_10593.pdf](https://github.com/the-john/GANs/blob/master/Unpaired_Image_to_Image_Translation_using_Cycle_Consistent_Adversarial_Networks_1703_10593.pdf)
- [Wasserstein_GAN_1701_07875.pdf](https://github.com/the-john/GANs/blob/master/Wasserstein_GAN_1701_07875.pdf)
- [improved-training-techniques.pdf](https://github.com/the-john/GANs/blob/master/improved-training-techniques.pdf)

## Additional Assets

There is a [/asset/](https://github.com/the-john/GANs/tree/master/assets) folder that contains graphics to support the jupyter notebook files used for the sample code.

There is a [/generative-models-master](https://github.com/the-john/GANs/tree/master/generative-models-master) folder holds a bunch of really good stuff.
  - 20 different GAN models
  - 5 Variational Autoencoders
  - 2 Restricted Boltzmann Machines
  - A Helmholtz Machine

    Please refer to the README.md file included for details on Dependencies in this folder
    
## MNIST_GAN Sample Code
There is some useful sample code in the jupyter notebook [MNIST_GAN_Solution.ipynb](https://github.com/the-john/GANs/blob/master/MNIST_GAN_Solution.ipynb).

This is a simple GAN that is trained on the MNIST dataset.  The idea is to be able to generate new handwritten digits from noise.

Here we create Generator and Discriminator networks, generate a latent vector from latent space, and create a model.  An interesting thing about this code is the ability to quickly start playing with hyperparameters to see the effects.  
