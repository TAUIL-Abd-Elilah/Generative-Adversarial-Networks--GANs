# The original GAN:
A clean, simple and readable implementation of the original GAN in PyTorch. I've tried to replicate the original paper as closely as possible, so if you read the paper the implementation should be pretty much identical.
You can find a video where I explain the code here: https://www.youtube.com/watch?v=iyUv7QyMAIw&list=PL3uMf2H28qwdtxJPWwOrYd6n_ztY_5jAf

# ProGAN
ProGAN is one of the revolutionary papers that was the first to generate high-quality images

In this video I walkthrough the original paper and expain its goals, key components, and how it really works: https://www.youtube.com/watch?v=UTr89QpeV2A&t=372s

In this video I implemented ProGAN from scratch in PyTorch to generate fashion https://www.youtube.com/watch?v=ya4XI9S_VLY&t=4648s trying to make it compact but a goal is also to keep it readable and understandable.
Specifically the key points implemented are:
1) Progressive growing (of model and layers)
2) Minibatch std on Discriminator
3) Normalization with PixelNorm
4) Equalized Learning Rate.

Dataset I used in the code: https://www.kaggle.com/datasets/tauilabdelilah/women-clothes


# StyleGAN
StyleGAN from the paper: https://arxiv.org/abs/1812.04948 is one of the best GANs today.

In this video I walkthrough the original paper and expain its goals, key components, and how it really works: https://www.youtube.com/watch?v=8HKHj_CYpaE&t=96s

In this video I implemented StyleGAN from scratch in PyTorch to generate fashion https://www.youtube.com/watch?v=X8k96xfZXwo trying to make it compact but a goal is also to keep it readable and understandable.
Specifically the key points implemented are:
1) Noice apping network
2) AdaIN (Adaptive Insctance Normalisation)
3) Progressice growing

Dataset I used in the code: https://www.kaggle.com/datasets/tauilabdelilah/women-clothes
