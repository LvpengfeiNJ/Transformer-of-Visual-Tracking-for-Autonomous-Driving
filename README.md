# Transformer-of-Visual-Tracking-for-Autonomous-Driving
Single Object Tracking
Including training **code** and trained **models**.

# Tracker
## TransLPF
This work presents a attention-based feature fusion network, which effectively combines the template and search region features using attention. Specifically, the proposed method includes an ego-context augment module based on self-attention and a cross-feature augment module based on cross-attention. We present a Transformer tracking (named TransT) method based on the Siamese-like feature extraction backbone, the designed attention-based fusion mechanism, and the classification and regression head.

# Results
pass

# Installation
This document contains detailed instructions for installing the necessary dependencied for TransT. The instructions have been tested on Ubuntu 18.04 system.

## Install dependencies

- Create and activate a conda environment

> conda create -n transt python=3.7
> conda activate transt

- Install PyTorch
> conda install -c pytorch pytorch=1.5 torchvision=0.6.1 cudatoolkit=10.2

- install other packages
> conda install matplotlib pandas tqdm
> 
> pip install opencv-python tb-nightly visdom scikit-image tikzplotlib gdown
> 
> conda install cython scipy
> 
> sudo apt-get install libturbojpeg
> 
> pip install pycocotools jpeg4py
> 
> pip install wget yacs
> 
> pip install shapely==1.6.4.post2


