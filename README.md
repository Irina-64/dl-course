# Deep Learning with Catalyst [![Stepik](https://img.shields.io/badge/DLS-Stepik-success)](https://stepik.org/course/83344/syllabus) [![Slack](https://img.shields.io/badge/Catalyst-slack-success)](https://join.slack.com/t/catalyst-team-core/shared_invite/zt-d9miirnn-z86oKDzFMKlMG4fgFdZafw)

[![dls-catalyst-course](https://github.com/catalyst-team/catalyst-pics/blob/master/pics/catalyst-dl-course-poster-eng.png)](https://github.com/catalyst-team/dl-course)

This is an open deep learning course made by [Deep Learning School](https://dlschool.org), [Tinkoff](https://tinkoff.ru), and [Catalyst team](https://github.com/catalyst-team). 
Lectures and practice notebooks located in ```./week*``` folders. Homeworks are in ```./homework*``` folders.

## Syllabus

- week 1: Deep learning intro
  - Deep learning – introduction, backpropagation algorithm. Optimization methods.
  - Neural Network in numpy.
- week 2: Deep learning frameworks
  - Regularization methods and deep learning frameworks.
  - Pytorch basics & extras.
- week 3: Convolutional Neural Network
  - CNN. Model Zoo.
  - Convolutional kernels. ResNet. Simple Noise Attack.
- week 4: Object Detection, Image Segmentation
  - Object Detection. (One, Two)-Stage methods. Anchors.
  - Image Segmentation. Up-scaling. FCN, U-net, FPN. DeepMask.
- week 5: Metric Learning
  - Metric Learning. Contrastive and Triplet Loss. Samplers.
  - Cross Entropy Loss modifications. SphereFace, CosFace, ArcFace.
- week 6: Autoencoders
  - AutoEncoders. Denoise, Sparse, Variational.
  - Generative Models. Autoregressive models.
- week 7: Generative Adversarial Models
  - Generative Adversarial Networks. VAE-GAN. AAE.
  - Energy based model.
- week 8: Natural Language Processing
  - Embeddings.
  - RNN. LSTM, GRU.
- week 9: Attention and transformer model
  - Attention Mechanism.
  - Transformer Model.
- week 10: Transfer Learning in NLP
  - Pretrained Transformers. BERT. GPT.
  - Data Augmentation in Texts. Domain Adaptation.
- week 11: Recommender Systems
  - Collaborative Filtering. FunkSVD.
  - Neural Collaborative Filtering.
- week 12: Reinforcement Learning for RecSys
  - Reinforcement Learning. DQN Algorithm. 
  - DDPG Algorithm. Wolpertinger.
- week 13: Extras
  - Research & Deploy.
  - Config API. Reaction.
  
## Environment

### Anaconda setup
```bash
# setup - env
conda create -n catalyst-dl python=3.7 anaconda
source activate catalyst-dl
conda remove nb_conda_kernels -y
conda install -c conda-forge nb_conda_kernels -y
conda install notebook jupyter nb_conda -y
conda remove nbpresent -y

# setup - jupyter
jupyter notebook password

# jupyter run
jupyter notebook --no-browser --ip 0.0.0.0 --port 8888
```

### Requirements
```bash
pip install -U catalyst==21.04.2 torch==1.8.0 albumentations==0.5.0
```

## Course staff & contributors

- [@AlexeySh](https://github.com/AlekseySh)
- [@artek0chumak](https://github.com/artek0chumak)
- [@elephantmipt](https://github.com/elephantmipt)
- [@Inkln](https://github.com/Inkln)
- [@lordofprograms](https://github.com/lordofprograms)
- [@Scitator](https://github.com/Scitator)
- [@zelcookie](https://github.com/zelcookie)

