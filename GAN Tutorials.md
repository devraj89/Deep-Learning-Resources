Here I am listing all the resources I am using to learn about GAN's and their implementations 

I will be mostly focussing on the Pytorch learning framework 

[1] GAN general implementations

https://github.com/znxlwm/pytorch-generative-model-collections

https://github.com/wiseodd/generative-models

https://github.com/eriklindernoren/PyTorch-GAN

https://github.com/sunshineatnoon/Paper-Implementations

[2] WGAN and WGAN Improved 

https://github.com/martinarjovsky/WassersteinGAN

https://github.com/caogang/wgan-gp

Conditional WGAN and Improved WGAN
-------------------------------------
https://www.reddit.com/r/MachineLearning/comments/8hrfb4/p_implementation_of_conditional_wgan_and_wgan_in/

https://github.com/jalola/improved-wgan-pytorch

https://github.com/shaform/DeepNetworks/blob/master/notebooks/GAN%20-%20MNIST%20WACGAN-GP.ipynb

https://github.com/fairytale0011/Conditional-WassersteinGAN

http://blog.richardweiss.org/2017/07/21/conditional-wasserstein-gan.html

https://github.com/ririw/ririw.github.io/blob/master/assets/conditional-wasserstein-gans/Improved.ipynb

[3] ACGAN -- two implementations are available 

-- does not use class information on D and G as inputs

https://github.com/gitlimlab/ACGAN-PyTorch 

https://github.com/znxlwm/pytorch-generative-model-collections/blob/master/ACGAN.py 

doubt : should it use class information ? No we should not according to the paper. But in the implementations above it seems that class information is being used in the G to generate samples.

https://github.com/znxlwm/pytorch-generative-model-collections/blob/master/ACGAN.py#L188

https://github.com/gitlimlab/ACGAN-PyTorch/blob/master/main.py#L203

[4] GAN and DCGAN : https://github.com/znxlwm/pytorch-MNIST-CelebA-GAN-DCGAN

CGAN and CDCGAN : https://github.com/znxlwm/pytorch-MNIST-CelebA-cGAN-cDCGAN

[5] GAN HACKS

https://github.com/soumith/ganhacks

Improved Techniques for Training GANs -- https://github.com/Sleepychord/ImprovedGAN-pytorch

[6] Coupled GAN COGAN

https://github.com/mingyuliutw/CoGAN/tree/master/cogan_pytorch/src -- original authors

[7] Disco GAN

https://github.com/carpedm20/DiscoGAN-pytorch

https://github.com/SKTBrain/DiscoGAN -- original authors

https://github.com/sunshineatnoon/Paper-Implementations/tree/master/DiscoGAN

[8] Adverarially learned inference !

https://arxiv.org/pdf/1606.00704.pdf

https://github.com/IshmaelBelghazi/ALI -- original authors

https://ishmaelbelghazi.github.io/ALI/ -- original authors

*** NOTE the training part of the GAN is different in both ***

*** To note which is the correct one I have to go through the original authors implementation***

*** Looking at algorithm 1 in paper I found that ozansener's implementation is matching ***

https://github.com/ozansener/GAN/tree/master/bigan -- another implementation

https://github.com/wiseodd/generative-models/tree/master/GAN/ali_bigan

[9] Semi supervised GAN's

https://arxiv.org/pdf/1606.01583.pdf [Semi-Supervised Generative Adversarial Network]

https://github.com/eriklindernoren/PyTorch-GAN/blob/master/implementations/sgan/sgan.py -- matches with that of the paper

https://github.com/Vetal1977/semi-supervised-gan

https://arxiv.org/pdf/1511.06390.pdf [UNSUPERVISED AND SEMI-SUPERVISED LEARNING WITH CATEGORICAL GANs]

https://github.com/xinario/catgan_pytorch
*** Check out the different entropy regularizations used ***

[10] Energy based GANs

https://github.com/eriklindernoren/PyTorch-GAN/tree/master/implementations/ebgan

https://github.com/1Konny/EBGAN-pytorch








****************************************************************************************
****************************************************************************************
To study and understand further 
-- infogan**(difficult to understand -- look into code also) 
--- bicycle gan (look into code to understand KL div loss)
-- Energy based GAN 
-- Boundary Seeking GAN
-- adversarial auto encoders
-- https://github.com/kimiyoung/ssl_bad_gan & https://arxiv.org/pdf/1705.09783.pdf
-- Categorical GAN unsupervised & semi supervised 
https://github.com/xinario/catgan_pytorch
****************************************************************************************
****************************************************************************************

Variational Auto-encoders 
Let me first read it up from different blogs so that I must first understand it 
- http://kvfrans.com/variational-autoencoders-explained/
- https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf 
- https://jaan.io/what-is-variational-autoencoder-vae-tutorial/
- https://wiseodd.github.io/techblog/2016/12/10/variational-autoencoder/ (KERAS CODE)
- https://wiseodd.github.io/techblog/2017/01/24/vae-pytorch/ (PYTORCH CODE)
- https://arxiv.org/pdf/1606.05908.pdf
- https://github.com/pytorch/examples/tree/master/vae (OFFICIAL CODE)
- https://vxlabs.com/2017/12/08/variational-autoencoder-in-pytorch-commented-and-annotated/ (OFFICIAL CODE ANNOTATED)



