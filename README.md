# Ghost transmission using physics-driven untrained neural network

Pytorch implementation of paper: High-fidelity and high-robustness free-space ghost transmission in complex media with coherent light source using physics-driven untrained neural network. The data of six analog signals and three images used in the experiments are provided.

# Requirements: 

> Anaconda 3; Python 3.8.13; Pytorch 1.7.0.

# How to use:

Step 1: create a virtual environment
```
conda create -n unnTrans
conda activate unnTrans
```

Step 2: download the required packages
```
conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cudatoolkit=11.0 -c pytorch (cuda version should be chosen according to your GPU.)
conda install jupyter
pip install matplotlib
pip install scikit-image
pip install opencv-python
```

Step 3: download and extract the ZIP file.

Step 4: Run unn-spi-13-signal.ipynb to encode a magnified analog signal into a series of amplitude-only patterns.

Step 5: Run unn-spi-13-image.ipynb to encode the 2D image information into a series of amplitude-only patterns.
