# SiENet-Image-extrapolation
Paper:"SiENet: Siamese Expansion Network for Image Extrapolation"
# Abstract
In this paper, we propose a novel two-stage siamese adversarial model for image extrapolation, named Siamese Expansion Network(SiENet). In two stages, a novel border sensitive convolution named filling convolution is designed for allowing encoder to predict the unknown content, alleviating the burden of decoder. Besides, to introduce prior knowledge to network and reinforce the inferring ability of encoder, siamese adversarial mechanism is designed to enable our network to model covered long range feature toward the uncovered image feature.
 ![image](https://github.com/nanjingxiaobawang/SieNet-Image-extrapolation/blob/master/structure.png)
# Requirements

1.Pytorch >= 1.0

2.Python 3

3.NVIDIA GPU + CUDA 9.0

4.Tensorboard

5.Matlab

# Installation

1.Clone the code

git clone https://github.com/nanjingxiaobawang/SieNet-Image-extrapolation

2.Build Gaussian Sampling CUDA package

cd ./SieNet-Image-extrapolation/resample2d_package
python setup.py install --user


# Run 
our method is evaluated on three datasets, i.e., Cityscapes, paris street-view and beach . Single-direction evaluation is made on Scenery dataset. Smooth image
could be get by ![structure](https://github.com/RenYurui/StructureFlow）
