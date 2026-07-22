# MMDL-NAI

This repository contains the datasets, feature representations, pretrained models, and source code used for the MMDL-NAI framework.

## Data

Contains the raw training and testing datasets used in this study.

## Modalities

Contains Mol2Vec features generated using a 100-dimensional pretrained Mol2Vec model. This folder also includes the GRU-based AE embedding network used to learn molecular representations for the first modality.

Contains MACCS fingerprint features and the corresponding fully connected autoencoder (FCN-AE) used for feature encoding and representation learning.

Contains graph-based molecular features extracted using a pretrained ChemProp model. The pretrained weights were obtained from:
https://zenodo.org/records/15460715/files/chemeleon_mp.pt

## Multimodal Fusion and Classification

Contains the source code for CNN-based multimodal representation learning and classification, as well as the best model used for inference and evaluation.
