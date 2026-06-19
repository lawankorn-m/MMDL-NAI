# MMDL-NAI

This repository contains the datasets, feature representations, pretrained models, and source code used for the MMDL-NAI framework.

## Data

Contains the raw training and testing datasets used in this study.

## Mol2Vec Modality

Contains Mol2Vec features generated using a 100-dimensional pretrained Mol2Vec model. This folder also includes the GRU-based embedding network used to learn molecular representations for the first modality.

## MACCS Text Modality

Contains MACCS fingerprint features and the corresponding fully connected autoencoder (FCN-AE) used for feature encoding and representation learning.

## ChemProp Graph Modality

Contains graph-based molecular features extracted using a pretrained ChemProp model. The pretrained weights were obtained from:
https://zenodo.org/records/15460715/files/chemeleon_mp.pt

## MMDL-NAI Representation and Classification

Contains the source code for multimodal representation learning and classification, as well as the pretrained MMDL-NAI model used for inference and evaluation.
